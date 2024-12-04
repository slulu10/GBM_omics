# Analysis Code for "Neoadjuvant PD-1 blockade induces T cell and cDC1 activation but fails to overcome the immunosuppressive tumor associated macrophages in recurrent glioblastoma" (Lee et al., Nature Communications, 2021)

# scRNAseq Analysis Steps and Codes
01-ProcessAndAnnotateAllCells.rmd

02-ProcessLymphoid.rmd

03-ProcessMyeloid.rmd

04-ProcessDC.rmd

05-ProcessMonocyte.rmd

06-Monocle2.CD8T.rmd

07-Monocle2.CD4T.rmd

08-Monocle2.DC.rmd

09-ProcessAndAnnotatePBMC.rmd

10-ProcessPBMC-Lymphoid.rmd


# Notes
Please run the code in the sequence indicated by the numbers.

The raw scRNAseq data has been deposited to Gene Expression Omnibus (GEO) under accession number GSE154795.

The scRNAseq mapped files can be generated using Cell Ranger version 3.0.0 or higher (10X Genomics) and aligned to the Genome Reference Consortium Human Build 38 (GRCh38).

You can also replicate the analysis using the combined RDS file (GSE154795_GBM.AllCell.Integrated.Scaled.ClusterRes.0.1.rds.gz), which is also deposited at GEO under accession number GSE154795.

Requirements: R (tested with version 3.1.5).
