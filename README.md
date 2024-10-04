# Testable-PGx-Genes-Database

This repository contains Python script and data for building a Testable Pharmacogenomic (PGx) Genes Database, which includes gene-to-genotype mappings, therapeutic areas, and associated drugs. The goal of this project is to create a structured database that supports personalized medicine by allowing clinicians and researchers to identify relevant drugs and dosing recommendations based on gene and genotypes.

## Table of Contents

Project Overview

File Descriptions

Setup Instructions

Data Structure

## Project Overview

The Testable PGx Genes Database focuses on extracting and structuring data from pharmacogenomic sources, primarily PharmGKB, to provide information about genes, genotypes, therapeutic areas, and associated drugs. This database is designed to support applications that require pharmacogenomic testing and personalized medication recommendations.

## File Descriptions

1. Build Testable PGx Genes.ipynb

This is a Python script that contains step-by-step code for building the testable PGx gene database.

3. Testable PGx Genes Database QC Report.docx
   
This is a quality control report document for testable PGx genes database.

5. Testable_PGx_Genes.xlsx
   
This is the database build from the all genes CSV's.

7. gene_name.csv

This repository contains individual CSV's for all the genes.

## Setup Instructions

### Prerequisites

To run the code in this repository, you'll need:

- Python 3.x
- Required Python packages:
    - pandas
    - selenium
    - beautifulsoup4
    - requests
- ChromeDriver (for Selenium web scraping)

## Data Structure

The data is stored in a CSV format with the following structure:

Column Name        | Description
-----------        | -----------
Gene	           | Name of the pharmacogenomic gene
Genotype(s)	       | Genotypes to be tested 
Therapeutic Area(s)| List of therapeutic areas relevant to the drugs
Drug(s)	           | Drugs associated with the gene and genotype

Drugs with no pharmacogenomic clinical action are excluded from the output.
  
