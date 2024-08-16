# Single-Cell and Spatial Omics learning notes
Single-cell and spatial omics are two increasingly popular areas, which greatly revolutionize life studies.   
I am on the way to learn them, so it is a good time for me to take down notes here.

*** 
## 0. Single-Cell   
### 0.1 Review
+ [Eleven grand challenges in single-cell data science](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-1926-6)    
Genome Biology   
Published: 07 February 2020
### 0.2 Tools
+ [sceasy](https://github.com/cellgeni/sceasy) is a package that helps easy conversion of different single-cell data formats to each other.   
+ [sfaira](https://sfaira.readthedocs.io/en/latest/) is a model and a data **repository** for single-cell data in a single python package.   
[sfaira-site](https://theislab.github.io/sfaira-site/index.html)    
[github](https://github.com/theislab/sfaira)    
### 0.3 Projects
+ [Open Problems in Single-Cell Analysis](https://openproblems.bio/), whose goal is to formalize challenges such as these and create a living community-driven state-of-the-art benchmarking platform to facilitate development of single-cell methods.  
### 0.4 Tutorials
+ [ANALYSIS OF SINGLE CELL RNA-SEQ DATA](https://broadinstitute.github.io/2019_scWorkshop/)    
+ [Analysis of single cell RNA-seq data](https://www.singlecellcourse.org/)   
+ [Basics of Single-Cell Analysis with Bioconductor](http://bioconductor.org/books/3.14/OSCA.basic/)    
+ [Advanced Single-Cell Analysis with Bioconductor](http://bioconductor.org/books/3.14/OSCA.advanced/)    
### 0.5 Worth reading    
+ [Ming Tang: scRNAseq-analysis-notes](https://github.com/crazyhottommy/scRNAseq-analysis-notes)
+ [Sean Davis: awesome-single-cell >> List of software packages (and the people developing these methods) for single-cell data analysis](https://github.com/seandavi/awesome-single-cell)

***
## 1. scRNA-seq method
### 1.1 Review   
+ [Single-cell RNA-sequencing: The future of genome biology is now](https://www.tandfonline.com/doi/full/10.1080/15476286.2016.1201618)   
RNA Biology   
Published: 21 July 2016    
+ [Tutorial: guidelines for the experimental design of single-cell RNA sequencing studies](https://www.nature.com/articles/s41596-018-0073-y)   
Nature Protocols   
Published: 16 November 2018   

***   
## 2. scRNA-seq analysis
### 2.1 Review
+ [Current best practices in single-cell RNA-seq analysis: a tutorial](https://www.embopress.org/doi/full/10.15252/msb.20188746)   
Molecular systems biology    
Published: 19 June 2019 
+ [Orchestrating single-cell analysis with Bioconductor](https://www.nature.com/articles/s41592-019-0654-x)   
Nature Methods    
Published: 02 December 2019 
+ [Tutorial: guidelines for the computational analysis of single-cell RNA sequencing data](https://www.nature.com/articles/s41596-020-00409-w)  
Nature Protocols   
Published: 07 December 2020   

### 2.2 Clustering   
+ [TooManyCells identifies and visualizes relationships of single-cell clades]()    
Nature Methods    
Published: 02 March 2020   
+ [Souporcell: robust clustering of single-cell RNA-seq data by genotype without reference genotypes](https://www.nature.com/articles/s41592-020-0820-1)     
Nature Methods    
Published: 04 May 2020     
+ [Putative cell type discovery from single-cell gene expression data](https://www.nature.com/articles/s41592-020-0825-9)    
Nature Methods    
Published: 18 May 2020   

### 2.3 Integration    
#### 2.3.1 Assessment    
+ [Benchmarking atlas-level data integration in single-cell genomics](https://www.biorxiv.org/content/10.1101/2020.05.22.111161v2)    
bioRxiv    
Posted May 27, 2020.   
+ [A multicenter study benchmarking single-cell RNA sequencing technologies using reference samples](https://www.nature.com/articles/s41587-020-00748-9)   
Nature Biotechnology    
Published: 21 December 2020   

+ [A test metric for assessing single-cell RNA-seq batch correction](https://www.nature.com/articles/s41592-018-0254-1)    
Nature Methods    
Published: 20 December 2018  
+ [A benchmark of batch-effect correction methods for single-cell RNA sequencing data](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1850-9)     
Genome Biology    
Published: 16 January 2020  
+ [Flexible comparison of batch correction methods for single-cell RNA-seq using BatchBench](https://www.biorxiv.org/content/10.1101/2020.05.22.111211v2)     
bioRxiv    
Posted May 27, 2020.  

#### 2.3.2 Method
+ [Fast, sensitive and accurate integration of single-cell data with Harmony](https://www.nature.com/articles/s41592-019-0619-0)   
Nature Methods   
Published: 18 November 2019    
+ [BERMUDA: a novel deep transfer learning method for single-cell RNA sequencing batch correction reveals hidden high-resolution cellular subtypes](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1764-6)   
Genome Biology    
Published: 12 August 2019    
+ [Batch effects in single-cell RNA-sequencing data are corrected by matching mutual nearest neighbors](https://www.nature.com/articles/nbt.4091)    
Nature Biotechnology    
Published: 02 April 2018

+ [FIRM](https://github.com/mingjingsi/FIRM) is an algorithm for accurate integration of heterogeneous scRNA-seq datasets across multiple platforms, which specifically accounts for the heterogeneity in cell type composition between SS2 and 10X datasets.   
+ [A Joint Deep Learning Model for Simultaneous Batch Effect Correction, Denoising and Clustering in Single-Cell Transcriptomics](https://www.biorxiv.org/content/10.1101/2020.09.23.310003v1)   
bioRxiv    
Posted September 25, 2020.   
In this paper, they present CarDEC, a joint deep learning model that simultaneously clusters and denoises scRNA-seq data, while correcting batch effect both in the embedding and **the gene expression space**.   
+ [Monet: An open-source Python package for analyzing and integrating scRNA-Seq data using PCA-based latent spaces](https://www.biorxiv.org/content/10.1101/2020.06.08.140673v2)   
bioRxiv   
Posted June 10, 2020.  
+ [Latent cellular analysis robustly reveals subtle diversity in large-scale single-cell RNA-seq data](https://academic.oup.com/nar/article/47/22/e143/5576119)    
Nucleic Acids Research   
Published: 30 September 2019    
+ [ClusterMap: compare multiple single cell RNA-Seq datasets across different experimental conditions](https://academic.oup.com/bioinformatics/article-abstract/35/17/3038/5289328)    
Bioinformatics   
Published: 14 January 2019    
Using marker genes and purity tree cut, ClusterMap match multiple samples reliably at cluster level and overcomes batch effects directly.    

### 2.4 Preprocessing pipeline
+ [alevin](https://salmon.readthedocs.io/en/latest/alevin.html) extends the directional method used in [UMI-tools](https://umi-tools.readthedocs.io/en/latest/Single_cell_tutorial.html) to correct UMI errors with droplet scRNA-Seq within a framework that also enables quantification using multi-mapped reads. [alevin](https://salmon.readthedocs.io/en/latest/alevin.html) is an accurate, fast and convenient end-to-end tool to go from fastq -> count matrix.   
   
   
### 2.5 RNA velocity or transcription dynamics   
+ [velocyto](http://velocyto.org/): [RNA velocity of single cells](https://www.nature.com/articles/s41586-018-0414-6)   
Nature   
Published: 08 August 2018    
+ **scVelo**: [Generalizing RNA velocity to transient cell states through dynamical modeling](https://www.nature.com/articles/s41587-020-0591-3)   
Nature Biotechnology   
Published: 03 August 2020

+ [CellRank for directed single-cell fate mapping](https://www.biorxiv.org/content/10.1101/2020.10.19.345983v2)    
bioRxiv    
Posted November 20, 2020.    
Here, we present [CellRank](https://cellrank.readthedocs.io/en/latest/) for mapping the fate of single cells in diverse scenarios, including perturbations such as regeneration or disease, **for which direction is unknown**.   

+ [VeTra: a new trajectory inference tool based on RNA velocity](https://www.biorxiv.org/content/10.1101/2020.09.01.277095v1)   
bioRxiv    
Posted September 01, 2020.    
+ [Cytopath: Simulation based inference of differentiation trajectories from RNA velocity fields](https://www.biorxiv.org/content/10.1101/2020.12.21.423801v1)    
bioRxiv    
Posted December 22, 2020.   

+ **revisit the whole process of RNA velocity analysis from the mathematical point of view**    
[On the Mathematics of RNA Velocity I: Theoretical Analysis](https://www.biorxiv.org/content/10.1101/2020.09.19.304584v1)    
bioRxiv    
Posted September 20, 2020.   
   
### 2.6 Supervised method for cell-type classification/annotation    
+ [scHPL](https://github.com/lcmmichielsen/scHPL), a hierarchical progressive learning method which allows continuous learning from single-cell data by leveraging the different resolutions of annotations across multiple datasets to learn and continuously update a classification tree. Paper is [here](https://www.nature.com/articles/s41467-021-23196-8).   
+ [ProjecTILs](https://github.com/carmonalab/ProjecTILs): Interpretation of T cell states using reference single-cell atlases.   
+ [ELeFHAnt](https://github.com/praneet1988/ELeFHAnt): Ensemble Learning for Harmonization and Annotation of Single Cells (ELeFHAnt) provides an easy to use R package for users to annotate clusters of single cells, harmonize labels across single cell datasets to generate a unified atlas and infer relationship among celltypes between two datasets.   
+ [cellassign](https://github.com/Irrationone/cellassign) automatically assigns single-cell RNA-seq data to known cell types across thousands of cells accounting for patient and batch specific effects. Information about a priori known markers cell types is provided as input to the model in the form of a (binary) marker gene by cell-type matrix. cellassign then probabilistically assigns each cell to a cell type, removing subjective biases from typical unsupervised clustering workflows.
+ [scArches](https://scarches.readthedocs.io/en/latest/index.html): a deep learning strategy for mapping query datasets on top of a reference called single-cell architectural surgery (scArches). scArches uses transfer learning and parameter optimization to enable efficient, decentralized, iterative reference building and contextualization of new datasets with existing references without sharing raw data. Paper is [here](https://www.nature.com/articles/s41587-021-01001-7).    


### 2.7 Ambient RNA Correction    
+ [CellClear: Enhancing Single-cell RNA Data Quality via Biologically-Informed Ambient RNA Correction](https://www.biorxiv.org/content/10.1101/2024.08.05.606571v1)


***
## 3. snRNA-seq (single-nucleus RNA-sequencing)
### 3.1 Compared with scRNA-seq   
+ [Systematic comparison of single-cell and single-nucleus RNA-sequencing methods](https://www.nature.com/articles/s41587-020-0465-8)    
Nature Biotechnology    
Published: 06 April 2020

***
## 4. spatial (ST, spatial transcriptomics)
### 4.1 experimental method   
+ [**Slide-seq**：A scalable technology for measuring genome-wide expression at high spatial resolution](https://science.sciencemag.org/content/363/6434/1463.full)   
Science 29 Mar 2019   
+ [Highly sensitive spatial transcriptomics at near-cellular resolution with **Slide-seqV2**](https://www.nature.com/articles/s41587-020-0739-1)   
Nature Biotechnology    
Published: 07 December 2020    
+ **ExSeq**: [**Expansion Sequencing**: Spatially Precise *In Situ* Transcriptomics in Intact Biological Systems](https://www.biorxiv.org/content/10.1101/2020.05.13.094268v1)   
bioRxiv    
Posted May 15, 2020.    
+ **seqFISH**: [Highly multiplexed spatially resolved gene expression profiling of mouse organogenesis](https://www.biorxiv.org/content/10.1101/2020.11.20.391896v1)   
bioRxiv    
Posted November 21, 2020.    
In sum, by **computationally integrating high-resolution spatially-resolved gene expression maps with single-cell genomics data**, we provide a powerful new approach for studying how and when cell fate decisions are made during early mammalian development.    
+ **DBiT-seq**: [High-Spatial-Resolution Multi-Omics Sequencing via Deterministic Barcoding in Tissue](https://www.cell.com/cell/fulltext/S0092-8674(20)31390-8)   
cell   
December 10, 2020   

### 4.2 computational method
+ [Whole brain alignment of spatial transcriptomics between humans and mice with BrainAlign](https://www.nature.com/articles/s41467-024-50608-2)    
Nature Communications    
Published: 30 July 2024          
BrainAlign could integrate cross-species spots into the embedding space and reveal the conserved brain regions supported by ST information, which facilitates the detection of homologous regions between humans and mice.


***
## 5. cell–cell interactions
### 5.1 Review
+ [Deciphering cell–cell interactions and communication from gene expression](https://www.nature.com/articles/s41576-020-00292-x)     
Nature Reviews Genetics    
Published: 09 November 2020.    
### 5.2 Database
+ [OmniPath](https://omnipathdb.org/) is a database of molecular biology prior knowledge developed in Saez Lab and Korcsmaros Lab. It combines data from more than 100 resources and contains protein-protein and gene regulatory interactions, enzyme-PTM relationships, protein complexes, protein annotations and intercellular communication.      
[paper](https://www.embopress.org/doi/full/10.15252/msb.20209923): Integrated intra‐ and intercellular signaling knowledge for multicellular omics analysis   

***
## 6. single-cell immune profiling
+ [scRepertoire](https://github.com/ncborcherding/scRepertoire): A toolkit for single-cell immune profiling. Enabling users to easily combine RNA and immune profiling, scRepertoire was built to process data derived from the 10x Genomics Chromium Immune Profiling for both T-cell receptor (TCR) and immunoglobulin (Ig) enrichment workflows and subsequently interacts with the popular Seurat R package.    

***
## 7. Dimension reduction
### 7.1 Methods   
+ t-SNE: [How to Use t-SNE Effectively](https://distill.pub/2016/misread-tsne/)   
+ UMAP: [Understanding UMAP](https://pair-code.github.io/understanding-umap/)    
+ **den-SNE and densMAP**, which are density-preserving visualization tools based on t-SNE and UMAP, respectively, and demonstrate their ability to accurately incorporate information about transcriptomic variability into the visual interpretation of single-cell RNA sequencing data. Paper is [here](https://www.nature.com/articles/s41587-020-00801-7).

***
## 8. Cross-species comparative analyses
### 8.1 Cross-species cell-type assignment   
+ CAME: [Cross-species cell-type assignment from single-cell RNA-seq data by a heterogeneous graph neural network](https://genome.cshlp.org/content/33/1/96.long)
Here, we design a heterogeneous graph neural network model, CAME, to learn aligned and interpretable cell and gene embeddings for cross-species cell-type assignment and gene module extraction from scRNA-seq data. In short, CAME can make accurate cross-species cell-type assignments even for nonmodel species and uncover shared and divergent characteristics between two species from scRNA-seq data.    


