# Diversity-Analysis-Feature-Engineering
# Google Tech Diversity Analysis (2014–2023)

## 📌 Project Overview

This project explores workforce diversity in the technology industry by analyzing Google's ethnicity diversity dataset from 2014 to 2023.

The main objective is to understand the representation of different ethnic groups over time using data preprocessing, feature engineering, feature selection, dimensionality reduction, data visualization, and machine learning techniques.

The project also applies Linear Regression to predict the representation percentage of the Asian+ ethnic group based on other demographic attributes.

## 🎯 Objectives

- Analyze Google's workforce ethnicity diversity data.
- Identify categorical, discrete, and continuous variables.
- Handle missing values and preprocess the dataset.
- Apply normalization and encoding techniques.
- Perform feature engineering and feature extraction.
- Select relevant features using statistical and machine learning methods.
- Apply Principal Component Analysis (PCA).
- Visualize data distributions and correlations.
- Build a Linear Regression model for prediction.

## 📂 Dataset

**Dataset:** Google Ethnicity Dataset (2014–2023)

The dataset contains workforce representation information across different ethnic groups.

### Key Attributes

- Characteristic (Year)
- Asian+
- Black+
- Latinx+
- Native American+*
- White+

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## ⚙️ Project Workflow

### 1. Data Loading and Inspection
- Loaded the Google ethnicity dataset using Pandas.
- Inspected dataset structure and column information.

### 2. Data Preprocessing
- Checked for missing values.
- Converted percentage-based columns into numerical values.
- Applied MinMax Scaling for normalization.

### 3. Data Encoding
- Applied Label Encoding to categorical variables.
- Used One-Hot Encoding for discrete features.

### 4. Feature Engineering
- Created a new feature called `Years_Since_Start`.
- Generated polynomial features using PolynomialFeatures.

### 5. Feature Extraction
- Used Random Forest Regressor to identify important features.

### 6. Feature Selection
- Examined feature correlations.
- Identified highly correlated features and potential multicollinearity.

### 7. Dimensionality Reduction
- Applied Principal Component Analysis (PCA).
- Analyzed explained variance ratios.
- Visualized principal component relationships.

### 8. Data Visualization
- Generated histograms to understand ethnicity distributions.
- Created correlation heatmaps to examine relationships between attributes.

### 9. Machine Learning Model
- Implemented Linear Regression.
- Used an 80:20 train-test split.
- Predicted the Asian+ representation percentage.
- Evaluated the model using:
  - Mean Squared Error (MSE)
  - R-squared (R²)

## 📊 Results

The project demonstrates the application of data analytics and machine learning techniques to workforce diversity data.

The Linear Regression model compares actual and predicted Asian+ representation percentages using a scatter plot.

Model performance is evaluated using MSE and R² metrics.

## 🚀 How to Run the Project

1. Clone this repository:

```bash
git clone <your-repository-link>
```

2. Navigate to the project folder:

```bash
cd <project-folder>
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

4. Ensure that `google_ethnicity.csv` is available in the project directory.

5. Launch Jupyter Notebook:

```bash
jupyter notebook
```

6. Open `Diversity Analyis.ipynb` and run the cells sequentially.

## 📁 Project Structure

```text
Google-Tech-Diversity-Analysis/
│
├── Diversity Analysis.ipynb
├── google_ethnicity.csv
└── README.md
```

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

- Data preprocessing and cleaning.
- Data normalization and encoding.
- Feature engineering and feature selection.
- Random Forest-based feature importance.
- Principal Component Analysis.
- Exploratory Data Analysis and visualization.
- Machine learning model development.
- Regression model evaluation.

## 👩‍💻 Author

**Bijin Biju**

BCA Student | Aspiring Data Analyst | AI & ML Enthusiast
