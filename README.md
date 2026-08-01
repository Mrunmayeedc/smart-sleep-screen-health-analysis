# Smart Sleep & Screen Health Analysis

## Overview

Smart Sleep & Screen Health Analysis is a research-oriented data science project that investigates the relationship between screen exposure and sleep health across different age groups. The project combines two complementary public datasets representing children, teenagers, and adults to perform exploratory data analysis, predictive modelling, and cross-age-group comparisons.

The project follows a complete data science workflow, including data preprocessing, feature engineering, machine learning model development, and research-based interpretation of the results.

## Research Objective
The primary objective of this study is to analyse how screen exposure influences sleep health across different age groups and to determine whether increasing screen time is associated with sleep-related issues.

## Technologies Used
- Python
- Pandas
- NumPy
- TensorFlow / Keras
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Datasets
Two publicly available datasets were used.
### Adult Dataset
**File:** `Dry_Eye_Dataset.csv`
Contains information related to:
- Age
- Gender
- Sleep Duration
- Sleep Quality
- Stress Level
- Physical Activity
- Average Screen Time
- Sleep Disorder
- Dry Eye Disease

### Children & Teen Dataset
**File:** `Indian_Kids_Screen_Time.csv`
Contains information related to:
- Age
- Gender
- Average Daily Screen Time
- Primary Device
- Health Impacts
- Educational vs Recreational Screen Usage
- Urban/Rural Classification

The datasets were analysed independently before creating a harmonized comparison dataset.

## Repository Structure
```
smart-sleep-screen-health-analysis/

├── data/
│   ├── Dry_Eye_Dataset.csv
│   ├── Indian_Kids_Screen_Time.csv
│   ├── cleaned_adult_dataset.csv
│   ├── cleaned_kids_dataset.csv
│   ├── harmonized_comparison.csv
│   └── harmonized_summary.csv
│
├── notebooks/
│   ├── 01_data_preprocessing_and_exploratory_analysis.ipynb
│   ├── 02_machine_learning_analysis.ipynb
│   └── 03_cross_age_group_findings.ipynb
│
├── results/
│   ├── model_performance.csv
│   └── Project visualizations
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

## Project Workflow
### Notebook 1 – Data Preprocessing & Exploratory Analysis
- Data loading
- Data cleaning
- Missing value analysis
- Duplicate removal
- Exploratory Data Analysis
- Feature engineering
- Dataset harmonization

Outputs:
- Cleaned datasets
- Harmonized comparison dataset
- Exploratory visualizations

### Notebook 2 – Machine Learning Analysis
Separate predictive models are developed for the adult and children datasets.
Algorithms used:
- Random Forest Classifier
- Artificial Neural Network (TensorFlow)
Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve
- Feature Importance

Outputs:
- Trained models
- Performance comparison
- Evaluation visualizations

### Notebook 3 – Cross-Age Group Analysis
This notebook combines the processed datasets to perform research-oriented analysis.
Tasks include:
- Screen time comparison across age groups
- Sleep health comparison
- Statistical summaries
- Visualization of research findings
- Interpretation of results
- Study limitations
- Future work

## Machine Learning Pipeline
1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Dataset Harmonization
6. Feature Encoding
7. Train-Test Split
8. Feature Scaling
9. Random Forest Classification
10. Neural Network Classification
11. Model Evaluation
12. Cross-Age Group Analysis
13. Research Conclusions

## Key Results
The study demonstrates meaningful relationships between screen exposure and sleep health across different age groups.
Major observations include:
- Screen time patterns differ considerably between children, teenagers, and adults.
- Increased screen exposure is associated with a higher prevalence of sleep-related issues.
- Lifestyle factors such as physical activity and stress influence sleep quality among adults.
- Random Forest and Neural Network models achieved strong predictive performance on both datasets.

## Results
The repository includes visualizations generated throughout the project, including:
- Age distribution
- Screen time distribution
- Correlation heatmaps
- Screen time versus sleep quality
- Feature importance
- Confusion matrices
- Model comparison
- Cross-age group comparison
  
## Future Improvements
Potential extensions of this work include:
- Incorporating longitudinal sleep datasets
- Expanding the study to include participants over 45 years of age
- Integrating wearable device data
- Applying Explainable AI techniques such as SHAP and LIME
- Investigating device-specific effects on sleep health
  
## Requirements
Install the required Python packages using:
```bash
pip install -r requirements.txt
```
## How to Run

1. Clone the repository.
```bash
git clone https://github.com/your-username/smart-sleep-screen-health-analysis.git
```
2. Install the required libraries.
```bash
pip install -r requirements.txt
```
3. Execute the notebooks in order:
- `01_data_preprocessing_and_exploratory_analysis.ipynb`
- `02_machine_learning_analysis.ipynb`
- `03_cross_age_group_findings.ipynb`

