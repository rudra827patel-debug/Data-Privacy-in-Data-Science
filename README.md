# Data Privacy in Data Science

## Project Overview

This project demonstrates basic data privacy techniques
using Python and Pandas.

It explains how personal information can be protected
while retaining useful information for data analysis.

## Objectives

- Understand personal and sensitive data.
- Identify privacy risks in a dataset.
- Apply email masking.
- Perform age generalization.
- Generalize city information into regions.
- Generate anonymous customer IDs.
- Create a privacy-preserved dataset.
- Analyse data without displaying unnecessary
  personal identifiers.

## Technologies Used

- Python
- Pandas
- Jupyter Notebook
- GitHub

## Dataset

The project uses an educational customer purchase
dataset containing 20 sample records.

The dataset includes customer IDs, names, ages,
gender, cities, email addresses, purchase amounts,
and payment methods.

## Privacy Techniques

### 1. Email Masking
Email addresses are partially hidden to reduce
the exposure of personal information.

### 2. Age Generalization
Exact ages are converted into age groups.

### 3. Region Generalization
City names are replaced with broader regional
categories.

### 4. Anonymization
Anonymous customer IDs are generated to reduce
direct identification.

### 5. Privacy-Preserved Dataset
A separate dataset is created containing
transformed identifiers and useful analytical
attributes.

## Data Analysis

The project analyses:

- Number of customers in each age group
- Customer distribution by region
- Payment method distribution
- Total purchase amount
- Average purchase amount
- Maximum and minimum purchase amounts

## How to Run

1. Download or clone this repository.
2. Install Python and Jupyter Notebook.
3. Install Pandas:

   pip install pandas

4. Open Data_Privacy_Analysis.ipynb in Jupyter
   Notebook or Google Colab.
5. Run the notebook cells in order.

## Expected Outcome

The project demonstrates how masking, anonymization,
and generalization can reduce the exposure of
personal identifiers while preserving useful
information for analysis.
