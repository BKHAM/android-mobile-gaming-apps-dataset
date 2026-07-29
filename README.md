# Android Mobile Gaming Research Dataset

## Overview

This repository contains the datasets, Android manifest artifacts, and supporting files used in our empirical studies investigating privacy and security characteristics of Android mobile gaming applications.

The repository was created to promote research transparency, reproducibility, and open science by providing the data and supporting materials required to reproduce the analyses presented in our publications.

---

## Repository Structure

```
Android-Mobile-Gaming-Research/
│
├── Dataset/
│   ├── Master_Dataset.xlsx
│   └── App_Mapping.xlsx
│
├── AndroidManifest/
│   ├── App01_xmltree.txt
│   ├── ...
│   └── App41_xmltree.txt
│
├── Statistical_Analysis/
---

## Dataset Description

The dataset consists of **41 popular Android mobile gaming applications**, including:

- **20 children-oriented mobile games**
- **21 general-audience mobile games**

Applications were selected from the Google Play Store based on popularity indicators, installation counts, and predefined inclusion criteria described in the associated publications.

To avoid promoting or negatively affecting individual developers, all applications are anonymized using identifiers:

- App01
- App02
- ...
- App41

The mapping between anonymized identifiers and application names is provided separately.

---

## Android Manifest Files

The **AndroidManifest** directory contains one file for each analysed application.

Each file is the output of:

```
aapt dump xmltree <APK> AndroidManifest.xml
```

These files preserve the complete manifest structure and were used during the static analysis performed in the associated studies.

The manifest artifacts contain configuration information including:

- Package information
- SDK versions
- Permission declarations
- Backup configuration
- Network security configuration
- Exported components
- Application metadata
- Intent filters
- Providers
- Services
- Receivers
- Other manifest-level security attributes

---

## Reproducibility

The repository provides the supporting materials required to reproduce the static analysis reported in the associated publications.

These materials include:

- Android manifest artifacts
- Master datasets
- Privacy indicators
- Statistical analysis outputs
- Figures
- Supplementary tables

The repository does **not** include APK files because they remain the intellectual property of their respective developers and distributors.

---

## Software Used

The analyses were conducted using publicly available tools, including:

- Apktool
- Android Asset Packaging Tool (AAPT)
- jadx
- Microsoft Excel
- Jamovi

---

## Citation

If you use this dataset or any material from this repository, please cite the corresponding publication.

---

## License

This repository is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** License.

---

## Contact

**Bakheet Aljedaani**

Computer Science Department

Umm Al-Qura University

Makkah, Saudi Arabia

Email: bhjedaani@uqu.edu.sa
