# DSS (Dispersion Shrinkage for Sequencing data)

[HTML file](https://bioconductor.org/packages/release/bioc/vignettes/DSS/inst/doc/DSS.html)

Differential analysis on high-thoughput sequencing data.

Problématique : Nombre de replica biologique faible due aux coûts élevés.  
--> Estimations non stables de la variance dans un groupe et par conséquence résultats non désirables de l'hypothèse de départ.  
Des méthodes de rétrécissage de la variance on été utilisées dans des analyses d'expression génique. Ces méthodes sont basé sur des modèles hiérarchique Bayesian.

> Modèle hiérarchique bayésienne: modèle statistique écrit à plusieurs niveaux (forme hierarchique) qui estime les paramètres de la distribution postérieure à l'aide de la méthode bayésienne.  
> > L'inférence bayésienne est une méthode d'inférence statistique dans laquelle le théorème de Bayes est utilisé pour mettre à jour la probabilité d'une hyporthèse à mesure que davantage de preuves ou d'informations deviennent disponibles.  
> > > Dans la théorie des probabilité et les statistiques, le théorème de Bayes décrit la probabilité d'un événement basée sur une connaissance préalable des conditions qui pourraient être liées à un évènement.  
> > > Problème de santé augmentant avec l'age -> Bayes -> évalue le risque d'un individu d'age x d'avoir pb de santé. (P(A|B) = (P(B|A)\*P(A))/P(B))  
***En gros, prédire un score à partir de connaissance de base et de probabilité sachant que tel élément est dans tel état***

La connaissance de base étant les variances spécifiques aux gènes comme base d'information partagée entre tous les gènes.  

Les données de RNA seq et BS seq sont des counts et on doit donc modéliser des distributions discrètes. La variance dépend de la moyenne ce qui implique que la variance de l'échantillon ne compte pas comme une variation biologique et que le rétrécissement ne peut pas être appliqué aux variances directement.

DSS assume que les données de count suivent des distribution beta-binomial et paramètre ces distributions par une moyenne et un dispersion. La dispersion représentant la variation biologique de réplicats dans un groupe et joue un role central dans les différentes analyses.

DSS a implémenté une série d'algoritmes de détections de DM basé sur la méthode de dispersion du rétrécissement suivi par un test de Wald pour chaque CpG.

# Using DSS for BS-seq differential methylation analysis

La détection de DM est basée sur un test de Wald dépendant des variations biologique (soit le paramètre de dispersion) et la profondeur de séquençage. Une partie de l'algorithm sert donc à estimer ce paramètre de dispersion à travers la méthode de rétrécissement basé sur le modèle hiérarchique Bayesian.

DSS a besoin de bsseq.

## Input data preparation

Les données doivent être de type :  

| chromosome number | genomic coordinate | total number of reads |  and number of reads showing methylation |
|------|------|------|------|
| chr | pos | N | X |
