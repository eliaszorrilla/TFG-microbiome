

# Bioinformatic Analysis of the *hutH* Gene in the Human Gut Microbiome Across Dysbiosis Contexts

## 📌 General Description

This repository contains the computational workflow and data analysis pipeline developed for the **Bachelor’s Thesis (TFG)** in **Food Science and Technology**.

The project focuses on the computational extraction, processing, and visualization of metagenomic data to analyze the prevalence and abundance of the **hutH gene** (histidine ammonia-lyase) in the human gut microbiome. The analysis compares healthy profiles with various contexts of intestinal dysbiosis.

Using **Python** and advanced data manipulation techniques, the pipeline processes clinical and omics data from **239 samples**, integrating metadata to classify patients into **5 distinct clinical groups**. 

---

## 🎯 Project Objectives

- Automate the genomic screening of **42 bacterial species** through public APIs (MGnify, NCBI).
- Process, clean, and restructure complex metagenomic abundance matrices using Python.
- Perform statistical normalization of biological data to correct mathematical biases across patient groups.
- Develop robust, reproducible data visualizations to understand the role of *hutH*-carrying bacteria in gut dysbiosis.

---

## 🧪 Data Analyzed

This project heavily relies on bioinformatic data wrangling and API interactions:

- **Metagenomic Data:** Extracted via **MGnify**, **ENA**, and **NCBI** databases.
- **Bacterial profiles:** Genomic screening of 42 specific species.
- **Clinical Metadata:** Integration of patient data to categorize **239 samples** into 5 experimental/clinical groups.
- **Abundance Matrices:** Handling multidimensional dataframes (Absolute and Normalized counts).

---

## 🛠️ Technologies and Libraries

- **Language:** Python 3
- **Data Manipulation & Cleaning:** `pandas`, `numpy`
- **Data Visualization:** `seaborn`, `matplotlib`
- **Bioinformatics & API:** `Biopython`, `requests` (for automated database querying)

---

## 📂 Repository structure
```
TFG/
└── data/
│   ├── raw/ # Raw data
│   └── processed/ # Preprocessed data
├── notebooks/ # Jupyter notebooks with analyses
├── results/ # Figures, tables, and outputs
├── README.md # Project description
├── .gitignore
└── requirements.txt # Project dependencies
```
---

## ⚙️ Analysis Methodology

1. **Automated Data Extraction:**
   - Scripting queries to MGnify/NCBI to retrieve genome data for targeted species.
2. **Data Wrangling & Cleaning:**
   - Merging clinical metadata with abundance matrices.
   - Restructuring DataFrames to solve dimensional mismatches and missing individuals.
3. **Statistical Normalization:**
   - Transforming absolute abundance counts into relative metrics per individual to ensure unbiased cross-group comparisons.
4. **Data Visualization:**
   - Generation of normalized plots using Seaborn to highlight differences across the 5 clinical groups.

---

## 🚧 Project Status

**Completed.** *Note: The repository is currently in the final phase of code optimization, refactoring, and inline documentation before the final academic defense.*

---

## 👩‍🎓 Authorship

- **Author:** Elías Zorrilla Galdón  
- **Degree:** Food Science and Technology  
- **University:** University of Granada (UGR) 
- **Academic year:** 2025–2026

---

## 📄 License

This project has been developed for academic purposes. The use of the data and code is restricted to educational and research contexts unless otherwise stated.