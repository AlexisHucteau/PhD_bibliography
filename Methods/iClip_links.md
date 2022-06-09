# iClip overlap with splicing method

Pour commencer, vous partez d'une liste d'annotations iCLIP xlink, de votre annotation ((de Ensembl - bioMart ou UCSC) dans laquelle vous incluez des informations sur les gènes et les exons), et enfin d'une liste d'événements d'épissage alternatif indiquant l'emplacement génomique où il a lieu (de rMATS vous l'avez).

À partir de là, vous pouvez procéder de différentes manières : Normalement, je génère d'abord une liste d'introns en utilisant l'annotation génomique de gènes entiers et en soustrayant les exons. Ceci est ensuite pratique pour trouver les introns adjacents, les limites d'exon, d'intron/exon, etc. (voir la vignette (https://www.bioconductor.org/packages/devel/bioc/vignettes/branchpointer/inst/doc/branchpointer.pdf).

Ensuite, vous commencez à utiliser mergeByOverlaps pour trier votre liste de données. Par exemple, la première liaison xlink dans les exons ou les introns. Comme vous fusionnez la plage d'annotation du site xlink (1 base) et la plage d'annotation de l'exon/intron, vous aurez alors toutes les informations pour demander plus tard si ce sont des exons/introns affectés par AS en appelant à nouveau findOverlaps.  

Pour voir si ces sites xlink se trouvent dans les introns flanquants d'un exon alternatif, il suffit d'étendre la plage de l'exon AS pour générer une plage fictive (2 à 3 bases, si cela suffit, à l'extrémité 5', à l'extrémité 3' ou aux deux, conservez cette nouvelle plage dans une colonne différente de votre cadre de données car il s'agit d'une plage fictive). Cela sera suffisant pour appeler à nouveau findOverlaps entre l'intervalle fictif de l'exon AS et votre liste d'introns avec xlinks. (J'ai trouvé cette méthode plutôt simple mais très efficace).

Ensuite, vous pouvez voir où se trouvent ces xlinks dans les introns concernés (sites d'épissage 5', 3', points de branchement,...) en générant des cartes ARN. Ceci est déjà généré pour tous les xlinks détectés dans iCLIP et pour PTBP1 la liaison se produit principalement dans la piste polypyrimidine près de la limite intron-exon. Ainsi, il n'est pas très utile de le répéter.
