# Breast Cancer Detection

## Overview
Breast Cancer Detection is an open-source project aimed at building a machine learning model for the detection of Invasive Ductal Carcinoma (IDC), the most common subtype of all breast cancers. The project leverages a dataset sourced from Kaggle, consisting of histopathology images, to train and evaluate models that can aid in the identification of cancerous tissue patches.

## Table of Contents
- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Authors](#authors)
- [License](#license)

## About the Project
Early and accurate identification of IDC is crucial for effective treatment planning. This project aims to automate the process of IDC detection using deep learning techniques, thus helping pathologists focus on the most relevant areas of the sample and improve diagnostic efficiency.

### Key Objectives:
- Create a robust pipeline for processing and analyzing histopathology images.
- Build a model capable of classifying patches as IDC positive (1) or IDC negative (0).
- Evaluate the performance of the model using standard classification metrics.

## Dataset
The dataset used in this project is publicly available on [Kaggle](https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images/data). It comprises patches extracted from 162 whole mount slide images of breast cancer specimens scanned at 40x magnification.

### Dataset Details:
- **Total Patches**: 277,524
- **Patch Size**: 50 x 50 pixels
- **IDC Negative**: 198,738 patches
- **IDC Positive**: 78,786 patches
- **File Naming Convention**: `u_xX_yY_classC.png`
  - `u`: Patient ID
  - `X`: x-coordinate of the patch
  - `Y`: y-coordinate of the patch
  - `C`: Class label (0 for non-IDC, 1 for IDC)

### Source and Citation:
- The original dataset and related research can be found [here](http://gleason.case.edu/webdata/jpi-dl-tutorial/IDC_regular_ps50_idx5.zip).
- Citation for the dataset: [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/27563488) and [SPIE](http://spie.org/Publications/Proceedings/Paper/10.1117/12.2043872).


## Authors

- **Mingi Kang** - *Collaborator* - [mkang817415](https://github.com/mkang817415)
- **Isaac Klar** - *Collaborator* 
- **Karam Al-Askar** - *Collaborator* 
- **Shaamil Karim** - *Collaborator*
- **Dr. Roland Molontayn** - *Instructor*

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

