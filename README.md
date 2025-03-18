# Customer Segmentation using Classification

## Project By : Kevin Marakana

### Project Overview
In this practical, we will predict customer segments (A, B, C, or D) for potential new customers using machine learning classification models. An automobile company plans to expand into new markets with their existing products (P1-P5), and wants to classify 2,627 new potential customers into segments based on demographic and behavioral attributes.

## Dataset Information
The dataset contains various customer attributes:

| Variable | Definition |
|----------|------------|
| ID | Unique ID of the customer |
| Gender | Gender of the customer |
| Ever_Married | Marital status of the customer |
| Age | Age of the customer |
| Graduated | Whether the customer is a graduate |
| Profession | Profession of the customer |
| Work_Experience | Work experience in years |
| Spending_Score | Spending score of the customer |
| Family_Size | Number of family members (including customer) |
| Var_1 | Anonymized category of the customer |
| Segmentation | Target Variable - Customer segment (A, B, C, or D) |

## Project Tasks

| Task | Description |
|------|-------------|
| 1. Data Exploration | • Load the dataset and display basic statistics<br>• Identify the number of records, missing values, and data types<br>• Visualize class distribution of Segmentation |
| 2. Handling Missing Values | • Identify missing values and impute or drop them as required<br>• Use appropriate strategies such as mean/median for numerical data and mode for categorical data |
| 3. Exploratory Data Analysis | Perform at least 5 analyses:<br>• Univariate Analysis (Distribution plots for numerical features)<br>• Bivariate Analysis (Comparison between variables)<br>• Correlation Heatmap<br>• Bar plot for categorical variables<br>• Outlier detection using box plots |
| 4. Model Building | • Convert categorical variables into numerical representations<br>• Perform train-test split (e.g., 80-20 split)<br>• Train at least four classification models:<br>&nbsp;&nbsp;1. Logistic Regression<br>&nbsp;&nbsp;2. Random Forest Classifier<br>&nbsp;&nbsp;3. Support Vector Machine (SVM)<br>&nbsp;&nbsp;4. XGBoost |
| 5. Model Evaluation | Compare models using performance metrics:<br>• Accuracy<br>• Precision, Recall, and F1-Score<br>• Confusion Matrix |
| 6. Model Saving | • Save the best-performing model |
| 7. Prediction | • Load the saved model and make predictions on the new dataset<br>• Display the predicted segments for new customers |

Let's begin our analysis!
