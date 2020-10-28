# Multi-Omics-TWAS
Integrating genetic regulation of multi-omics levels facilitates elucidating schizophrenia pathogenesis

## Workflow
<img src=".img/workflow.png" width="750" />

## Main results

### Genetic regulation are mostly shared from mRNA to protein level
<img src=".img/cor.qtleffs.png" width="750" />
> Correlation of QTL (P < 0.05) effect sizes at different omics levels

Cutoff | Proportion of eQTLs preserved in rQTLs | Proportion of rQTLs preserved in sQTLs | Proportion of sQTLs preserved in pQTLs | Proportion of rQTLs preserved in pQTLs | Proportion of eQTLs preserved in pQTLs
--- | --- | --- | --- | --- | ---
P < 1e-2 | 0.422 | 0.189 | 0.185 | 0.382 | 0.262
P < 1e-4 | 0.611 | 0.398 | 0.189 | 0.444 | 0.364
P < 1e-6 | 0.601 | 0.457 | 0.445 | 0.822 | 0.397
P < 1e-8 | 0.701 | 0.480 | 0.306 | 0.897 | 0.485
> Pi1 at different omics levels

### Genetic regulation signals at different omics levels implicate schizophrenia pathogenesis
- [x] LDSC (QTL loci at different omics levels contribute to schizophrenia heritability)
  - [ ] figure 3-21
- [x] MESC (integrating multi-omics data mediated the most heritability for schizophrenia)
  - [ ] table 3-24

### Running PrediXcan of different omics levels identify schizophrenia risk genes
- [x] Correlation of PrediXcan r2s at different omics levels (Multi-SNP QTL)
- [x] Compare r2 in PrediXcan original and conditional models
- [ ] For TWAS risk genes, how many were in the conditional models?
  - [ ] figure 3-24

### Integrating genetic regulation of multi-omics levels identifies schizophrenia risk genes
- [ ] meta analysis of TWAS at differemt omics levels
- [ ] colocalization of TWAS signals at different omics levels
- [ ] Joint-omics TWAS using MR-JTI

### Functional support of the schizophrenia risk genes
- [ ] HiC, enhancer, etc.
- [ ] drug target, known risk genes, etc.
