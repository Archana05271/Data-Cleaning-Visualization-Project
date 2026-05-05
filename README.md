 Data Cleaning & Visualization Project
 
Project Overview
This project focuses on cleaning and analyzing raw sales data to extract meaningful insights using Python. It demonstrates how data preprocessing and visualization help in understanding patterns and making better decisions.

 Objectives
- Handle missing values in the dataset
- Remove duplicate records
- Detect outliers in sales data
- Perform data preprocessing
- Visualize key insights using graphs

Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Seaborn  

Dataset
The dataset contains sales-related information with the following fields:
- Date
- Product
- Category
- Price
- Quantity
- Region

Dataset Characteristics:
- Includes missing values (Quantity column)
- Contains duplicate entries
- Covers multiple product categories and regions

Data Cleaning Process
- Missing values in the **Quantity** column were replaced using the median
- Duplicate rows were removed
- Date column was converted into datetime format
- A new column **Total Sales** was created:
  
  `Total = Price × Quantity`

Data Visualization
The following visualizations were created:

 **Category-wise Sales** (Bar Chart)  
 **Region-wise Sales** (Bar Chart)  
 **Sales Trend Over Time** (Line Graph)  
 **Outlier Detection** (Boxplot)  
 **Correlation Heatmap**

 Key Insights
- Electronics category contributes the highest revenue  
- Sales vary across different regions  
- Outliers exist in high-value transactions  
- Price strongly influences total sales  

 Project Structure
 - sales_data.csv
 - analysis.ipynb
 - README.md

Conclusion
This project highlights the importance of data cleaning and visualization in data analysis. By preprocessing raw data and applying visualization techniques, meaningful insights were extracted effectively.

 Outcome
- Learned data preprocessing techniques  
- Improved visualization skills  
- Gained experience in data storytelling  
