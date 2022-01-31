# Protocole Western-blot (LDS/BCA)

## Liste des produits

* LDS Sample Buffer 1X
* kit BSA
* eau milliQ
* Réactifs A et B
* MES ou MOPS
* Antioxydant?
* TG 10X
* ethanol absolu
* Rouge ponceau
* TBST
* BSA
* Lait

## Etape 1 : Préparation des échantillons

* Cellules dans falcons 15mL
* Centri 4°C @ 1200RPM pendant 5minutes
* Aspi surnageant
* Laver dans 1mL PBS froid
* Transférer dans eppendorff 1,5mL
* Centri 4°C @ 1200RPM pendant 5minutes
* Aspirer surnageant --> -2O°C  

---------------------
---------------------

[1]  
* Ajouter tampon de lyse : LDS Sample Buffer 1x (sans réducteur). 30µL-40µL de tampon pour 1mL de cellules dans les conditions initiales.

## Etape 2 : Sonication des échantillons

* Faire 3-4 pulses de 5-10s, puissance 50-60 (selon viscosité)
Mettre 15sec dans la glace entre chaque pulse. Nettoyer la sonde à l'éthanol entre chaque échantillon.

## Etape 3 : Dosage des échantillons par la méthode du BCA

### 1- Préparation de la gamme (BSA)

[2]  
A partir de la solution de 2mg/ml du kit, faire la série de dilution au 1/2 suivante :

| µg/µl | 2000 | 1000 | 500 | 250 | 125 | 75 |
|---|--- |---|---|---|---|---|
|H2O(µL)| 0 |100|100|100|100|100|
|Protéine (conc.précédente)| 200 (stock) | 100 (2000) | 100 (1000) | 100 (500) | 100 (250) | 100 (125) |

* Dans une plaque 96 puits fond plat, déposer en duplicat ou triplicat:
  * Gamme :
    * 10µL de la concentration souhaitée
  * Échantillons :
    * 2µL d'échantillon protéique
    * 8µL d'eau milliQ
    * 196µL de réactif A + 4µL de réactif B  

* **IMPORTANT : Ne pas oublier des puits "blancs" avec :**
  * 2µL de LDS Sample Buffer 1X
  * 8µL d'eau milliQ
  * 194µL de réactif A ° 4µL de réactif B  

* Incuber à 37°C pendant 30 minutes puis mesurer de la D0 à 570nM.

## Etape 4 : Dépôt des échantillons

[3]  
* Préparation des échantillons, par puits :
  * 15µL d'échantillon protéique
  * 1,6µL de Sample Reducing Agent 10X
* Faire bouillir les échantillons à 95°C, puis centrifuger
* Préparation des tampons de migration :
  * MES : Séparation des petites protéines (taille inf à 50kDa)
  * MOPS : séparation des grosses protéines (taille supp à 50kDa)
* Préparer 400mL de tampon de migration par cuve soit : 20mL de tampon MES ou MOPS 20X puis qsp? (quantité suffisante pour?) 400mL d'eau milliQ.
* Déposer 2,5µL de marqueur de poids moléculaire et 15µL d'échantillon. (Perte d'environ 1-1.5µL après avoir bouilli les échantillons)  
Note : S'il reste un dernier puits vide, on peut rajouter 1-2µL d'un échantillon quelconque : cela permet une meilleure migration du gel.
* Rajouter au milieu de la cuve, entre les deux gels, 500µL d'antioxydant.

## Etape 5 : Migration

* Mettre en voltage constant, 160V, 60-80minutes selon les protéines.

## Etape 6 : Transfert

* Tampon de transfert 1L par cuve (2 gels) :
  * 100mL de TG 10X
  * 200mL d'éthanol absolu
  * QSP 1L eau milliQ
* Montage transfert (dans l'ordre) :
  * Mettre vers soi le "côté noir" de la cassette de transfert, puis ajouter côté noir dans l'ordre:
    * Eponge de transfert (noire)
    * 2 papier whatman (taille 9cm*7cm)
    * Gel
    * Membrane de nitrocellulose (taille 8cm * 6cm)
    * 2 papiers whatman (taille 9cm * 7cm)
    * Eponge de transfert (noire)
    * Refermer la cassette
* **Bien enlever les bulles lors du montage !**
*(Ne pas oublier d'ajouter un pain de glace dans la cuve)*
**Note : Attention au sens et respecter le code couleur ! Les protéines migrent du pôle - (noir) vers le pôle + (rouge) !**
* Transfert : 60 minutes (protéines taille inf à 100kDa) ou 70 minutes (protéines sup à 100kDa), 100V, voltage constant

## Etape 7 : Saturation de la membrane

* Avant cette étape, on peut vérifier le bon transfert des protéines en faisant une coloration au rouge ponceau.
* Après le transfert, faire 2 lavages rapides avec du TBST.
* Saturation : 1h à RT? avec agitation, dans du TBST (TBS 0.1% Tween-20) 5% BSA (ou 5% Lait), 5mL par boîte (on peut mettre 2-3 membrane par boite).  

*Note : La majorité des anticorps peuvent être utilisés en lait ou BSA avec des résultats équivalents. Pour les anticorps totaux, le lait permet souvent de réduire le signal non spécifique. Pour les anticorps anti-phospho, toujours utiliser de la BSA (le lait contient des phosphatases)*

## Etape 8 : Incubation avec l'anticorps primaire

* Incuber sur la nuit, à 4°C avec agitation, dans 5mL de TBST 5% BSA (ou lait) par boite. Par défaut, mettre l'anticorps primaire au 1/1000ème (ajuster par la suite selon le résultat).

--------------------------------------
--------------------------------------

* Faire 3 lavages de 5 minutes avec du TBST.

## Etape 9 : Incubation avec l'anticorps secondaire

* Incuber 45 minutes, à RT avec agitation, dans 5mL de TBST 5% BSA (ou lait) par boite. Par défaut, mettre l'anticorps secondaire au 1/5000ème.
* Faire 3 lavages de 5 minutes avec du TBST.

## Etape 10 : Incubation avec le révélateur

* Préparer le révélateur ECL (West-Pico) : 2mL par gel (ou membrane). Pour cela mélanger 1mL de buffer A avec 1mL de buffer B. Attention : bien changer de cône de pipette en prélevant pour ne pas mélanger les buffers entre eux !
* Recouvrir les membranes à révéler 5 minutes avec l'ECL.
* A la fin des 5 minutes, éponger rapidement la membrane avec du papier absorbant, puis la glisser entre deux feuilles plastiques transparentes.

## Etape 11 : Révélation avec l'imageur PXi

* Révéler en mode "série", choisir 16 images espacées de 15s permet de révéler correctement la majorité des WB.
* Toujours vérifier que "add content to previous image" est bien coché.
* Choisir de révéler en binning 2*2 : ceci permet de diminuer d'un facteur 4 la taille des images avec une perte de qualité invisible à l’œil, et qui est celle demandée par les journaux scientifiques. De plus, cela permet d'avoir une intensité de signal 4X supérieure par rapport à l'option "no binning" et donc de révéler plus facilement les signaux faibles.


# Questions

[1]
LDS Sample Buffer ?

[2]
Kit BSA ?
milliQ ?
Réactifs A et B ?

[3]
Sample Reducing Agent 10X
