---
title: ChIP-Seq1 - Motif Prediction
sidebar: mydoc_sidebar
permalink: mydoc_project_chipseq1.html 
---

## ChIP-Seq Workflow  

1. Read quality assessment, filtering and trimming 
2. Align reads to reference genome 
3. Compute read coverage across genome
4. Peak calling with different methods and consensus peak identification 
5. Annotate peaks 
6. Differential binding analysis 
7. Gene set enrichment analysis 
8. Motif prediction to identify putative TF binding sites

## Challenge Project: Comparison of motif enrichment and finding methods

+ Run workflow from start to finish (steps 1-8) on ChIP-Seq data set from Kaufman et al. (2010)
+ Challenge project tasks
    + Prioritize/rank peaks by FDR from differential binding analysis
    + Parse peak sequences from genome
    + Determine which _A. thaliana_ motifs in the Jaspar database ([motifDB](http://bioconductor.org/packages/release/bioc/html/MotifDb.html)) show the highest enrichment in the peak sequences. The motif enrichment tests can be performed with the [PWMEnrich](http://bioconductor.org/packages/release/bioc/html/PWMEnrich.html) package. Basic starter code for accomplishing these tasks is provided [here](https://gist.github.com/tgirke/df6fe20c2e42e71a7ade04941d4a05e9).
    + Optional: use different statistical methods to test for motif enrichment.
 

## References

+ Alipanahi B, Delong A, Weirauch MT, Frey BJ (2015) Predicting the sequence specificities of DNA- and RNA-binding proteins by deep learning. Nat Biotechnol 33: 831–838. [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/26213851)
+ Frith, Martin C., Yutao Fu, Liqun Yu, Jiang‐fan Chen, Ulla Hansen, and Zhiping Weng. 2004. “Detection of Functional DNA Motifs via Statistical Over‐representation.” Nucleic Acids Research 32 (4): 1372–81. [PubMed](http://www.ncbi.nlm.nih.gov/pubmed/14988425)
+ Kaufmann, K, F Wellmer, J M Muiño, T Ferrier, S E Wuest, V Kumar, A Serrano-Mislata, et al. 2010. "Orchestration of Floral Initiation by APETALA1." Science 328 (5974): 85–89. [PubMed](http://www.ncbi.nlm.nih.gov/pubmed/20360106)
+ Machanick P, Bailey TL (2011) MEME-ChIP: motif analysis of large DNA datasets. Bioinformatics 27: 1696–1697. [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/21486936)
+ McLeay, Robert C, and Timothy L Bailey. 2010. “Motif Enrichment Analysis: A Unified Framework and an Evaluation on ChIP Data.” BMC Bioinformatics 11: 165. [PubMed](http://www.ncbi.nlm.nih.gov/pubmed/20356413)
+ Tompa, M, N Li, T L Bailey, G M Church, B De Moor, E Eskin, A V Favorov, et al. 2005. “Assessing Computational Tools for the Discovery of Transcription Factor Binding Sites.” Nature Biotechnology 23 (1): 137–44. [PubMed](http://www.ncbi.nlm.nih.gov/pubmed/15637633)


