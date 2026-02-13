PROJECT TITLE
- Diwali Sales Data Analysis

PROJECT OVERVIEW
- This project is an Exploratory Data Analysis (EDA) of sales data during the Diwali festival period. The analysis aims to uncover consumer buying patterns and identify key demographics that drive sales. By examining variables such as gender, age, occupation, and state, the project provides actionable insights to improve marketing strategies and inventory planning for future festive seasons.

DATASET DESCRIPTION
The dataset ("Diwali Sales Data.csv") contains 11,251 records of customer transactions with the following key columns:
1. User_ID: Unique identifier for each customer.
2. Cust_name: Name of the customer.
3. Product_ID: Unique identifier for the product sold.
4. Gender: Gender of the customer (M/F).
5. Age Group: Categorical age bracket of the customer.
6. Age: Numerical age of the customer.
7. Marital_Status: Marital status of the customer (0 for Single, 1 for Married).
8. State: The state where the customer resides.
9. Zone: Geographical zone (e.g., Western, Southern).
10. Occupation: The customer's profession.
11. Product_Category: Category of the product purchased (e.g., Auto, Clothing).
12. Orders: Number of orders placed by the customer.
13. Amount: Total transaction amount.

OBJECTIVES OF THE PROJECT
- To clean and preprocess the raw sales data for analysis.
- To perform exploratory data analysis (EDA) to understand the distribution of sales across different demographics.
- To identify the target audience (Gender, Age Group, Marital Status) that contributes most to revenue.
- To determine which states and zones have the highest purchasing power.
- To analyze product preferences based on occupation and product categories.

STEPS PERFORMED
1. Data Loading: Imported the CSV dataset using Pandas and inspected the dataframe structure.
2. Data Cleaning:
   - Dropped unrelated and empty columns ('Status', 'unnamed1').
   - Handled missing values by dropping null rows.
   - Converted the 'Amount' column to integer type for accurate calculations.
   - Renamed columns for better readability (e.g., 'Marital_Status' to 'Marriage').
3. Exploratory Data Analysis (EDA):
   - Analyzed gender distribution and total sales amount by gender.
   - Examined the relationship between age groups and purchasing behavior.
   - Investigated the impact of marital status on sales.
   - Explored occupation-wise and state-wise sales trends.
4. Data Visualization:
   - Used Seaborn and Matplotlib to create count plots and bar charts.
   - Visualized the top 10 states by orders and amount.
   - Plotted sales distribution across different product categories.
5. Insight Generation: derived conclusions about the most profitable customer segments and product categories.

TOOLS AND LIBRARIES USED
- Python
- Pandas (for data manipulation and cleaning)
- NumPy (for numerical operations)
- Matplotlib (for static plotting)
- Seaborn (for advanced statistical visualizations)
- Jupyter Notebook

FILES INCLUDED
- Diwali.ipynb: The Jupyter Notebook containing all the code and visualizations.
- Diwali Sales Data.csv: The dataset used for the analysis.

HOW TO RUN THE PROJECT
1. Install the required libraries:
   pip install pandas numpy matplotlib seaborn
2. Download "Diwali.ipynb" and "Diwali Sales Data.csv" to the same directory.
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Run the cells sequentially to perform the analysis and generate the plots.

KEY INSIGHTS
- Target Demographics: Female customers in the age group of 26-35 years are the highest contributors to sales.
- Top Performing States: Uttar Pradesh, Maharashtra, and Karnataka generate the most orders and revenue.
- Profitable Categories: The "Food", "Clothing", and "Electronics" categories see the highest demand.
- Occupation Impact: Individuals working in the IT Sector, Healthcare, and Aviation industries are the top spenders.
- Marital Status: Married women show a higher purchasing trend compared to other groups.

CONCLUSION
- The analysis reveals that the primary target audience for Diwali sales is married women aged 26-35 years, particularly from Uttar Pradesh, Maharashtra, and Karnataka, who work in the IT, Healthcare, and Aviation sectors. Businesses should focus their marketing efforts and inventory stocking on Food, Clothing, and Electronics categories to maximize revenue in future sales events.

AUTHOR
- Rishan Menezes
