# From Genome to Cell: Exploring Disease Gene Using the UCSC Cell Browser 

## 1. Assigned Gene and Disease

- **Gene:** KCNQ1
- **Disease:** Long QT Syndrome Type 1 (LQT1)

This activity uses the UCSC Cell Browser to investigate where the KCNQ1 gene is expressed at the single-cell level and to examine the cell types and clusters associated with its expression.

## 2. Organ/Tissue Choice and Dataset Information

### Selected Dataset
**Dataset:** Heart Cell Atlas – Global  
**Organ/Tissue:** Adult human heart  
**Dataset ID:** `heart-cell-atlas`

### Why This Tissue Was Selected
The heart was selected because KCNQ1 is associated with Long QT Syndrome Type 1, a cardiac condition involving the electrical activity of the heart. The Heart Cell Atlas contains different cell populations from the adult human heart, allowing KCNQ1 expression to be examined at the single-cell level.

### Dataset Information
The Heart Cell Atlas contains multiple datasets, including atrial cardiomyocytes, ventricular cardiomyocytes, vascular cells, fibroblasts, immune cells, neuronal cells, adipocytes, and skeletal muscle cells. The selected dataset was the Global dataset.

**Dataset URL:** [https://cells.ucsc.edu/](https://heart-cell-atlas.cells.ucsc.edu)

**Publication:** Litvinuková et al. 2020, *Nature*  
**Cell Browser Dataset ID:** `heart-cell-atlas`

## 3. Understanding the Cell Map

The selected Cell Browser dataset displays a cell map containing different clusters of cells. The visualization is a UMAP, where each dot represents an individual measured cell. Cells that are positioned close together generally have more similar molecular profiles, while groups of nearby cells form clusters.

In this dataset, the clusters correspond to different annotated cell types. Examples include Ventricular_Cardiomyocyte, Atrial_Cardiomyocyte, Endothelial, Fibroblast, Pericytes, Smooth_muscle_cells, Myeloid, and Lymphoid.

### Visualization Observations
- **Visualization type:** UMAP
- **One dot represents:** One measured cell
- **Clusters represent:** Groups of cells with similar molecular profiles and assigned cell-type annotations
- **Examples of cell types/clusters:** Ventricular_Cardiomyocyte, Atrial_Cardiomyocyte, Endothelial, Fibroblast

## 4. Assigned Gene Expression

The assigned gene KCNQ1 was searched in the Gene tab of the UCSC Cell Browser. The cell map was then colored according to KCNQ1 expression.

The KCNQ1 expression pattern was not equally strong across all cell types. The strongest visible expression was observed in the Atrial_Cardiomyocyte and Ventricular_Cardiomyocyte populations, where warmer-colored dots were more noticeable. The Endothelial cluster was mostly pale/blue, indicating lower visible expression compared with the cardiomyocyte clusters.

The expression legend showed that most cells had a value of 0, while smaller percentages of cells had higher KCNQ1 expression values.

### KCNQ1 Expression Summary
- **Gene:** KCNQ1
- **Expression pattern:** More noticeable in cardiomyocyte populations
- **Stronger expression:** Atrial_Cardiomyocyte and Ventricular_Cardiomyocyte
- **Lower expression:** Endothelial and several other non-cardiomyocyte populations
- **Overall pattern:** KCNQ1 expression was detectable across multiple cell populations but was more noticeable in cardiomyocytes

## 5. Cell Types and Clusters

The KCNQ1 expression map was compared with the cell-type labels in the Heart Cell Atlas – Global dataset.

The Atrial_Cardiomyocyte cluster showed a relatively high amount of warmer-colored KCNQ1-expressing dots. The Ventricular_Cardiomyocyte cluster also showed noticeable KCNQ1 expression, with warmer-colored dots particularly visible in the lower portion of the cluster. In comparison, the Endothelial cluster was mostly pale/blue, with only a smaller amount of warmer-colored dots.

### Observed Cell Types
- **Ventricular_Cardiomyocyte:** Stronger KCNQ1 expression was visible.
- **Atrial_Cardiomyocyte:** Stronger KCNQ1 expression was also visible.
- **Endothelial:** Mostly pale/blue KCNQ1 expression, indicating lower visible expression compared with the cardiomyocyte populations.

### Interpretation
The expression pattern in this dataset suggests that KCNQ1 is more strongly represented in cardiomyocyte populations than in some other heart cell types. This observation is consistent with the relevance of KCNQ1 to cardiac function, although expression in a particular cell type alone does not establish disease causation.

## 6. Expression Plot

A dot plot was used to compare KCNQ1 expression among the annotated cell types.

The dot plot provides two types of information. Color represents average expression, while dot size represents the percentage of cells with detectable (non-zero) expression.

The Ventricular_Cardiomyocyte population showed a relatively large and darker KCNQ1 dot. Atrial_Cardiomyocyte also showed detectable KCNQ1 expression. Several other cell types had smaller and/or lighter dots.

This plot adds information beyond the UMAP because it allows the expression level and the proportion of expressing cells to be compared across cell types.

## 7. Marker Genes

The Ventricular_Cardiomyocyte cluster was selected to examine its marker genes.

**Table 1.** _Cluster marker with top marker genes._
| Marker Gene | Z-score |
|---|---:|
| CTNNA3 | 4.15324E+02 |
| SLC8A1 | 4.11613E+02 |
| MYBPC3 | 3.99095E+02 |

These genes were identified by the Cell Browser as markers associated with the selected Ventricular_Cardiomyocyte cluster.

KCNQ1 was not one of the three top marker genes shown in this table. Therefore, in this dataset, KCNQ1 does not appear to be among the strongest cell-type marker genes for the Ventricular_Cardiomyocyte cluster based on this marker table.

## 8. Disease Gene vs. Marker Gene

For comparison, MYBPC3 was selected as a marker gene from the Ventricular_Cardiomyocyte cluster.

**Table 2.** _Comparison between the features of the disease gene and the marker gene._
| Feature | KCNQ1 | MYBPC3 |
|---|---|---|
| Role in this activity | Assigned disease-associated gene | Marker gene for Ventricular_Cardiomyocyte |
| Stronger expression observed in | Cardiomyocyte populations | Cardiomyocyte populations, especially ventricular cardiomyocytes |
| Expression pattern | Detectable across multiple cell populations | More concentrated in cardiomyocyte populations |
| Relationship to cell-type identity | Not one of the three top markers examined | Identified as a marker of the selected cluster |

Both KCNQ1 and MYBPC3 showed noticeable expression in cardiomyocyte populations. In the selected dataset, MYBPC3 appeared more restricted to the cardiomyocyte populations, while KCNQ1 showed detectable expression across a broader range of cell types. This comparison shows that a disease-associated gene and a cell-type marker can have overlapping expression patterns while still serving different purposes in interpreting the dataset.

## 9. Connection to Genome Browser and ClinVar

KCNQ1 is located on chromosome 11, and the previous UCSC Genome Browser activity showed its detailed exon-intron structure. The ClinVar variant NM_000218.3:c.834C>A (p.Tyr278Ter) was classified as pathogenic and has a nonsense molecular consequence. In the Heart Cell Atlas – Global dataset, KCNQ1 expression was particularly noticeable in atrial and ventricular cardiomyocytes, which is relevant because Long QT Syndrome Type 1 (LQT1) involves the cardiac electrical system. However, the Cell Browser dataset alone cannot prove that KCNQ1 causes Long QT Syndrome because gene expression by itself does not establish disease causation.

## 10. Reflection

1. What did UCSC Cell Browser show that UCSC Genome Browser could not?

UCSC Cell Browser showed where KCNQ1 is expressed across different cell types at the single-cell level. It allowed me to compare expression patterns among cell populations, while UCSC Genome Browser focused more on the gene's genomic location, structure, annotations, and variants.

2. Why can the same gene have different expression among different cell types?

Different cell types have different functions and therefore require different sets and levels of genes to be active. In the Heart Cell Atlas dataset, KCNQ1 showed stronger expression in cardiomyocyte populations than in several other cell types.

3. Why should we be careful when interpreting zero or very low expression in single-cell data?

Zero or very low expression does not necessarily mean that a gene is completely absent from a cell. Single-cell data can contain undetected or low-expression values because of the methods used to measure and process individual cells.

4. Why is it useful to combine genomic location, genetic variants, and cell-specific expression?

Combining these types of information provides a broader understanding of a disease-associated gene. Genomic location shows where the gene is found, genetic variants provide information about possible disease-associated changes, and cell-specific expression shows which cell types may be relevant to the gene's activity.

5. What was the most interesting observation?

The most interesting observation was that KCNQ1 showed stronger expression in atrial and ventricular cardiomyocytes in the Heart Cell Atlas dataset. Comparing KCNQ1 with the ventricular cardiomyocyte marker MYBPC3 also showed that a disease-associated gene can be expressed in the same cell population as a cell-type marker while having a different expression pattern.

## 11. References and Links

- UCSC Cell Browser: https://cells.ucsc.edu/
- Heart Cell Atlas – Cells of the adult human heart: [https://cells.ucsc.edu/](https://heart-cell-atlas.cells.ucsc.edu)
- Litvinuková et al. (2020). Cells of the adult human heart. Nature.
- PubMed: https://pubmed.ncbi.nlm.nih.gov/32971526/
- Previous UCSC Genome Browser activity: https://genome.ucsc.edu/
- NCBI ClinVar: https://www.ncbi.nlm.nih.gov/clinvar/
