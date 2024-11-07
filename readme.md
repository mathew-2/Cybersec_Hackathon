# NLP Text Classification for Cybercrime Reporting

## Project Overview
This project aims to develop NLP models for classifying text descriptions of cybercrimes into relevant categories and subcategories. The models are built using a range of techniques, from traditional machine learning methods to state-of-the-art NLP models.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Preprocessing](#preprocessing)
- [Modeling](#modeling)
- [Evaluation Metrics](#evaluation-metrics)
- [Installation](#installation)


## Data Description
The training dataset consists of text descriptions of cybercrimes, categorized into various categories and subcategories. The key columns are:
- `category`: The main category of the crime.
- `sub_category`: The subcategory providing additional context.
- `crimeaditionalinfo`: The raw text description for analysis.

## Preprocessing
Text preprocessing includes:
- Converting text to lowercase.
- Removing special characters and punctuation.
- Tokenization.
- Removing stop words.
- Stemming or lemmatization.

The preprocessed data is stored in `data/cleaned_text.csv`.

## Modeling
Various models were trained, including:
- **Logistic Regression**: Baseline model for classification.
- **BERT**: Fine-tuned model for state-of-the-art performance.

## Evaluation Metrics
The models were evaluated using:
- **Accuracy**
- **Precision, Recall, F1-Score**
- **Confusion Matrix**

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-project-name.git
   cd your-project-name
2. Install the required packages:
   ```bash
   pip install -r requirements.txt

  
