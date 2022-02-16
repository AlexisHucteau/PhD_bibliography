# Plan Comité de thèse

***In silico investigations épigénomiques et fonctionnelles sur la résistance aux IDH inhibiteurs dans les leucémies aiguë myéloïde***

## Listes des figures



## I - Points à aborder

## Context & Etat de l'art

* Voie différenciation hématopoïétique
* Dérégulations dans ces voies --> LAM
* Mutation IDH
* Conséquences de cette mutation
* Inhibiteurs IDH
* Résultats Lucille sur IDH inhibiteur

## Méthodes Bioinfo

* Définition clinique de la réponse au traitement
* Analyse computationnelle de transcriptomes de patients
* Présentation de la prédiction d'activité de TF
* Utilisation de réseaux d'interaction
* Mesure d'influence de noeuds

## Résultats Bioinfo

* Résultats
* RELA
* RELA en général
* RELA dans les LAM
* MYC
* MYC en général
* MYC dans les LAM
* Analyse des lignées cellulaires HL60 et Molm14
* Différences entre les deux lignées
* On retrouve les gènes de notre analyse de données in vivo

## Nouvelle question

* Deux lignées Bon/Mauvais répondeur ?
* Besoin de caractériser les lignées

## Methodes in vitro

* Expérimentations in vitro
* Culture cellulaire
* Design experiments
* Types de manips
* Scenith
* Facs
* Marqueurs de différenciation
* Quantification protéiques

## Résultats in vitro

* Résultats

## Conclusion

* Prochaines étapes

## II - Suite logique

LAM ? --> hématopoïèse --> Dérégulations --> LAM  
Type de LAM --> Mutation IDH --> IDH --> IDH muté  
IDH muté dans les LAM --> Inhibiteur IDH --> Résultats Lucille  
Ma question --> Qu'est ce qui différencie bon et mauvais répondeur d'un point de vue transcriptionnel ? --> Analyse de données transcriptomiques    

-----------
Les données --> Définition réponse clinique  
Présentation analyses bioinfo transcription --> RNAseq --> Normalisation --> DEG  
Problème avec mRNA --> prédiction activité TF --> Résultats  
Analyse Résultats --> mise en relation via réseau d'interaction --> REACTOME & Dorothea  
Mesure d'influence de noeuds --> Degré --> Page rank --> EigenValue --> Résultats

----------
Mise en évidence de RELA et Myc --> Rela? --> Rela dans les LAM  
Myc? --> Myc dans les LAM --> dans les lignées cellulaires ?  
HL60? --> Molm14R132? --> Résultats différents --> Rela et myc? --> Caractériser HL60 et Molm14  

----------
Expérimentations in vitro --> Culture cellulaires --> Design manips  
Différents read-outs --> scenith? --> Facs --> marqueur de diffs  
Quantification des protéines --> WB? --> Résultats  

-----------
Résultats? --> relation avec RELA Myc et la réponse --> Futur

---------

## III - Diapo

* 1 - Titre
* 2 - Sommaire

### 3 - Contexte et état de l'art

* 4 - Voie de différenciation des cellules hématopoïétique
* 5 - Dérégulations de la voie myéloïde
* 6 - LAM
* 7 - Type de LAM
* 8 - LAM & IDHm
* 9 - IDH
* 10 - Mutation IDH
* 11 - Mutation IDH dans les LAM
* 12 - Inhibiteur IDH
* 13 - Résultats de Lucille
* 14 - Ma question

### 15 - Méthodes Bioinfo

* 16 - Données Koichi
* 17 - Définition clinique de la réponse au traitement
* 18 - Analyse computationnelle (normalisation et DEG)
* 19 - Problème avec l'exp génique
* 20 - Prédiction TF activity
* 21 - Résultats
* 22 - Problème TF --> trop de cibles
* 23 - Utilisation de réseau
* 24 - Reactome network
* 25 - Mesure d'influence Degré
* 26 - EigenValue et Page rank

### 27 - Résultats

* 28 - Noeuds les plus influents
* 29 - RELA?
* 30 - Rela dans les LAM
* 31 - MYC?
* 32 - MYC dans les LAMs
* 33 - Jeu de données in vitro
* 34 - HL60?
* 35 - Molm14?
* 36 - Résultats
* 37 - Besoin de caractériser HL60 et Molm14

### 38 - Méthodes in vitro

* 39 - Culture cellulaires
* 40 - Design manips
* 41 - Scenith
* 42 - Marqueurs de différenciation
* 43 - Rhod2
* 44 - Quantification des protéines
* 45 - Bcl2? PGC1a?

### 46 - Résultats

* 47 - Résultats Facs Marqueurs de diff
* 48 - Rhod2
* 49 - Scenith
* 50 - Quantif prot

### 51 - Perspective et futur

* 52 - Bioinfo --> Methylation et épigénome
* 53 - In vitro --> Replica & autres modèle de lignées cell

### 54 - Conclusion

* 55 - In silico & in vivo
* 56 - Liste connaissances acquises
  * Analyse DNA methylation
  * Analyse Transcription
  * Prediction TF activité
  * Network analysis
  * RNA splicing
  * Culture cell
  * WB
  * Facs
  * Scenith
* 57 - Posters
  * JOBIM 2020
  * International Symposium
  * CICOR
  * JOBIM 2021
  * Cancer cell symposium
* 58 - Apprentis chercheurs

## IV - Text

### Diapo 1

Hello! So I'll present my project and what I've done during this first year. This thesis is possible thanks to the INSERM, the Laboratoire d'excellence Toulouse Cancer Labex Toucan and the University of Toulouse Paul Sabatier. I'm also part of the CARe program but it's pretty recent.

### Diapo 2

To explain my project, I will present the cancer I working on with its specificities and what is the problematique I'm trying to answer.
I'll show you my in silico analyses and explain how I proceed. What I have found.
Then, I'll present my in vitro analyses that are a kind of validation of the previous results.
Finally, I'll talk about the perspectives in term of in silico and in vitro analysis and do a recap of what I've learn and what I've done as a PhD student in term of communications.

### Diapo 3

So the context of my PhD. The acute myeloid leukemia and the gene Isocitrate dehydrogenase.

### Diapo 4

The acute myeloid leukemia is a blood cancer that takes place during the haematopoiesis. The normal haematopoiesis, is the process that generates all the mature blood cells circulating in the blood from a single stem cell that resides in the bone marrow.
It's in this context that occurs different cancer depending the lineage impacted like B-ALL, T-ALL and AML.

### Diapo 5

Clinically, AML is associated with a poor outcome and declines with age. That disease lacked of novel therapies depuis une vingtaine d'années, surtout pour les patients qui n'ont pas les prérecquis pour recevoir une chimiothérapie intensive. Une combinaison a été récemment acceptée pour traiter ces patients mais il y a un manque cruel de traitement pour passer outre les résistance et les rechutes.

### Diapo 6

Des analyses génomiques et cytogéniques ont permis d'identifier des mutations qui induisent ces résistances ou des rechutes. Nous avons la mutation FLT3-ITD mais aussi les mutations des gènes IDH1 et IDH2. Mon projet se focalise sur ces mutations d'IDH.

### Diapo 7

Pour comprendre pourquoi ces mutations sont de mauvais prognostique, il faut d'abord comprendre les fonctions de ces deux protéines.
IDH1 et IDH2 sont des gènes métaboliques qui convertissent l'isocitrate en alpha-ketoglutarate. Cette réaction est importante car faisant partie de cycle de Krebs et productrice de NADPH.

### Diapo 8

 Mutée, la protéine va réutiliser cet alpha-kétoglutarate et ce NADPH pour le transformer en D-2-hydroxyglutarate. Cette production anormale de cette molécule que l'on appellera 2HG, entraine des reprogrammations transcriptionnelles, épigénétiques, des biais des différenciation ainsi qu'une susceptibilité des cellules cancéreuses aux inhibiteurs mitochondriaux.

### Diapo 9

Une récente étude a démontré que les patients atteint de LAM IDHm présentent un métabolisme oxydatif mitochondrial exacerbé par une induction du facteur de transcription CEBPa via des changement de méthylation d'histones. Des traitements contre ces mutations ont été mises au point et acceptée, cependant, il reste des résistances à ces traitememtns et comme on peut le voir, malgré une réduction du 2HG, on retrouve ce phénotype d'hyper activité mitochondriale.

### Diapo 10

Mon project est donc d'investiguer sur cette résistances aux traitements aux IDHm inhibiteurs. Quels sont les gènes dérégulés ou dont l'activité varie entre avec la réponse aux traitements et quel est le rôle de l'épigénome ?

### Diapo 11

Pour répondre à ces questions, je me suis penché sur un dataset de données RNAseq et DNA methylation de patient LAM ayant une mutation sur IDH1 ou 2. Ces patients ont notemment reçu un traitement à différents inhibiteurs de ces mutations et une classification clinique a pu être faite. J'ai pu regrouper les patients selon leur réponse clinique au traitement. Les mauvais répondeurs sont les patients qui, après traitements, ont une maladie stable ou en progression. Les bons répondeurs sont ceux achevant une rémission complète.

A partir de ces données et afin de pouvoir déterminé en amont quels sont ceux qui vont répondre ou pas, j'ai comparé les patients à baseline leurs données d'expression des génique mais aussi de methylation.

### Diapo 12

Cependant, je vais vous montrer uniquement les résultats de mes analyses de RNAseq.
J'ai donc analyser ces données mais au lieu d'analyser uniquement l'expression génique pour savoir quels sont les gènes dont l'expression différents entre les deux groupes j'ai utilisé une méthode pouvant inférer l'activité des facteurs de transcription.

### Diapo 13
