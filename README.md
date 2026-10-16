# UCSC-Cell-Browser

Name- Maria Ryzah May I. Vertudazo

## 1. Assigned Gene and Disease

- **Gene:** BRCA1
- **Associated disease:** Hereditary breast and ovarian cancer syndrome (HBOC)
- **Reference transcript:** NM_007294.4
- **Chromosome:** 17

## 2. Organ/Tissue Choice and Dataset Information

- **Dataset name:** Single-cell atlas of human leptomeningeal metastasis- Patient C with Breast Primary Tumor
- **Organ/tissue:** brain,spinal cord,tumor,leptomeningeal metastasis
- **Dataset URL:** https://cells.ucsc.edu/?ds=lepto-metastasis+patient-c&gene=BRCA1
- **Reason for selection:** This dataset was selected to investigate BRCA1 expression in a tissue relevant to hereditary breast and ovarian cancer syndrome. The interpretation will be based on the cell types and expression patterns actually observed in the dataset.

## 3. Understanding the Cell Map

- **Visualization type:** two dimensional scatter plot of single-cell data. 
- **Meaning of one dot:** representation of an individual measured cell from the single-cell dataset. 
- **Meaning of clusters:** representation of group of cells with similar molecular profiles. 
- **Three visible cell types/clusters:** CD4 T cells, CD8 T cells, NK cells

## 4. Assigned Gene Expression

- **Gene searched:** BRCA1
- **Overall expression pattern:** BRCA1 expression was low across the dataset. Most cells had values near 0.01, and only about the top 10 percent of the cells reached higher value. The dot plot showed no clear difference between cell types. 
- **Clusters with stronger expression:** No clusters had clearly stronger BRCA1 on the dot plot. On the map, the darkest cells were mainly in Monocyte 1 and 2, NK cell, and the upper part of the CD8 T cell cluster. 
- **Clusters with lower or undetected expression:** The lowest expression was in the lower part of the CD4 T cell cluster and in most macrophages. The cDCs also looked low, but they are very few cells. 

## 5. Cell Types and Clusters

- **Strongest visible expression:** Monocyte 2. Has the densest group f dark purple to black cells on the map. 
- **Another detectable cell type/cluster:** Nk cells. They formed a compact cluster of mostly dark purple cells on the map
- **Low or undetected expression:** Lower part of the CD4 T cell cluster. The cDCs also looked low, but just a few of them. 
- **Expression pattern:** BRCA1 was low overall and scattered.
- **Possible biological explanation:** BRCA1 is a DNA repair gene needed at low levels in many cell types, so a weak, widespread signal is expected. Cells that are dividing or active may express it more, which could explain the scattered higher cells. 

## 6. Expression Plot

- **Selected cluster/cells:** Monocyte 2 cluster [480 cells, 19 percent of the dataset] and colored cells by BRCA1 
- **Comparison with other cells:** Both groups had a similar distribution, mostly near 0.01. The other cells had a few cells reaching the dataset maximum of 2.18, while Monocyte 2 reached about 1.3. 
- **What the plot shows:** Both violins have wide base near the lowest value and a thin tail upward, so most cells in both groups express very little BRCA1. Monocyte 2 was not clearly higher than the other cells, and BRCA1 not strongly specific to this cluster. On the map the cluster looks dark, but that coloring ranks cells within the dataset, so it exaggerates small differences between cells whose values are all 0.01.  

## 7. Marker Genes

- **Cluster/cell type examined:** Monocyte 2 
- **Marker gene 1:** LYZ[dark purple dot]
- **Marker gene 2:** CST3[dark dot]
- **Marker gene 3:** CD14
- **Is BRCA1 a cell-type marker in this dataset?** No. BRCA1 was pale and similar in every cell type on the dot plot, and the Monocyte 2 violin was not clearly different from the other cells. In contrast with LYZ, CST3 and CD14 were clearly higher in Monocyte 2. 

## 8. Disease Gene vs. Marker Gene

- **Assigned disease gene:** BRCA1
- **Marker gene:** LYZ
- **More cell-type-restricted gene:** LYZ. It was high in Monocyte 1 and , with some signal in macrophages and cDCs, and low in T cells, NK cells, and cancer cells. 
- **More broadly expressed gene:** BRCA1 with low but detectable in all cells types, with no group clearly higher. 
- **Interpretation:** LYZ marks a specific lineage and can be used to identify them. BRCA1 does not separate any cell type from the others in the dataset. BRCA1 is broadly expressed disease gene here, not a cell-type marker. 

## 9. Connection to Genome Browser and ClinVar

- **Chromosome location:** Chromosome 17
- **Disease-associated variant:** c.68_69del (185delAG)
- **Cell types expressing BRCA1:** CD4 and CD8 T cells, NK cells, Monocyte 1 and 2, macrophages, cDCs, and the cancer clusters.
- **Biological interpretation:** BRCA1 is a DNA repair gene needed at modest levels in many cell types, so low, widespread expression  is expected.
- **Can this dataset prove causation?** No. It shows where BRCA1 is expressed in one’s patient’s cells, but it does not test the effect of the variant. 

## 10. Reflection

1.  What did the UCSC Cell Browser show that the UCSC Genome Browser could not?
Cell Browser showed expression in individual cells and cell types, such as T cells, monocytes, and cancer cells. The Genome Browser shows only where the gene sits in the genome, its structure, and its variants.
2.  Why can the same gene have different expression levels among cell types?
 Every cell has the same DNA, but different cell types turn genes on and off through regulation. A gene’s level also depends on how active, dividing, or specialized the cell is.
3.  Why should zero or very low single-cell expression be interpreted carefully?
 single-cell methods often miss lowly expressed genes (dropout), so a zero does not prove the gene is off. Small cell numbers and sample type can also distort the picture.
4.  Why combine genomic location, variants, and cell-specific expression?
location and variants show what could change in the gene, and expression shows which cells might be affected.
5.  What was the most interesting observation about BRCA1?
BRCA1 was low in nearly every cell type, unlike marker genes such as LYZ, which separated cell types clearly. It acts as a widely expressed repair gene, not a cell-type marker.

## 11. References and Links

- UCSC Cell Browser: https://cells.ucsc.edu/
- National Center for Biotechnology Information. (n.d.). NM_007294.4(BRCA1):c.5266dup (p.Gln1756fs) (VCV000017677). ClinVar. Retrieved October 7, 2026, from https://www.ncbi.nlm.nih.gov/clinvar/variation/17677/
