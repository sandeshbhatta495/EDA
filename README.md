# Titanic Dataset - Exploratory Data Analysis (EDA)

A comprehensive exploratory data analysis of the Titanic survival dataset, covering descriptive statistics, univariate analysis, bivariate analysis, data visualization, and automated profiling.

## 📋 Project Overview

This project provides an in-depth exploration of the Titanic dataset through multiple analytical approaches:
- **Descriptive Statistics**: Understanding data dimensions, types, and basic characteristics
- **Univariate Analysis**: Individual variable analysis and distributions
- **Bivariate Analysis**: Relationships between pairs of variables
- **Data Visualization**: Visual representations of patterns and insights
- **Automated Profiling**: Comprehensive data profiling reports using pandas-profiling

## 📁 Project Structure

```
02_EXPLORATORY_DATA_ANALYSIS/
├── 02a_DESCRIPTIVE_STATISTICS/
│   └── Descriptive_Statistics/
│       ├── day19.ipynb              # Basic descriptive statistics
│       └── train.csv                # Titanic training dataset
├── 02b_UNIVARIATE_ANALYSIS/
│   └── Univariate_Analysis/
│       ├── uni.ipynb                # Univariate analysis
│       └── train.csv
├── 02c_BIVARIATE_ANALYSIS/
│   └── Bivariate_Analysis/
│       ├── day21.ipynb              # Bivariate analysis
│       └── train.csv
├── 02d_DATA_VISUALIZATION/          # Visualization outputs
├── 02e_PANDAS_PROFILING/
│   └── Pandas_profiling/
│       ├── titanic survival.ipynb   # Comprehensive pandas profiling
│       ├── cleaned_data.csv
│       └── datas/
│           ├── train.csv            # Titanic training data
│           ├── test.csv             # Titanic test data
│           └── gender_submission.csv
└── README.md                        # This file
```

## 🎯 Analysis Sections

### 1. **Descriptive Statistics** (02a_DESCRIPTIVE_STATISTICS)
Answers fundamental questions about the dataset:
- How big is the data?
- How does the data look?
- What are the data types?
- Are there missing values?
- Statistical summary (mean, median, std, etc.)
- Any duplicate values?
- Correlation analysis with survival target

### 2. **Univariate Analysis** (02b_UNIVARIATE_ANALYSIS)
Individual variable analysis examining:
- Distribution patterns
- Central tendency measures
- Spread and variability
- Outlier detection

### 3. **Bivariate Analysis** (02c_BIVARIATE_ANALYSIS)
Relationship analysis between variables:
- Correlation matrices
- Cross-tabulations
- Joint distributions
- Survival patterns across variables

### 4. **Data Visualization** (02d_DATA_VISUALIZATION)
Visual insights including:
- Count plots for categorical features
- Distribution plots for numerical features
- Survival by gender analysis
- Survival by passenger class analysis
- Relationship visualizations

### 5. **Automated Profiling** (02e_PANDAS_PROFILING)
Comprehensive data reports using pandas-profiling:
- Automatic missing value analysis
- Correlation discovery
- Variable type detection
- Interactive HTML reports

## 📊 Dataset Information

**Titanic Dataset** contains information about passengers aboard the RMS Titanic:

### Key Variables:
- **Survived**: Target variable (0 = No, 1 = Yes)
- **PassengerId**: Unique identifier
- **Pclass**: Passenger class (1, 2, 3)
- **Name**: Passenger name
- **Sex**: Gender (male, female)
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Ticket fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C=Cherbourg, Q=Queenstown, S=Southampton)

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.7+
pandas
numpy
matplotlib
seaborn
pandas-profiling
jupyter
```

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd 02_EXPLORATORY_DATA_ANALYSIS
```

2. Install required packages
```bash
pip install pandas numpy matplotlib seaborn pandas-profiling jupyter
```

3. Navigate to any analysis folder and open the Jupyter notebook
```bash
cd 02a_DESCRIPTIVE_STATISTICS/Descriptive_Statistics
jupyter notebook day19.ipynb
```

## 📈 Key Findings

Based on the exploratory analysis:

- **Survival Rate**: Examine the overall survival count and patterns
- **Gender Impact**: Significant survival difference between males and females
- **Class Distribution**: Passenger class strongly correlates with survival
- **Age Factor**: Age-based patterns in survival rates
- **Missing Data**: Notable missing values in Age and Cabin columns

## 🔧 How to Use

1. **Run Individual Analysis**: Each notebook can be run independently
2. **Modify Data**: Replace `train.csv` with your own Titanic dataset
3. **Extend Analysis**: Add new cells to perform additional analysis
4. **Generate Reports**: Use pandas-profiling for automated analysis reports

## 📝 Notebooks Overview

| Notebook | Focus | Key Metrics |
|----------|-------|-------------|
| day19.ipynb | Descriptive Statistics | Shape, dtypes, null values, correlation |
| uni.ipynb | Univariate Analysis | Distribution, variance, outliers |
| day21.ipynb | Bivariate Analysis | Relationships, cross-tabulation |
| titanic survival.ipynb | Comprehensive Profiling & Visualization | Full EDA with plots |

## 🎓 Learning Objectives

This project helps you:
- Master pandas data manipulation and analysis
- Create effective data visualizations
- Understand statistical measures and their interpretation
- Develop a systematic EDA workflow
- Learn correlation and bivariate analysis techniques
- Generate automated data quality reports

## 📚 Resources

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Pandas-profiling Documentation](https://pandas-profiling.ydata.ai/)

## 💡 Next Steps

- Perform multivariate analysis
- Build predictive models for survival
- Create an interactive dashboard
- Generate insights for business decisions

## 📄 License

This project uses the public Titanic dataset from Kaggle.

## 👤 Author

Created as part of exploratory data analysis training and learning.

---

**Last Updated**: January 2026

For questions or suggestions, please feel free to contribute or open an issue.
