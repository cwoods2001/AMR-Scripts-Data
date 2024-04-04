
Project Title: Investigating the Relationship Between Bacteriophage Presence and Antimicrobial Resistance Phenotype in Different Environments

Overview

This repository contains all necessary Python scripts, reference datasets, and supplementary information required to review, replicate, or extend the research conducted on the analysis of antimicrobial resistance (AMR) in Escherichia coli genomes and its relationship with Bacteriophage Presence. Our study focuses on identifying AMR genes and prophage communities within 272 E. coli genomes and their relationship to the phenotype of antimicrobial resistance, utilizing a combination of bioinformatics tools and machine learning algorithms.

Contents

Scripts/: Contains all Python scripts and Unix shell commands used for data processing and analysis.
Data/: This directory includes the output CSV files and the unified dataset created for machine learning analysis.
Analysis/: Contains the Jupyter notebooks and R scripts used for GeNomad analysis, including the creation of Sourmash sketches and the identification of elbow points.
ARFF_Files/: The ARFF files generated for use with the Weka machine learning software are stored here.
Documentation/: Additional documentation on the methodologies and algorithms used in the study.

Getting Started

To replicate our study or use our datasets and scripts for your research, follow these steps:

Clone this repository to your local machine using git clone https://github.com/cwoods2001/AMR-Scripts-Data.
Ensure you have the required dependencies installed. A list of dependencies can be found in requirements.txt.
Review the Scripts/README.md for details on the preprocessing steps and how to execute the scripts.
Dependencies

Python 3.8+
R version 4.0+
Weka 3.8.6
Additional Python and R packages are listed in requirements.txt.
Usage

Each script and notebook is designed to be standalone, allowing you to execute each part of the analysis independently:

Data Preprocessing: python Scripts/preprocess_data.py
Analysis: Instructions for running the analysis notebooks are provided within each notebook.

Contributing

We welcome contributions and suggestions to improve the analysis or extend the research. Please open an issue or pull request with your contributions or suggestions.

Citation

If you use the data, scripts, or methodologies from this project in your research, please cite:

Your research paper or dataset********
Any other relevant citations
License

This project is made available under the MIT License. See LICENSE for more details.

Contact

For any questions or further information, please contact COREY WOODS.




