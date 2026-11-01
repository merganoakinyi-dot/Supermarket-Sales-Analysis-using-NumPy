Supermarket Sales Analysis with NumPy
Project Overview
This project uses Python and NumPy to analyze supermarket sales data from four departments over a seven-day period.

The analysis includes:

Sales aggregation
Statistical analysis
Sales classification
Data filtering
Revenue prediction
Array manipulation using NumPy
This project was created as part of my journey learning Python, NumPy, Data Analysis, and Machine Learning fundamentals.

Dataset
The dataset contains sales figures (KES) for four supermarket departments:

Food
Electronics
Clothes
Furniture
Sales are recorded for:

Monday
Tuesday
Wednesday
Thursday
Friday
Saturday
Sunday
Features
1. Sales Analysis
Total supermarket sales
Total sales per department
Total sales per day
Highest and lowest sales
2. Statistical Calculations
Mean
Median
Variance
Standard Deviation
3. Data Filtering
Display sales above a specified threshold
Identify high-performing sales
4. Sales Classification
Sales are categorized into:

Sales Amount	Classification
Above 15,000	Excellent
10,000 - 15,000	Good
7,000 - 9,999	Average
Below 7,000	Poor
5. Sales Prediction
A prediction function estimates future sales with a 5% growth rate.

def predict_next_day(avg_sales):
    return avg_sales * 1.05
Technologies Used
Python
NumPy
Visual Studio Code
Git
GitHub
Project Structure
SUPPRMARKET_DATA/
│
├── sales.py
├── README.md
Learning Outcomes
Through this project I learned:

Creating and manipulating NumPy arrays
Working with multidimensional arrays
Using NumPy statistical functions
Writing reusable Python functions
Applying conditional logic to business problems
Building simple prediction models
Organizing projects for GitHub
Sample Output
Total Sales: 265800

Highest Sale: 18000

Mean Sales:  9492.857142857143

Food -> Excellent
Electronics -> Good
Furniture -> Average
Future Improvements
Data visualization with Matplotlib
Dashboard creation with Plotly
Exporting results to Excel
Machine Learning sales forecasting
Interactive user input

Author
Megan

Aspiring Data Analyst | Learning Python, SQL, NumPy, Pandas, Excel, and Machine Learning.
