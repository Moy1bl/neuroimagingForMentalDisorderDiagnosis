# ML driven Neuroimaging Analysis for Mental Disorder Diagnostics

## Project Overview
This research project focuses on leveraging machine learning (ML) for diagnosing mental disorders using neuroimaging data. The motivation stems from the prevalent issue of misdiagnosis in psychiatry, traditionally relaying on behavioral observations (e.g., DSM criteria) rather than biomarkers in the brain. Considering advancments in brain-imaging technology and ML - exploring neuro-basis for diagnositic becomes a highly important avenue to consider.

### Key Objectives
- **Literature Review**: Assess existing analysis pipelines, successes, and limitations in ML applications to neuroimaging for mental health diagnostics.
- **Data Analysis**: Hands-on exploration of the ADHD200 dataset from INDI's 1000 Functional Connectomes Project, including data characterization, phenotypic analysis, and functional connectivity studies.

## Current Status
- The data is non-BIDS compliant and has been preliminarily explored.
- Phenotypic data analysis includes deriving mean, standard deviation, and median values for ADHD and control groups.
- Visual inspection of anatomical group scan mean images.
- Correlation matrices derived from functional connectivity using standard brain atlases (e.g., Harvard atlas).
- Initial ML experiment with LSTM architecture yielded a 62% test accuracy, indicating the need for further data preprocessing and hyperparameter tuning.

### Challenges Faced
- Limited computational resources.
- Non-standardized brain scans leading to uneven feature vectors.
- Initial analysis suggest required improvements through preprocessing and hyperparameter optimization.

## Potential Future Direction
- Access raw data from the Amazon S3 bucket and perform comprehensive preprocessing.
- Explore diverse ML models and architectures.
- Investigate the diagnosis of overlapping mental disorders and their clinical applicability.
- Experiment with data augmentation and combining neuroimaging with demographical and DSM-based measures.
