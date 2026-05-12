# HCCpred: Diagnostic Biomarker Panel for Hepatocellular Carcinoma

Welcome to the official documentation for **HCCpred**, a computational platform developed to identify and validate diagnostic biomarkers for Hepatocellular Carcinoma (HCC). By leveraging large-scale transcriptomics data, HCCpred provides a platform-independent diagnostic panel that can accurately distinguish HCC samples from normal liver tissues.

**Web Server:** [http://webs.iiitd.edu.in/raghava/hccpred/](http://webs.iiitd.edu.in/raghava/hccpred/)

---

## Citation

Kaur, H., Dhall, A., Kumar, R., & Raghava, G. P. S. (2019). 
**Identification of Platform-Independent Diagnostic Biomarker Panel for Hepatocellular Carcinoma using Large-scale Transcriptomics Data.** *bioRxiv*. 
[https://doi.org/10.1101/758250](https://doi.org/10.1101/758250)

---

## About the Platform

Hepatocellular Carcinoma is one of the most common and lethal forms of liver cancer. Early diagnosis is critical for improving patient survival rates. HCCpred was developed by analyzing massive gene expression datasets (including TCGA and various GEO series) to identify a robust 3-gene biomarker panel consisting of **FCN3**, **CLEC1B**, and **PRC1**.

### Dataset Composition
* **Discovery Dataset**: Comprised of 371 HCC and 50 normal samples from The Cancer Genome Atlas (TCGA).
* **Validation Datasets**: Evaluated across multiple GEO datasets (e.g., GSE14520, GSE25097) to ensure platform independence.
* **Large-scale Meta-analysis**: Analysis of over 1,500 samples to confirm the consistency of the biomarker panel.

---

## Key Features

### Diagnostic Modules
* **3-Gene Panel**: Provides a highly accurate diagnostic score based on the expression levels of FCN3, CLEC1B, and PRC1.
* **Platform Independence**: Validated across different transcriptomics technologies, including RNA-Seq and various microarray platforms.
* **High Sensitivity and Specificity**: Achieved an Area Under the Curve (AUC) of over 0.98 in most validation cohorts.

### Analysis & Visualization
* **Single Sample Prediction**: Users can upload expression data for a single sample to predict its status (Tumor vs. Normal).
* **Expression Profiling**: Visualizes the differential expression of the biomarker panel across different stages of HCC.
* **Correlation Analysis**: Explores the relationship between the biomarker panel and clinical parameters like tumor stage and overall survival.

---

## Technical Overview

HCCpred utilizes a combination of statistical methods and machine learning to ensure robust biomarker selection.

* **Statistical Analysis**: Employs DESeq2 and Limma for identifying differentially expressed genes (DEGs).
* **Machine Learning**: Developed using Logistic Regression and Random Forest models to create the final diagnostic panel.
* **Cross-Validation**: Performance was rigorously tested using leave-one-out and k-fold cross-validation techniques.

---

## Applications

* **Clinical Diagnostics**: Assisting in the early detection of HCC using tissue or blood-based gene expression signatures.
* **Biomarker Validation**: Serving as a benchmark for researchers looking to validate new liver cancer biomarkers.
* **Prognostic Insights**: Identifying genes that are not only diagnostic but also correlate with disease progression and patient outcomes.

---

## Contact & Authors

**Prof. Gajendra P. S. Raghava**
Department of Computational Biology, Indraprastha Institute of Information Technology (IIIT-Delhi), New Delhi, India.
**Email**: raghava@iiitd.ac.in

---

## License

This resource is open-access and distributed under the terms of the **Creative Commons Attribution-NonCommercial-NoDerivs 4.0 International (CC BY-NC-ND 4.0) License**.
