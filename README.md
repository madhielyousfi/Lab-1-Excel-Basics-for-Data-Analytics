# Lab 1: Excel Basics for Data Analytics

### **Scenario:**

You are a junior data analyst at a retail company, and you are given a dataset containing sales data for the last quarter. Your task is to clean the data, perform some basic analysis, and present your findings to your manager using Excel. The data includes information about sales regions, product categories, sales amounts, and dates.

Your goal for this lab is to familiarize yourself with the fundamental operations in Excel, including data entry, formulas, sorting, filtering, and basic data analysis.

---

### **Steps for Lab 1:**

### **Step 1: Understanding the Dataset**

- Download or create a simple Excel dataset with columns such as:
    - **Date**: The date of the sale.
    - **Region**: The region where the sale occurred (e.g., East, West, North, South).
    - **Product**: The product category (e.g., Electronics, Furniture, Clothing).
    - **Sales Amount**: The amount of the sale.

For this lab, you can create a small dataset manually in Excel to simulate the sales data. Here’s an example of a few rows you could create:

| Date | Region | Product | Sales Amount |
| --- | --- | --- | --- |
| 2024-01-15 | East | Electronics | 150 |
| 2024-01-16 | West | Furniture | 200 |
| 2024-01-17 | North | Clothing | 100 |
| 2024-01-18 | South | Electronics | 300 |

### **Step 2: Entering and Formatting Data**

- Open Excel and create a new worksheet.
- Manually enter the sales data as shown above.
- **Format the cells** appropriately:
    - Dates should be formatted as **Date**.
    - Sales Amount should be formatted as **Currency** or **Number** with 2 decimal places.
- **Bold the headers** (Date, Region, Product, Sales Amount) to make them stand out.

### **Step 3: Using Basic Formulas**

Learn and apply basic Excel formulas to calculate summary statistics and other key metrics:

1. **Sum the Sales Amount**:
    - Click in a blank cell (e.g., E2) and use the `SUM` formula to calculate the total sales:
        
        ```
        =SUM(D2:D5)
        
        ```
        
    - This will give you the total sales for the dataset.
2. **Average Sales**:
    - Calculate the average sales amount by using the `AVERAGE` function:
        
        ```
        =AVERAGE(D2:D5)
        
        ```
        
    - This will give you the average sales amount per transaction.
3. **Maximum and Minimum Sales**:
    - Use the `MAX` and `MIN` functions to find the highest and lowest sales amounts:
        
        ```
        =MAX(D2:D5)
        =MIN(D2:D5)
        
        ```
        

### **Step 4: Sorting and Filtering Data**

1. **Sorting Data**:
    - Select the entire dataset.
    - Go to the **Data** tab and click on **Sort**.
    - Sort the data by **Sales Amount** from largest to smallest.
2. **Filtering Data**:
    - Select the header row.
    - Go to the **Data** tab and click on **Filter**.
    - Use the filter to only show rows where the **Region** is "East". This allows you to focus on a specific segment of your dataset.

### **Step 5: Data Cleaning**

In real-world scenarios, datasets often contain inconsistencies, missing values, or incorrect data. Learn to spot and fix these issues:

- Check for missing data:
    - If any cell under **Sales Amount** is blank, fill it in with `0` or use a placeholder such as "N/A".
- Correct spelling mistakes:
    - If the **Region** column has inconsistent data (e.g., "Nort" instead of "North"), correct it.

### **Step 6: Create Basic Charts**

1. **Bar Chart of Sales by Region**:
    - Highlight the data in the **Region** and **Sales Amount** columns.
    - Go to the **Insert** tab and choose **Bar Chart**.
    - Excel will create a simple bar chart showing the sales for each region.
2. **Line Chart for Sales over Time**:
    - Highlight the data in the **Date** and **Sales Amount** columns.
    - Insert a **Line Chart** to visualize how sales have changed over time.

### **Step 7: Conditional Formatting**

- Highlight the **Sales Amount** column and use **Conditional Formatting** to color-code the sales:
    - Use a rule to highlight values greater than 200 in green and values less than 150 in red.

### **Step 8: Save and Share**

- After completing the tasks, save the Excel file as **Sales_Analysis_Lab1.xlsx**.
- You can share this file with your manager or team to showcase your ability to clean, manipulate, and analyze data using basic Excel skills.

---

### **Expected Output:**

By the end of Lab 1, you should be comfortable with:

- Basic data entry and formatting in Excel.
- Using simple formulas like SUM, AVERAGE, MAX, and MIN.
- Sorting and filtering data for quick analysis.
- Creating basic visualizations like bar charts and line charts.
- Applying conditional formatting for better data visualization.

This first lab lays the groundwork for more advanced Excel skills and prepares you for future labs that build on these foundational concepts.