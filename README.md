# Insurer Competitive Analysis
The Insurance Competitor Analysis Tool is a RAG-powered application that enables insurance analysts to quickly analyze and compare competitor financial statements (10K filings).

## Files Required
1. InsuranceAnalyzer.ipynb - The Jupyter notebook containing the analysis code
2. PDF files (to be placed in a 10KFilings directory):
      - travelers_10k_2024.pdf
      - progressive_10k_2024.pdf
      - chubb_10k_2024.pdf
      - allstate_10k_2024.pdf

# Setup Steps

## 1. Create Directory Structure
    your-project-folder/
    ├── InsuranceAnalyzer.ipynb
    └── 10KFilings/
        ├── travelers_10k_2024.pdf
        ├── progressive_10k_2024.pdf
        ├── chubb_10k_2024.pdf
        └── allstate_10k_2024.pdf

## 2. Environment Setup
  - Install Python 3.8 or higher
  - Install Jupyter Notebook

## 3. OpenAI API Key
  - In the notebook, replace "your-api-key-here" with your actual API key

## 4. Running the Notebook
  - Navigate to your project folder
  - Start Jupyter
  - Open InsuranceAnalyzer.ipynb
  - Run all cells (Cell → Run All)

# Common Issues and Solutions

## PDF Files Not Found

      Verify PDF files are in the 10KFilings directory
      Check file names match exactly
      Ensure proper file permissions

## API Key Error

      Verify API key is correctly set

## Package Installation Errors

      Try running pip install commands individually
      Update pip: pip install --upgrade pip
