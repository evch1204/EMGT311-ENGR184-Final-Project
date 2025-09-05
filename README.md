# EMGT 311 - Engineering Management Final Project

## Project Overview

This project focuses on **Electromyography (EMG) Data Analysis and Risk Classification** using machine learning techniques. The goal is to analyze EMG signals from different individuals and classify them into high-risk and low-risk categories based on various physiological parameters.

## Project Structure

```
EMGT_311_Final_Project/
├── EMGT_311_Final_Project_code.ipynb    # Main Jupyter notebook with analysis
├── EMGT311-ENGR184-Final Project Report.pdf      # Detailed project report
├── EMGT311-ENGR184-Final Project Presentation.pdf # Project presentation slides
├── EMGT311-ENGR184-Final Project.zip            # Compressed project files
└── README.md                                    # This file
```

## Dataset Description

The project analyzes four main datasets:
- **P1_High.csv** - Person 1 High Risk EMG data
- **P1_Low.csv** - Person 1 Low Risk EMG data  
- **P2_High.csv** - Person 2 High Risk EMG data
- **P2_Low.csv** - Person 2 Low Risk EMG data

Each dataset contains 56 columns of EMG signal data with the first 5 rows containing metadata.

## Features

### Data Processing
- CSV data loading and preprocessing
- Data cleaning and normalization
- Feature engineering and scaling
- Outlier detection and removal

### Machine Learning Models
- **Logistic Regression** - Binary classification (Low Risk vs High Risk)
- **Random Forest Classifier** - Ensemble learning approach
- **Principal Component Analysis (PCA)** - Dimensionality reduction

### Analysis and Visualization
- Raw EMG signal plotting
- Model performance evaluation
- Confusion matrix analysis
- ROC curve analysis
- Classification reports
- Feature importance analysis

## Technologies Used

- **Python** - Primary programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Scikit-learn** - Machine learning algorithms
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Google Colab** - Cloud-based development environment

## Key Findings

The project demonstrates:
- Successful classification of EMG data into risk categories
- Comparison of different machine learning approaches
- Feature importance analysis for risk assessment
- Model performance evaluation metrics

## Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook or Google Colab
- Required Python packages (see requirements below)

### Installation
1. Clone or download the project files
2. Install required dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Open `EMGT_311_Final_Project_code.ipynb` in Jupyter Notebook or Google Colab

### Data Requirements
- Place the CSV files in the appropriate directory structure
- Ensure data files follow the expected format (56 columns, skip first 5 rows)

## Usage

1. **Data Loading**: The notebook automatically loads and processes the four EMG datasets
2. **Preprocessing**: Data is cleaned, normalized, and prepared for analysis
3. **Model Training**: Multiple machine learning models are trained and evaluated
4. **Results Analysis**: Performance metrics and visualizations are generated
5. **Risk Classification**: Final classification results for high/low risk assessment

## Model Performance

The project evaluates models using:
- **Accuracy Score** - Overall classification accuracy
- **Precision & Recall** - Model performance per class
- **F1-Score** - Harmonic mean of precision and recall
- **Confusion Matrix** - Detailed classification results
- **ROC Curve** - Model discrimination ability

## Contributing

This is a final project for EMGT 311 - Engineering Management course. For questions or issues, please refer to the project report or presentation materials.

## License

This project is created for educational purposes as part of the EMGT 311 course requirements.

## Authors

- **Course**: EMGT 311 - Engineering Management
- **Institution**: Engineering Department
- **Semester**: Final Project
- **Project**: Group Project

## Acknowledgments

- Course instructors and teaching assistants
- EMG data collection and preprocessing teams
- Machine learning and data science community resources
- Thank you to Isabel for their contribution

---

*This README provides an overview of the EMGT 311 Final Project. For detailed analysis and results, please refer to the Jupyter notebook and project report.*
