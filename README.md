# KEGG Reference builder
Short programm to build a KEGG reference for metagenomes from BRITE hierarchies; Intended for GhostKOALA (https://www.kegg.jp/ghostkoala/) output but works with any KO dataset.
Across metabolic pathways, a single KEGG orthologue may have more than one function - which creates issues in assigning genes a precise function if multiple entries are availabe. 
This R-programm produces a neat table from hierachical h-text files available from KEGG (https://www.kegg.jp/brite/ko00001). Non-unique KO function levels are determined by last common function, KNrs, gene names etc are unaffected. 


