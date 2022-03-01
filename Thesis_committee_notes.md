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

Hello! So I'll present my project and what I've done during this first year.

### Diapo 2

To explain my project, I will present the cancer I'm working on with its specificities and what is the problematique I'm trying to answer.
I'll show you my in silico analyses and explain how I proceed. What I have found.
Then, I'll present my in vitro analyses that are a kind of validation of the previous results.
Then I'll show you some in silico analysis method I learnt that are not incorporated yet in the results.
Finally, I'll talk about the perspectives in term of in silico and in vitro analysis and do a recap of what I've learn and what I've done as a PhD student in term of communications.

### Diapo 3

So the context of my PhD. The acute myeloid leukemia and the gene Isocitrate dehydrogenase.

### Diapo 4

The acute myeloid leukemia is a blood cancer that takes place during the haematopoiesis. The normal haematopoiesis, is the process that generates all the mature blood cells circulating in the blood from a single stem cell that resides in the bone marrow.
It's in this context that occurs different cancer depending the lineage impacted like B-ALL, T-ALL and AML.

### Diapo 5

Clinically, AML is associated with a poor outcome and declines with age. That disease lacked of novel therapies for 20 years and more particularly for patients which have physician assessment that do not favor into intensive chemotherapy. Here is a schema of factors that are involved or determine what should be done. A new combinaison of therapies have been recently accepted notably for this group of patients.

### Diapo 6

Additionally, as you can see on this graph, the proportion of relapse is close to 40% and the majority of them will not survive to this relapse. And we can also notice patients that do not have any remissions at lot.

### Diapo 7

A proportion of relapse and refractory AML are due to the mutation of IDH.
IDH1 and IDH2 are two metabolic genes that convert isocitrate into alpha-ketoglutarate. This reaction is very important as a part of the Krebs cycle and produces NADPH. NADPH is notably involved in the pentose phosphate pathway but also a molecule that protects the cell against the toxicity of reactive oxygen species. The two genes are different by their localisation. IDH1 is in the cytoplasm and IDH2 is in the mitochondria. So they are keys metabolism enzymes.

### Diapo 8

 So there is the first reaction. But the mutations that is invovled here is a gain-of-function mutation. And mutated, the protein will uses the a-KG and NADPH to synthetise D2hydroxylglutarate and NADP+. As it requires a-KG, the allele need to be heterozygote.

### Diapo 9

 This abnormal production of this oncometabolite that we will call 2HG, provocs transcriptional, epigenomic reprogramming, but also differentiation biais and blocks and altertion of the metabolism.

### Diapo 10

A previous study of our lab, investigated the effect of an inhibitor of this mutation. First, they described an High OxPHOS state of the cells impacted by the mutation. This metabolic state is like super active and make the cell resist to treatment through a CEBPa increase of activity that permits Fatty acid oxydation pathway to supply this metabolic state.
But, despite the reduction of the oncometabolite 2HG with the inhibition of IDHm inhibitor and the complete differentiation phenotype, the cells keep their High OxPHOS state. The study conclusion was to make the metabolism of IDH AML cells the central element of the resistance through some remodeling aspect.

### Diapo 11

So the question I will try to answer or I'm investigating is :
What are the key genes that are involved in the resistance or in the remodeling ability? An in silico model can predict the outcome of a patient harbouring IDH mutation?

## Diapo 12

So we have seen the context of the project and a brief overview of the IDHm actual knowledge I'll use to present what I've done. So now, I'll show you what I did.

### Diapo 13

To investigate as a computational biologist, I analysed different set of data I will present. And made some analysis I'll try to explain like differential gene expression, Transcription factor activity, network analysis and DNA methylation.

### Diapo 14

One of the dataset I use came from a public dataset from the paper "Leukemia stemness and co-occurring mutations drive resistance to IDH inhibitors in acute myeloid leukemia". It's a cohort of AML patients harbouring IDH1 or IDH2 mutation. They all received IDHm respective inhibitor. The data available are RNAseq at baseline and at relapse. Briefly, in their paper, they only made a co-mutational analysis but didn't go further in transcriptionnal analysis. So I choose to compare the ones that are good responders to that therapy. In clinical terms, that had a complete remissions to bad responders that had a progressive disease. So from that data I made some differential gene expresion analysis and I'll not explain how I proceed. But I'll explain a different approach that I used, the Transcription factor activity analysis.

### Diapo 15

The transcription factors are proteins that enhance or block the transcription of targeted genes. That means we can infer their activity based on the expression of their own targets. To do that there is a gene set resource called Dorothea that described the interaction of TF and their targets based on litterature curated ressources, ChIP-seq analyses, TF binding motifs and previous inferences from gene expression.

### Diapo 16

By analyzing the differential gene expression, I inferred the transcription factor activity then compared their values between the two groups of patients. To finally have the TF that are significantly deferentially active. Here is a result I had from this analysis. I kept the list of those TFs.

### Diapo 17

From that result, I wanted to rebuild a network of interaction that can highlight the pathways that are involved in the resistance. To do this I combined a functional protein protein interaction network from Reactome and the network of Dorothea with TF-target genes and I filtered them from the TFs and genes I found changed in my previous analysis.
I got a network of resistance.
To go deeper in the network analysis, I wanted to highlight the nodes of my network that are the most influant.

### Diapo 18

There are a lot of metrix that describe the node connections like Degree Centrality. The degree centrality corresponds to the number of neighboor a node has. In this network, the Node 3, 15 and 25 are the highest degree nodes. But it doesn't represent the relevance of the node. The node 42 is highly connected to single nodes and has a high degree but is not be relevant as it is isolated.

### Diapo 19

So there are other metrix like Eigenvalue centrality. It scores the nodes depending of their neighbor's scores. So an highly connected nodes to single nodes will not have a good score. In fact, it describes where the information go. Comparing to the previous metrix, edges nodes have a lower score but nodes at the center have a bigger one.

### Diapo 20

Finally the PageRank scores depending of the incoming neighbors scores. In other terms, where the information ends the most of the time. In our context, it would score the final target genes of all the TFs and may be not interesting, so I inverted the metrix and it's what we call a CheiRank.

### Diapo 21

That was the most important in silico analysis I made for the results I will show you now. To recap, we are looking at the resistance in IDHmutated inhibition in AML patient sample by in silico analysis

### Diapo 22

 So from the differential gene expression, differential TF activity I made a network and here is the result of my analysis.

### Diapo 23

I put the genes and tf into a plot based on the two last network metrix. All of them are significantly differentially expressed or differentially active. And the highest values correspond to the most influants ones. So based on this analysis, the TFs RXRA, SMAD3, CREB1, STAT3, RelA and MYC are the key regulators of the resistance.
Here are the expression of RelA and MYC in the cohort based on the clinical outcome, it's clear that there is a difference in the response to IDHmi but looking at response to chemotherapy from another cohort, there are no differencies. That leads to the conclusion of RelA and Myc are two TF that are specific keys of the resistance to the IDHmi therapy.

### Diapo 24

Here is the visualisation of the network. The size of a node is based on its eigenvalue centrality and the gene expression is colorcoded from blue to red. Red are more expressed in bad responders. The links between nodes are based on the two network I presented previously. There are also other genes and TFs that are interesting like CREB1, HIF1a, SMAD3 etc. But at the moment I focused only on RelA and Myc.

### Diapo 26

What is the gene RelA? It is the gene that code for a protein called NF-kB p65. It is involved in a complex that can be connected to another protein p50 but also with an inhibitor kB-a. It's important to notice that the IkB-a has to be removed to let the TF be active as it's an inhibitor.

-----
Here for example, the TFNa binding to its receptor leads to the degradation of this inhibitor and to the relocalisation of the TF into the nucleus. Then, it also need to be phosphorylated to be able to bind the DNA and do its role of transcription factor. Here by the protein MSK1.
In a global view, NF-kB leads to the leukocyte activation and chemotaxy, TNF Inhibitor K Kinase pathway negative regulation, cellular metabolism, antigenic process and inflammation.

------
Here is another way of activation of this TFs. So to investigate its activity as we did in silico, it's very important to look at its phosphorylated form.

### Diapo 27

Then we have Myc. It's an oncogene also involved in many pathways like Transcription, Signal transduction, metabolism etc. But it can also be found connected to enhancers boxes and linked to CEBPa, a TFs we saw in the previous study.

### Diapo 28

In order to investigate deeper on those TFs, I analysed the same way affymetrix data of two cell lines. HL60 and MOLM14. The two cell lines are IDHm AML cells. Each of them received either a control treatment or an IDHm inhibitor. By doing the same analysis and comparing the two cell lines with a control treatment, I got the TFs from the previous analysis like MYC and STAT3

### Diapo 29

By looking at cell line with the IDHm inhibitor treatment, I found Myc, STAT3 and RelA.

### Diapo 30

At the end of the in silico analysis, we suggested that one of the cell line can be a model of good responder wereas the other one would be the bad responder. We then decided to characterise the two cell lines in vitro. My background in experimental biology was old but I did some in vitro anyway and I'll present them. I'll show results next.

### Diapo 31

So about the in vitro methods.

### Diapo 32

First, I cultivated cells with this kind of design where I induced molm14 to doxycycline 2 weeks before the analysis. Doxycycline induces IDH mutation in the molm14 cell lines. Then I treated one week to AGI our IDHm inhibitor. One day before analyzing the samples, I did a seeding to make the cell line in the best conditions.

### Diapo 33

The first analysis I've done is the scenith experiment. As you might remember, metabolism is a key process that is involved in AML. So we wanted to characterize their metabolism and to do so, we used a scenith protocol. The translation is the most expensive metabolic activity of a cells. So by blocking different metabolic pathways like glycolysis, Fatty acid oxydation and Oxydative phosphorylation, and by measuring the translation activity we can predict the metabolic dependancy at a single cell level.

### Diapo 34

To measure it, I did some Facs analysis but to also measure the level of other markers at the surface of cells and to measure a specific marker I'll present later called Rhod2. The principe of the fluorescence-activated cell sorting is to put a fluorescent element on a specific marker and measure it with a laser and through diffraction. In a facs like we can see on the slide, there are 4 channels that means we can measure 4 different fluorescent elements. They need to be associated to different wavelength of course. The plot at the right is an overview of what we can found. From some software we can filter cells that may not be interesting. Here, the cells out of the circle in fact are not cells but debris.

### Diapo 35

I also made some western blot to quantify specific proteins by some migration methods and antibodies fixations and revelations.

### Diapo 36

So a quick recap of the in vitro analysis. The aim of the in vitro was to characterize cell lines in order to make a model of resistance based on in silico analysis.

### Diapo 37

### Diapo 38

Here are the results of the scenith. The results of the scenith that we are looking for is the mitochondrial dependency. At the left we have the percentage of ergergy that derived from the mitochondria pathway for sample. The HL60 cell line with a control treatment generates more than 45% of its energy from the mitochondria and 40% after treatment with IDHinhibitor. But for Molm14, we found a strong decrease of mitochondrial dependancy by the IDHinhibitor treatment. Molm 14 may have stronger mitochondrial remodeling than HL60 here.

### Diapo 39

Here is Rhod2. Rhod2 is a marker of the mitochondrial calcium of the cells. As the calcium is important in the energy metabolism of the mitochondria, it's a good marker of metabolism changes. As you can see, the two cell lines present two different tendances with a decrease of calcium value in HL60 with the treatment but an increase for Molm14. Globally, HL60 show a higher value at baseline too.

### Diapo 40

Now I'll present some differentiation marker. As AML is characterised by some differentiation biais, it may be interesting to measure it. CD15 is one of the differentiation marker of granulocytes. We can see a strong difference between the two cell lines but no big changes with the treatment.

### Diapo 41

CD38 is a lymphoïde marker. The two replica doesn't show the same values so it will need to be confirmed.

### Diapo 42

Here are 2 others markers I only did once each. Only baseline values are really different.

### Diapo 43

Finally, I quantified some proteins by western blots. On the left is the first replicat. Some results might be interesting, notably with myc where there is a change due to the treatment but for the two cell lines.
NF-kB and more particularly its phosphorylated form has not the same pattern for the two cell line.
Bcl2 is involved in a resistance to cytarabine (an AML treatment) and linked to the mitochondrial activity.
PGC1a is also involved the mitochondrial metabolism of AML cells.
All of this results need to be done a third time and some other proteins need to be quantified too as I suggested previously.

### Diapo 44

So we saw the line of the project we already created. Starting from In silico analysis of datasets to in vitro preliminary characterization. But I also made other in silico approaches I want to show but are not yet inserted in the followed study.

### Diapo 45

### Diapo 46

In fact, the first approach I made was about DNA methylation and 3D chromatin network analysis.

### Diapo 47

In fact, the alpha ketoglutarate is used by dioxygenases enzymes like the TETs et Jumonji demethylase to demethylate DNA and histones. The mutation consumes this aKG but is also a competitive inhibitor of the enzymes. This results to a DNA and histone hypermethylations phenotype.

I focused my analysis on DNA methylation.

### Diapo 48

I don't know how much I need to present DNA methylation but in a few words, it has an impact on gene expression so it's a interesting regulatory element that is perturbed and need to be analyzed.

### Diapo 49

The methylation occurs on dinucleotyde CpGs by the addition of a methyl group.

### Diapo 50

Determinating the CpGs methylated is possible thanks to the bisulfite conversion that converts unmethylated Cytosine into Uracile then into thymine. By hybridation then sequencing it is possible to determine the methylation of a CpGs.

### Diapo 51

In term of data, each CpGs will have a Betavalue going from 0 to 1 and the density of their values looks like a bimodal distribution with two peaks near 0 and 1. The BMIQ normalization is a type of normalization for bimodal distribution I made using an R package called ChAMP for Chip Analysis Methylation Pipeline.

### Diapo 52

They are different analysis that can be made to investigate the methylation of the DNA, one is a single position analysis to determine Differentially Methylated Positions as you can see here and a more spread analysis called Differentially methylated Regions. DMR are statistically more robust in term of relevance and it's often what we are looking at.

### Diapo 53

In a recent paper, Elisabeth Wilson and al analysed IDHm specific DMR in AML context. The majority of DMR found were localized on enhancer because the majority of the locus of the DNA are enhancer-like. What is very interesting is the enrichment of Genic enhancer associated region, the 6_EnhG ChrommHMM State and the strong transcription associated state.

The majority of DNA methylation is focalised on promoter methylation but it's clear that methylation is very important in distal elements like enhancer and is responsible of transcription alterations.

### Diapo 54

To investigate this distal regulations it's important to have in mind the 3D chromatin conformation. Because distal regulation is possible thanks to the compaction of the chromatin and the connections that can be made. Here you can see the schema of the chromatin with those connections.

### Diapo 55

To have access to this specific conformation, the Bluepint epigenome project made some Promoter Capture Hi-C that permitted to connect promoters to distal regions and my other team created a network based on that data to manipulate this knowledge.

### Diapo 56

So the idea was to find chromatin fragments that have differential methylated regions and by using their coordinates, connect them through a network to promoters. And by looking at the expression of their respective genes, link the expression to the methylation.

### Diapo 57

One of the problem I'm currently facing is the data I'm using. The problem is well explain in this paper where this plot  representing the coverage of EPIC data for distal elements. It shows that the coverage of all the DNAse proximal but more particularly distal regions by the EPIC array is very low. And for the regulatory regions covered, most are represented by just one probe on the array. So it might be not very accurate to capture the methylation variation across the extent of a regulatory region. One solution is Whole Genome Bisulfite Sequencing WGBS but it's very expensive.

### Diapo 58

But we have the data made from the previous paper of Elisabeth Wilson that are WGBS data of IDHm AML patients. There are no context of IDHm inhibitor but it can help to analyze the EPIC data in the IDHm inhibitor context. The data analysis is still in progress but is promising as they picked some TFs like Myc that are linked to methylation.

So the methylation part is a very promising project that I hope will connect the different results or somehow made us go in another direction.

### Diapo 59

Apart from my project, I also learnt to analyze RNA splicing

### Diapo 60

Quickly, alternative splicing event are focus in a study of our lab and from RNAseq data and by computational program, it's possible to capture those events. I'll not go further as the analysis are also in progress.

### Diapo 61

So we are going to the end of the presentation and I'll make a conclusion of all of that, talk about the perspectives and finally present what I actually achieved this first year.

### Diapo 62

To conclude this presentation, we have some study track on specific genes but some novel approach need to be added. We already identified potential genes and potential TFs but other data need to be done and mechanistic need to be highlighted.

### Diapo 63

In perspectives and in term of computational analysis. We saw that DNA methylation will be addded and combined to the previous results. Whole Genome Bisulfite Sequencing data are in progress but can add some precision of the previous DNA methylation analysis I have done.

In a way to explain the resistance, models could be made from the key genes and TF I found.
Other type of modifications are involved in AML and splicing event is one of them. Of course, the analysis of other dataset where the IDHm inhibitor is involved may validate my previous result.

In vitro, there is a need of replica but looking at other cell lines may be interesting. And as I said previously, other genes may be very relevant like CREB1, HIF1a or STAT3.

If the in vitro and in silico results are confirmed, an in vivo experiment on mice can be done to be closer to patient environment.

### Diapo 64

Finally, to close this presentation, I'll do a recap of the achievement done during this first year.
In term of publications, I was involved in 3 papers.

### Diapo 65

The first paper, I did some transcriptomic and methylome analysis on publicly available cohorts

### Diapo 66

For the second one, I built different signatures that have shown to be enriched in our AML IDHm context.

### Diapo 67

And a third paper that will be resubmitted soon where I made some 3D chromatin network analysis that permitted to combined expression data to methylation and enhance the signature made for deconvolution. So to give more details, we had a signatures composed of methylated cpgs and a signature of genes. Using 3D chromatin conformation, I found 48 genes that were not in the gene signature but that have cpgs from the cpgs signature in their promoter and that are connected to chromatin fragment having themselves cpgs from the cpgs signature. This enhanced the signature in term of deconvolution .

### Diapo 68

I also followed a training from the doctoral school about advanced biostatistics that will be usefull in the future.
I also participated in conferences through posters and flash talks.
I managed a project called Apprentis chercheurs during almost 6 month.
And finally, here is the list of skills I acquired during this first year.

Of course I thank the Inserm and the CRCT where I do all the work. The Labex Toucan and the université Paul Sabatier. And I course I thank the two teams I am part of, the team of Vera Pancaldi, the NetB(IO)² and the time of Jean Emmanuel Sarry, the METAML team.
