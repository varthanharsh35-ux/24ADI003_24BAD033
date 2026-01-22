# 24ADI003_24BAD033
EXPERIMENT 1
Introduction to Python Libraries and Dataset Preprocessing

DATASETS USED : 

SCENARIO 1: E-commerce Sales Data
The first code snippet works with an e-commerce sales dataset, which contains details about products sold, quantity purchased, and unit price. The dataset is loaded using the pandas library, and basic exploratory operations like viewing the first few rows, last rows, structure, statistical summary, and missing values are performed. After identifying missing values, the code removes them to clean the dataset. A new column called Sales is created by multiplying Quantity and UnitPrice. Then, the total sales for each product are calculated using groupby. Finally, the sales data is visualized using a bar chart and a line chart with matplotlib to understand product-wise sales distribution and trends.
Dataset (Kaggle – Public): https://www.kaggle.com/datasets/carrie1/ecommerce-data

SCENARIO 2: Hospital Patient Records
The second code snippet handles a medical dataset related to diabetes prediction, specifically the Pima Indians Diabetes dataset. This dataset includes health-related attributes such as glucose level, blood pressure, insulin, BMI, and age. The code loads the dataset and performs basic data inspection like viewing rows, checking data types, and identifying missing values. Since zero values in some medical columns are invalid, they are replaced with missing values. Histograms are plotted to visualize the distribution of glucose levels and age. Box plots are also used to identify outliers and understand the spread of glucose and age values in the dataset.
Dataset (Kaggle – Public): https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

SCENARIO 3: Housing Dataset
The third code snippet works with a housing price dataset, which contains information about house features such as area, number of bedrooms, and price. After loading the dataset, the code checks column names, data types, and missing values. Scatter plots are created to analyze the relationship between area and price, and bedrooms and price. The correlation between numerical variables is calculated, and a heatmap is generated using seaborn to visually represent the strength of relationships between different features in the dataset.
Dataset (Kaggle – Public): https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction

SCENARIO 4: Banking Customer Data
The fourth code snippet analyzes a customer personality and marketing dataset, which contains demographic and spending information of customers. The dataset is loaded using tab separation, and initial exploration is done by checking rows, columns, data types, and missing values. Missing records are removed for clean analysis. A new column called Age is calculated using the year of birth. A bar chart is used to show the age distribution of customers. Box plots are created to visualize income distribution and customer spending patterns. Total customer spending is calculated by summing spending across multiple product categories, and a box plot is used to understand overall spending behavior.
Dataset (Kaggle – Public): https://www.kaggle.com/datasets/ajay1735/customer-personality-analysis

