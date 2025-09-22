# Titanic Dataset Analysis - Internship Task 1

This repository contains a comprehensive analysis of the Titanic dataset as part of an internship task focusing on data preprocessing and exploratory data analysis.

## 📊 Project Overview

This project demonstrates essential data preprocessing techniques including:
1. Dataset import and exploration
2. Missing value handling
3. Categorical feature encoding
4. Numerical feature normalization/standardization
5. Outlier detection and visualization

## 🎯 Task Objectives

### 1. Import the dataset and explore basic info (nulls, data types)
- Load the Titanic dataset
- Examine data structure and basic information
- Identify missing values and data types

### 2. Handle missing values using mean/median/imputation
- Analyze missing value patterns
- Apply appropriate imputation strategies
- Handle missing data in Age, Cabin, and Embarked columns

### 3. Convert categorical features into numerical using encoding
- Encode categorical variables (Sex, Embarked)
- Apply appropriate encoding techniques
- Prepare features for machine learning

### 4. Normalize/standardize the numerical features
- Scale numerical features for better model performance
- Apply standardization techniques
- Ensure feature comparability

### 5. Visualize outliers using boxplots and remove them
- Create boxplot visualizations for numerical features
- Identify and analyze outliers
- Apply outlier removal strategies

## 📁 Dataset Information

**Dataset**: Titanic Dataset
- **Source**: [Download Link](https://www.kaggle.com/c/titanic/data)
- **Size**: 891 passengers
- **Features**: 12 columns including PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive development environment

## 📋 Repository Structure

```
Internship_Task1/
├── README.md                    # Project documentation
├── Internship_task1.ipynb      # Main analysis notebook
└── requirements.txt            # Python dependencies (if applicable)
```

## 🚀 Getting Started

### Prerequisites
- Python 3.6 or higher
- Jupyter Notebook or JupyterLab
- Required Python packages (see installation below)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Chakresh7/Internship_Task1_.git
cd Internship_Task1_
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open `Internship_task1.ipynb` to view the analysis

## 📈 Key Findings

The analysis reveals several important insights about the Titanic dataset:

- **Missing Values**: Significant missing data in Age (177 missing) and Cabin (687 missing) columns
- **Survival Patterns**: Higher survival rates among women and higher-class passengers
- **Feature Relationships**: Age, fare, and passenger class show interesting correlations with survival

## 🔍 Analysis Steps

1. **Data Loading & Exploration**
   - Import libraries and load dataset
   - Basic dataset information and statistics
   - Data type examination

2. **Missing Value Analysis**
   - Identify missing value patterns
   - Apply imputation strategies
   - Validate data completeness

3. **Feature Engineering**
   - Encode categorical variables
   - Create new features if needed
   - Prepare data for modeling

4. **Data Visualization**
   - Create boxplots for outlier detection
   - Generate correlation matrices
   - Visualize data distributions

5. **Data Preprocessing**
   - Normalize numerical features
   - Handle outliers appropriately
   - Final dataset preparation

## 📊 Visualizations

The notebook includes various visualizations:
- Boxplots for outlier detection
- Histograms for distribution analysis
- Correlation heatmaps
- Survival rate analysis charts

## 🤝 Contributing

This is an internship task project. For questions or suggestions, please contact the repository owner.

## 📝 License

This project is for educational purposes as part of an internship program.

## 👨‍💻 Author

**Chakresh**
- GitHub: [@Chakresh7](https://github.com/Chakresh7)

## 📞 Contact

For any questions about this project, please open an issue in the repository or contact the author directly.

---

*This project demonstrates practical data science skills including data preprocessing, exploratory data analysis, and visualization techniques using real-world data.*
