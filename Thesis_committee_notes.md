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

Clinically, AML is associated with a poor outcome and declines with age. That disease lacked of novel therapies patients for 20 years and more particularly for patients wich have physician assessment that do not favor into intensive chemotherapy. Here is a schema of factors that are involved or determine what should be done. A new combinaison of therapies have been recently acccepted notably for this group of patients but there is a crutial needs of novel therapies to bypass relapse or resistance.

### Diapo 6

As you can see on this graph, the proportion of relapse is close to 40% and the majority of them will not survive to this relapse. And we can also notice the patients that do not have any remissions.

### Diapo 7

A proportion of relapse and refractory AML are due to the mutation of IDH.
IDH1 and IDH2 are deux metabolic genes that convert isocitrate into alpha-ketoglutarate. This reaction is very important as a part of the Krebs cycle and produces NADPH. The two genes are different by their localisation. IDH1 is in the cytoplasm and IDH2 is in the mitochondria.

### Diapo 8

 So there is the first reaction. And mutated, the protein will use the a-KG and NADPH to synthetise D2hydroxylglutarate.

### Diapo 8.2

 This abnormal production of this oncometabolite that we will call 2HG, provocs transcriptional, epigenomic reprograming, but also differenciation biais and mitochondrial inhibitor susceptibility.

### Diapo 9

So the question I will try to answer or I'm investigating is :
What are the key genes that protect or explain the differences of response to that terapies?
Model that resistance to predict the patient outcome to that therapy.

### Diapo 10

To investigate as a computational biologist, I analysed different set of data I will present. And made some analysis I'll try to explain like differencial gene expression, Transcription factor activity, network analysis and DNA methylation.

### Diapo 11

One of the dataset I use came from a public dataset from """". It's a cohort of AML patients harbouring IDH1 or IDH2 mutation. They all received IDHm respective inhibitor. The data available are RNAseq at baseline and at relapse. I choose to compare the ones that are good responders to that therapy. In clinical terms, that had a complete remissions to bad responders that had a progressive disease. So from that data I made some differential gene expresion analysis and I'll not explain how I proceed. But I'll explain a different approach that I use, the Transcription factor activity analysis.

### Diapo 12

The transcription factor are proteins that enhance or block the transcrition of targeted genes. That means we can infer their activity based on the expression of their own targets. To do that there is a gene set resource called Dorothea that described the interaction of TF and their targets based on litterature curated ressources, ChIP-seq analyses, TF binding motifs and previous inferences from gene expression.

### Diapo 13

By analysing the differential gene expression, I infered the transcription factor activity then compared their values between the two groups of patients. Here is a result I had from this analysis.

### Diapo 14

From that result, I wanted to rebuild a network of interaction that can highlight the pathways that are involved in the resistance. To do this I combined a functional protein protein interaction network from Reactome and the netword of Dorothea with TF-target genes and I filtered them from the TFs and genes I found changed in my previous analysis.
I got a network that is specific to the IDHmi resistance.
To go deeper in the network analysis, I wanted to highlight the nodes of my network that are the most influant.

### Diapo 15

There are a lot of metrix that describe the node connections like Degree Centrality. The degree centrality corresponds to the number of neighboor a node has. But it doesn't represent the relevance of the node. For example, if you have a network of websites that are connected between them, a website that list all the world wide websites will be highly connected with the highest score but will not be relevant.

So there are other metrix like Eigenvalue centrality. It scores the nodes depending of their neighboor's scores. So an highly connected nodes to single nodes will not have a good score.

Then the PageRank that scores depending of the out-going neighboors scores.

### Diapo 16

That was the most important in silico analysis I made for the results I will show you now.

### Diapo 17

I put the genes and tf into a plot based on the two last network metrix. All of them are significantly differentially expressed or differentially active. And the highest values correspond to the most influants. So based on this analysis, the TFs RXRA, SMAD3, CREB1, RelA and MYC are the key regulators of the resistance.
Just looking at the expression through the cohort, it's clear that there is a difference in the response to IDHmi but looking at response to chemotherapy, there are no differencies. That leads to the conclusion of RelA and Myc are two TF that are specific keys of the resistance to the IDHmi therapy.

### Diapo 18

Here is the visualisation of the network. There are also other genes and TFs that are interesting like CREB1, HIF1a, SMAD3 etc. But at the moment I focused only on RelA and Myc.

### Diapo 19

RelA is the gene that code for a protein called NF-kB p65. It is involved in a complex that can be connected to another protein p50 but also with an inhibitor kB-a. It's important to notice that the IkB-a has to be removed to let the TF be active.

-----
Here for example, the TFNa binding to its receptor leads to the degradation of the inhibitor and to the relocalisation of the TF into the nucleus. Then, it also need to be phosphorylated to be able to bind the DNA to do its role of transcription factor. Here by the protein MSK1.
In a global view, NF-kB leads to the leukocyte activation and chemotaxy, TNFInhibitorKKinase pathway negative regulation, cellular metabolism, antigenic process and inflammation.

------
Here is another way of activation of this TFs.
So to investigate its activity as we did in silico, it's very important to look at its phosphorylated form.

### Diapo 20

Then we have Myc. It's an oncogene also involved in many pathways like Transcription, Signal transduction, metabolism etc. But it also be found to be connected to enhancers boxes and linked to CEBPa, a TFs we saw in the previous study.

### Diapo 21

In order to investigate deeper on those TFs, I analysed the same way affymetrix of two cell lines.
HL60 and MOLM14. The two cell lines are IDHm and received an inhibitor. By doing the same analysis, comparing sample that received the treatment to controls I found the same TFs and genes and notably RelA for HL60 and MYC for Molm14.

### Diapo 22

Here is the result of the comparison before the treatment with IDHmi. We can see TFs and gene we already found in our cohort like STAT3, MYC.

### Diapo 23

Here, after treatment, we can see MYC again, RelA, STAT3 etc.

### Diapo 24

We then decided to characterise the two cell lines in vitro that leads to my in vitro experiments and validations. The idea was to find if one of the cell line can be a model of good responder wereas the other one would be the bad responder.

### Diapo 25

To do so I cultivated cells with this kind of design where I induced the molm14 to doxycycline 2 weeks before the analysis. Doxycycline induces IDHmutation in the molm14 cell lines. Then I treated one week to AGI our IDHm inhibitor.

### Diapo 26

Now I'll explain the different analysis I've done on them.
The first one is the scenith experiment. As you might remember, metabolism is a key process that is involved in AML. So we wanted to characterise their metabolism and to do so, we used a scenith protocol. The translation is the most expensive metabolic activity of a cells. So by blocking the synthesis of ATP and by blocking different metabolic pathways like glycolysis, Fatty acid oxydation and Oxydative phosphorylation, we can predict the metabolic dependancy at a single cell level.

### Diapo 27

I also do some Facs analysis to measure the level of markers at the surface of cells and also to measure a specific marker I'll present later called Rhod2.

### Diapo 28

So I'll present my in vitro results that may help our understanding of the differencies of the cells.

### Diapo 29

Here are the results of the scenith. At the left is the first replica that had only Molm14. We found a decrease in metabolic dependancy from 15% to 0% that is confirmed by the second replicat with higher baseline mitochondrial dependancy but with the same tendance. Instead of HL60 which does not show significant differences by before and after the treatment.

### Diapo 30

Here is Rhod2. Rhod2 is a marker of the mitochondrial calcium of the cells. As the calcium is important in the energy metabolism of the mitochondria, it's a good marker of metabolism changes. As you can see, the two cell lines present two different tendances with a decrease of calcium value in HL60 with the treatment but an increase for Molm14. Globally, HL60 show a higher value at baseline too.

### Diapo 31

Now I'll present some differentiation marker. As AML is characterised by some differenciation biais, it may be interesting to measure it. CD15 is one of the differentiation marker of granulocytes. We can see a strong difference between the two cell lines but no big changes with the treatment.

### Diapo 32

CD38 is a lymphoïd marker. The two replica doesn't show the same values so it will need to be confirmed.

### Diapo 33

Here are 3 others markers I only did once each.

### Diapo 34

Finally, I quantified some proteins by western blots. On the left is the first replicat. Some results might be interesting, notably with myc where there is a change due to the treatment but for the two cell lines.
NF-kB and more particularly its phosphorylated form has not the same pattern for the two cell line.
Bcl2 is involved in a resistance to cytarabine (an AML treatment) and linked to the mitochondrial activity.
PGC1a is also involved the mitochondrial metabolism of AML cells.
All of this results need to be done a third time and some other proteins need to be quantified too as I suggested previously.

### Diapo 35

To conclude this presentation, we have some study track on specific genes but some novel approach need to be added. We already identified potential genes and potential TFs but other data need to be done and mechanistic need to be highlighted.

### Diapo 36

In perspectives and in term of computational analysis. I also learnt to analyse DNA methylation and they will be addded and combined to the previous results. Whole Genome Bisulfite Sequencing data are in progress but can add some precision of the previous DNA methylation analysis I have done.

In a way to explain the resistance, models could be made from the key genes and TF I found.
Other type of modifications are involved in AML and splicing event is one of them. Of course, the analysis of other dataset where the IDHm inhibitor is involved may validate my previous result.

In vitro, there is a need of replica but looking at other cell lines may be interesting. And as I said previously, other genes may be very relevant like CREB1, HIF1a or STAT3.

If the in vitro and in silico results are confirmed, an in vivo experiment on mice can be done to be closer to patient environment.

### Diapo 37

Finally, to close this presentation, I'll do a recap of the achievement done during this first year.
In term of publications, I was involved in 2 papers already published where I did some DNA methylation and gene expression analysis.
And a third paper that will be resubmitted soon where I made some 3D chromatin network analysis that permitted to combined expression data to methylation and enhance the signature made.

### Diapo 38

I followed a training from the doctoral school about advanced biostatistics that will be usefull in the future.
I also participated in conferences through posters and flash talks. I managed a project called Apprentis chercheurs during almost 6 month.
And finally, here is the list of skills I acquired during this first year.

Of course I thank the Inserm and the CRCT where I do all the work. The Labex Toucan and the université Paul Sabatier. And I course I thank the two teams I am part of, the team of Vera Pancaldi, the NetB(IO)² and the time of Jean Emmanuel Sarry, the METAML team.
