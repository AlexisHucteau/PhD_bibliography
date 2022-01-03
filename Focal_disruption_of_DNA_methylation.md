# Focal disruption of DNA methylation dynamics at enhancers in IDH-mutant AML cells

## Astract

Dans les LAM IDH1 ou IDH2 mutant, on retrouve une hyperméthylation de l'ADN. En analysant des données de séquençage du génome entier par méthode de conversion au bisulfite, ils ont trouvé environ 4000 régions local qui était uniquement hyperméthylés dans les LAM IDHm comparé aux cellules normales CD34+. Les cellules CD34+ étant des cellules souches hématopoiétique. Ces régions semblent modestement hyperméthylées chez les TET2 mutés et leur niveau de 5-hydroxymethylation diminué dans les TET2 et IDH mutants.  
La 5-hydroxymethylation correspond à une modification épigénétique d'une base nucléique via méthylation puis hydroxylation.   
![TET2](Pictures/TETs_et_methylation.jpg)  
Comme la figure le montre, les TETs convertissent les 5-methylcytosine en ce 5-hydroxymethylcytosine qui sera ensuite oxydé en 5-formylcytosine. Un niveau de 5-hydroxymethylcytosine faible représente une absence d'activité des protéines TETs.  
Cette diminution reflète donc une inhibition des TETs par la mutation des IDHs mais aussi de celle des TETs.   
Les régions retrouvées hyperméthylés dans les IDHm sont faiblement méthylés dans les cellules CD34+. Comme l'absence de TETs engendre une méthylation et qu'avec les TETs l'ADN n'est pas méthylé, cela implique que ces régions de l'ADN sont le siège d'une méthylation/démethylation active. Lorsque le gène impliqué dans la méthylation DNMTs est muté, l'ADN est significativement moins methylé. Cela implique les DNMTs dans ce phénotype hyperméthylés des IDHm.  
Les hypermethylations retrouvés dans les LAM IDHm semblent associées à des enhancers de gènes impliqués dans l'hématopoiétiese normal et dans les LAM comme MYC et ETV6.  
Pour résumer, les mutations d'IDH dans les LAM semblent créer un déséquilibre dans la balance methylation/déméthylation qui a pour conséquences des dérégulation d'enhancer de gènes impliqués dans la pathogénèse des LAM.

## Results

### Les échantillons de LAM IDH1/2 mutés sont hyperméthylés dans des régions faiblement méthylés chez les cellules souches CD34+.

Ce résultat provient d'une analyse de 51 échantillons primaires de LAM dont 15 sont IDHm (7 IDH1 et 8 IDH2) et de 6 échantillons sains de cellules primaires CD34+.  
![pictures/Focal_fig1.1](Pictures/Focal_fig1.1.png)  
Basés sur la méthylation de ces échantillons, ils ont retrouvé des clusters dépendants des mutations IDH/TET et DNMTs totalement écartés des échantillons sains CD34+.  
![pictures/Focal_fig1.2](Pictures/Focal_fig1.2.png)  
On remarque aussi un phénotype particulier des LAM sans mutation que ce soit IDH TET ou DNMTs mais le cluster IDH semble unique.  

Pour dire si la mutation d'IDH a un effet global sur la méthylation de l'ADN ou s'il est dépendant du contexte, ils ont analysé les niveaux de méthylation dans des régions définies par des état particuliers de la chromatines chez les progéniteurs et cellules souches hématopoiétiques.  
![Pictures/Focal_fig1.3](Pictures/Focal_fig1.3.png)  

Ils ont ensuite utilisé un logiciel appelé ChromHMM utilisant un modèle mutlivarié caché de Markov. Ce logiciel permet à partir de données liées à la chromatine comme des données de ChIP-seq de modifications d'histones de découvrir de nouveaux "schémas" combinatoires et spatiaux récurrents. Pour plus de détails, l'article sur ChromHMM : [Discovery and characterization of chromatin states for systematic annotation of the human genome](https://alexishucteau.github.io/PhD_bibliography/Discovery_and_characterization_of_chromatin_states_for_systematic_annotation_of_the_human_genome)  

Ces analyses ont pu montré que la chromatine dans un état quiescent et réprimée (donc où la transcription n'a pas lieu) ont des niveaux de méthylation plus faible dans les cellules de LAM comparées aux cellules CD34+ alors que les régions bivalentes (enrichies en CGIs (Ilots de CpGs)) semblent hyperméthylées.  

De plus, la méthylation des enhancers et des régions proches des sites de début de transcription regroupent les échantillons d'IDHm. La méthylation de ces deux sites sont significativement plus élevée dans les échantillons IDHm comparée à celle des échantillons CD34+ et LAM IDHwt.

![pictures/Focal_fig1.4](Pictures/Focal_fig1.4.png)

Ce résultat se retrouve aussi de manière global mais pas significativement dans les ilots de CpGs.  

Pour aller plus loin, ils se sont intéressés aux régions différentiellement methylés.

![DMR](Pictures/Focal_fig1.5.png)

Ils ont donc comparé les différents sous types de LAM avec les cellules normales hématopoiétiques CD34+. Tous les DMRs (Régions différentiellement méthylées) dans les IDHm le sont de manières hyperméthylées comparées aux CD34+.  

De plus, ces régions semblent particulièrement déméthylées dans les cellules normales CD34+.

![DMR density](Pictures/Focal_fig1.6.png)

### Les modifications de méthylation spécifiques aux IDHm sont distincts de l'hyperméthylation des ilots de CpGs associés à la LAM et sont influencés par le type de mutation d'IDH.

Ils ont ensuite voulu définir les locis differemment methylés chez les IDHm des CD34+ qui ne le sont pas dans les autres types de LAM.

![DMR_IDH1](Pictures/Focal_fig2.1.png)

Ils ont donc défini 4388 et 2552 DMR spécifiques respectivement aux mutations IDH1 et IDH2. Une fois de plus, ces zones semblent avoir un niveau de méthylation inférieur à 0.3 chez les CD34+ ou cellules matures myeloides.  

Ils ont aussi retrouvé un recoupement important des DMR associées aux deux mutations.

![DMR_IDHm](Pictures/Focal_fig2.2.png)

![DMR_E](Pictures/Focal_fig2.3.png)
