# STELLS
Developer: Yufeng Wu

STELLS is a program for finding the maximum likelihood estimate of the species tree for the given gene trees, which undergo incomplete lineage sorting (as illustrated in the above figure). STELLS can also compute the gene tree probability for a given species tree. It has also been extended for the inference of population trees from haplotypes. See my papers for more details.

STELLS is developed as the software accompaniment to: Yufeng Wu, "Coalescent-based Species Tree Inference from Gene Tree Topologies Under Incomplete Lineage Sorting by Maximum Likelihood", Evolution, v. 66 (3), p. 763-775, 2012. 

The following two papers have extensions to the original STELLS approach.
Yufeng Wu, "A coalescent-based method for population tree inference with haplotypes", Bioinformatics, v31, p. 691-698, 2015. (This paper develops an extension of STELLS, called STELLSH, for the inference of population tree, which takes population haplotypes as input and infer the population split history (called population tree). This allows the inference from sequences directly, and may be a better choice when the time scale is shorter.).

Yufeng Wu, "An Algorithm for Computing the Gene Tree Probability under the Multispecies
Coalescent and its Application in the Inference of Population Tree", submitted for publication, 2015. (This is a recent paper for a faster algorithm when there are multiple gene lineages for small number of populations. It also includes a new approach for the population tree inference from pairwise population distances.)

Note: Files can be downloaded using "Save Link/Target As..." After downloading the softwares, you may need to change file access permissions (e.g. chmod u+x stells-linux).

#STELLS2
I have developed a new version of STELLS, called STELLS2. STELLS2 is a heuristic version of STELLS. STELLS2 doesn't compute the same probability as STELLS, but it is much faster than STELLS. If you have large data, you may want to consider using STELLS2. In any case, I provide STELLS code here in case you want to use the original STELLS.
