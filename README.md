# Medical Text Classification

## Overview
This project focuses on the development and evaluation of several machine learning models to classify medical texts into categories such as Neoplasms, Digestive System Diseases, Nervous System Diseases, Cardiovascular Diseases, and General Pathological Conditions. The repository is rich with resources and documentation, aiming to support educational purposes and collaborative development.

## Data and Preprocessing
- **Dataset**: Utilizes medical texts provided in CSV format, requiring extensive cleaning and preprocessing.
- **Preprocessing Steps**: Detailed in `Data Pre-Processing.ipynb`, involving data cleaning, normalization, tokenization, stopwords removal, and vectorization.
- **Labels**: Stored separately and processed to align with training data needs.

## Models Implemented
- **BERT (Bidirectional Encoder Representations from Transformers)**: Utilizes context from both previous and subsequent words to understand text.
- **Recurrent Neural Networks (RNN)**: Manages sequence data, ideal for the sequential nature of text.
- **Logistic Regression**: Serves as a baseline for binary classification, extended here for multi-class scenarios.
- **Support Vector Machine (SVM)**: Adapted for high-dimensional text data classification.
- **XGBoost**: Employs gradient boosted decision trees for structured data classification, known for speed and performance.

## Evaluation
- **Confusion Matrices**: Visual tools for evaluating model performance, showing true positives, false positives, false negatives, and true negatives across different disease categories.
- **Performance Metrics**: Includes accuracy, precision, recall, and F1-scores, integrated within the notebooks and summarized through images and charts in the repository.

## Documentation and Usability
- **Comprehensive Documentation**: Includes detailed setup and installation instructions, usage details, and contribution guidelines.
- **Setup Instructions**: Detailed steps for setting up a virtual environment, installing dependencies, and running the notebooks.
- **Open for Contributions**: Encourages enhancements to models, additional features, better preprocessing methods, and more documentation.

## Output and Contribution
- **Utility**: Demonstrates the application of machine learning to medical text classification.
- **Resource for Learning**: Serves as a guide and starting point for applying machine learning in medical contexts.
- **Open-Source Collaboration**: Designed to be collaborative, with detailed contribution guidelines.

## How to Contribute
Contributors are welcome to:
- Improve existing models and add new features.
- Enhance data preprocessing techniques.
- Expand and refine documentation and examples.

Please submit pull requests or open issues to discuss proposed changes.

## Installation
Clone the repository and navigate into it:
```bash
git clone https://github.com/JadAlaouie/NLP-Medical-Text-Classification.git
cd medical-text-classification
