# Insurer Competitive Analysis
The Insurance Competitor Analysis Tool is a RAG-powered application that enables insurance analysts to quickly analyze and compare competitor financial statements (10K filings).

<img width="1230" alt="Screenshot 2025-01-31 at 1 46 26 PM" src="https://github.com/user-attachments/assets/ad3ba7ef-8cf1-40be-8d9a-b59a77abbc11" />

## Files Required
1. Insurance10KAnalyserPrototype.ipynb - The Jupyter notebook containing the analysis code
2. PDF files (to be placed in a 10KFilings directory):
      - travelers_10k_2024.pdf
      - progressive_10k_2024.pdf
      - chubb_10k_2024.pdf
      - allstate_10k_2024.pdf

# Setup Steps

## 1. Create Directory Structure
    your-project-folder/
    ├── Insurance10KAnalyserPrototype.ipynb
    └── 10KFilings/
        ├── travelers_10k_2024.pdf
        ├── progressive_10k_2024.pdf
        ├── chubb_10k_2024.pdf
        └── allstate_10k_2024.pdf

## 2. Environment Setup
  - Install Python 3.8 or higher
  - Install Jupyter Notebook

## 3. OpenAI API Key
  - In Insurance10KAnalyserPrototype.ipynb, replace "your-api-key-here" with your actual API key OR;
  - Replace "your-api-key-here" with the temporary key shared with you

## 4. Running the Notebook
  - Navigate to your project folder
  - Start Jupyter
  - Open Insurance10KAnalyserPrototype.ipynb
  - Run all cells (Cell → Run All)

# Common Issues and Solutions

## PDF Files Not Found
- Verify PDF files are in the 10KFilings directory
- Check file names match exactly
- Ensure proper file permissions

## API Key Error
- Verify API key is correctly set

## Package Installation Errors

      Try running pip install commands individually
      Update pip: pip install --upgrade pip


# Usage Tips

## First Run
- Initial setup may take a few minutes
- Wait for all packages to install
- Allow document processing to complete


## Asking Questions
- Start with example questions
- Be specific in company names
- Complex questions may take longer to process


## Resource Management
- Close other resource-intensive applications
- Restart kernel if memory usage is high
- Clear output cells periodically
