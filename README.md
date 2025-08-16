This project involves performing data cleaning and exploratory data analysis (EDA) on the Titanic dataset from Kaggle. The primary goal is to understand the structure of the dataset, handle missing or inconsistent data, and explore patterns related to passenger survival.

The Titanic dataset contains demographic and travel information about passengers, such as age, gender, passenger class, and whether they survived. By cleaning the data and analyzing key variables, we uncover insights into which factors may have influenced survival during the Titanic disaster.

🔍 Key Steps: Data Loading Load the Titanic dataset using pandas and inspect the first few rows.

Data Cleaning

Handle missing values (e.g., filling missing ages with the median).

Drop columns with too many missing or irrelevant values (like Cabin and Ticket).

Encode categorical features for further analysis.

Exploratory Data Analysis (EDA)

Univariate analysis (distribution of gender, survival, passenger class).

Bivariate analysis (survival by gender, age, class, and embarkation port).

Visualizations using seaborn and matplotlib (bar charts, histograms, heatmaps).

Correlation analysis to find relationships between numerical features.

Insights Derived

Higher survival rate among females and first-class passengers.

Younger passengers had better survival rates.

Port of embarkation and fare had a noticeable impact on survival.

📊 Tools Used: Python

Pandas

NumPy

Seaborn

Matplotlib

🎯 Outcome: This project builds a strong foundation in real-world data preprocessing and analysis. It highlights how to clean and explore data effectively before applying machine learning models in future steps.
