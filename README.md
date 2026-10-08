# UCSC Cell Browser Activity

**Student name:** Nesie D. Calipas
**Assigned Gene:** DMD  
**Associated Disease:** Duchenne muscular dystrophy (DMD)

DMD is the gene that encodes dystrophin, a protein that helps maintain the stability and integrity of muscle cells. Mutations in the DMD gene are associated with Duchenne muscular dystrophy.

---

## 1. Organ/Tissue Choice and Dataset Information

**Organ/Tissue:** Skeletal muscle

**Exact Dataset Name:** Human Muscle Inclusion Body Myositis-Myonuclei

**Organism:** Human

**Dataset URL:** https://cells.ucsc.edu/?ds=muscle-ibm+myonuclei 

**Why this dataset was selected:**

The skeletal muscle dataset was selected because Duchenne muscular dystrophy primarily affects skeletal muscle. Dystrophin is important for maintaining the structure and function of muscle cells, making a skeletal muscle dataset relevant for examining DMD expression.

---

## 2. Understanding the Cell Map

**a. What type of visualization is being shown (UMAP, t-SNE, or another layout)?**

UMAP
**b. What does one dot represent?**

One dot represents one measured cell in the single-cell dataset.

**c. What do the clusters represent in this particular dataset?**

The clusters represent groups of cells or nuclei with similar gene-expression profiles. In this dataset, the clusters correspond to different cell types or cellular groups found in human skeletal muscle affected by inclusion body myositis.

**d. List at least three cell-type or cluster labels visible in the dataset.**

1. Myonuclei
2. Immune Cells
3. Skeletal Muscle Cells

---

## 4. Assigned Gene Expression

**a. Assigned gene symbol**

DMD

**b. Dataset used**

Human Muscle Inclusion Body Myositis

**c. Is expression widespread, restricted, or low/undetected?**

DMD expression is widespread, with a greater proportion of cells showing non-zero expression in the dataset.

**d. Which cluster(s) appear to contain cells with stronger expression?**

Type 2 MN appears to contain cells with stronger DMD expression, with 99% of the cells showing non-zero expression.

**e. Which cluster(s) appear to contain little or no detectable expression?**

Damaged MN shows relatively lower expression, with only 38% of cells showing non-zero expression.

---

## 5. Cell Types and Clusters

**a. Cell type/cluster with the strongest visible expression**

Type 2 MN

**b. Another cell type/cluster with detectable expression**

Type 1 MN
Reactive MN
NMJs

**c. Cell type/cluster with relatively low or undetected expression**

Damaged MN

**d. Is the expression pattern broad or cell-type restricted?**

Broad / widespread

**e. In 2-3 sentences, give a possible biological explanation for the observed pattern. Clearly state that this is an interpretation based on the selected dataset.**

DMD expression appears broad/widespread because dystrophin is important for maintaining the structural stability of muscle fibers and supporting muscle contraction. The stronger expression in Type 2 MN and detectable expression in Type 1 MN, Reactive MN, and NMJs may reflect the need for dystrophin-related structural support in different muscle cell states and specialized muscle regions, while the lower expression in Damaged MN may be associated with changes in cellular condition caused by muscle damage. This interpretation is based on the selected Human Muscle Inclusion Body Myositis dataset.

---

## 6. Expression Plot

**a. Which cells/cluster did you select?**

 Type 2 MN 

**b. Does your selected group show higher, lower, or similar expression compared with the comparison cells?**

The Type 2 MN group shows higher DMD expression compared with the comparison cells

**c. What does the expression plot add that was not obvious from the UMAP/t-SNE map?**

The expression plot provides a clearer view of the distribution of DMD expression within and among the different cell types. It helps show that DMD is detected in a high proportion of Type 2 MN cells and allows a more direct comparison of expression between cell groups.
### Screenshot 4 - Expression Comparison

---

## 7. Marker Genes

**a. Cluster/cell type examined**

Skeletal muscle → Muscle cells (2/3 in dataset)

**b. Marker gene 1**

MYH11

**c. Marker gene 2**

PLN

**d. Marker gene 3**

none

**e. Does your assigned gene behave like a cell-type marker in this dataset? Explain briefly.**

No. DMD does not behave like a cell-type marker in this dataset because its expression is broad/widespread across several muscle-related cell types, including Type 2 MN, Type 1 MN, Reactive MN, and NMJs, rather than being restricted to one specific cell type. DMD is primarily a disease-associated gene with an important role in muscle structure and function, rather than a gene that uniquely identifies a particular cell type.

---

## 8. Disease Gene vs. Marker Gene

**a. Assigned disease gene:**

DMD

**b. Marker gene:**

MYH11

**c. Which gene shows a more cell-type-restricted expression pattern?**

MYH11 shows the more cell-type-restricted expression pattern.

**d. Which gene appears more broadly expressed?**

DMD appears more broadly expressed across the different muscle-related cell types

**e. What does this comparison teach you about the difference between a disease-associated gene and a cell-type marker gene?**

A disease-associated gene such as DMD can be expressed across several cell types because its function may be important in multiple cellular contexts. In contrast, a cell-type marker such as MYH11 has a more restricted expression pattern and can help identify or distinguish a particular cell type.

---

## 9. Connection to Genome Browser and ClinVar

**Chromosome location -> Gene structure -> Disease-associated variant -> Gene expression -> Cell type/tissue**

### 1. On which chromosome is your assigned gene located? Use your previous UCSC Genome Browser activity.

The DMD gene is located on the X chromosome.

### 2. What disease-associated variant did you examine previously?

rs2040709857

### 3. In the current Cell Browser dataset, which cell type(s) express the gene?

DMD is expressed in several muscle-related cell types, including Type 2 MN, Type 1 MN, Reactive MN, and NMJs. Damaged MN also shows detectable expression, but at a relatively lower level

### 4. Does the observed cell expression make biological sense based on what you already know about the gene's function or associated disease? Explain in 3-5 sentences.

Yes, the observed DMD expression makes biological sense because dystrophin is an important structural protein in muscle cells. Its expression across Type 2 MN, Type 1 MN, Reactive MN, and NMJs is consistent with the role of dystrophin in maintaining muscle fiber stability and supporting muscle function. The lower expression in Damaged MN may reflect changes in gene expression associated with muscle damage or altered cellular state. These observations are consistent with the involvement of DMD in Duchenne muscular dystrophy, although this dataset alone cannot establish disease causation.

### 5. Can this single Cell Browser dataset prove that the gene causes the disease? Explain why or why not.

No. A single Cell Browser dataset can show where the DMD gene is expressed and which cell types contain detectable expression, but it cannot prove that the gene causes the disease. Gene expression alone does not establish causation because disease development can involve genetic variants, protein function, cellular processes, and other biological factors.

---

## 10. Reflection

### 1. What did the UCSC Cell Browser show you that the UCSC Genome Browser could not?

The UCSC Cell Browser showed where the DMD gene is expressed at the single-cell level and allowed the expression pattern to be compared among different cell types or clusters. The UCSC Genome Browser mainly showed the genomic location, gene structure, and genomic annotations rather than cell-specific expression patterns.

### 2. Why can the same gene have different expression levels among different cell types?

The same gene can have different expression levels because different cell types have different functions and therefore require different sets of genes to be active. Gene regulation can cause a gene to be highly expressed in one cell type but have lower or undetectable expression in another.

### 3. Why should you be careful when interpreting a gene that shows zero or very low expression in single-cell data?

Zero or very low expression in single-cell data does not always mean that the gene is completely inactive. Single-cell measurements can contain zero or undetected values because of biological variation, sampling, experimental methods, and limitations in detecting transcripts.

### 4. Why is it useful to combine information about genomic location, genetic variants, and cell-specific gene expression?

Combining these types of information provides a more complete understanding of a disease-associated gene. Genomic location shows where the gene and variants are located, genetic variants provide information about possible disease-associated changes, and cell-specific expression shows which cells may be affected or involved.

### 5. What was the most interesting observation you made about your assigned gene?

 DMD was broadly expressed across different muscle cell types, rather than being restricted to a single cell type.
---

## 11. References and Links

### UCSC Cell Browser

**Dataset:** https://cells.ucsc.edu/?ds=muscle-ibm+myonuclei&gene=DMD 

**UCSC Cell Browser:** https://cells.ucsc.edu/

### UCSC Genome Browser

https://genome.ucsc.edu/

### NCBI ClinVar

https://www.ncbi.nlm.nih.gov/clinvar/

### Previous Selected Variant

**Variant:** rs2040709857

### Lab Activity

**UCSC Cell Browser Disease Gene Lab Activity**
