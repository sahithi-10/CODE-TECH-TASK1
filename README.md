# CODE-TECH-TASK1

Name: SAHITHI MOTUKURI

Company: CODETECH IT SOLUTIONS

ID: CT08DUD

Domain: POWER BI
Duration: Dec 2024-Jan 2025

Mentor : Nilla Santhosh

Sales-Dashboard

Problem Statement

This sales dashboard provides valuable insights into sales performance across various channels and product categories. However, it also highlights areas for improvement. For instance, the dashboard reveals a significant disparity between online and direct sales volumes, with online sales exceeding direct sales by 20%. Despite this higher volume, online sales appear less profitable.

Steps followed : 

Data Preparation

Step1 : Load Data: ->Open Power BI Desktop.
->In the "Home" tab, click "Get Data">"CSV".
->Navigate to your CSV file and select "Open".
->In the Navigator, select the table and click "Transform Data."

Data Cleaning & Transformation.

Step2 : Check Data Types:
->Ensure each column has the correct data type (e.g., Date, Number, Text).

Handle Missing Values:

Step 3: ->Identify rows with missing values (use the "Filter Rows" function).

Decide how to handle them:

Step 4: ->Remove rows with missing values.
->Replace missing values with an appropriate value (e.g., 0, average).
->Impute missing values using statistical methods.

Data Consistency:

Step 5:
->Check for and correct inconsistencies in data entry (e.g., variations in spelling, formatting).

Create Calculated Columns:

Step 6:

Calculate Total Sales:

      Total Sales = Quantity * Unit Price
Calculate Profit:
        Profit = Total Sales - Total Cost
      
Calculate Profit Margin:
        Profit Margin = Profit / Total Sales
Close & Apply:
     Once transformations are complete, click "Close & Apply" to load the data into Power BI.

Data Modeling

Create Relationships:

Step 7:
->If your data has multiple tables , establish relationships between them in the Data Model.

Dashboard Design

Add Pages:
Step 8:
->Create separate pages for different sections of your dashboard.

Add Visualizations:
Sales Overview:
Card Visuals:
  ->Total Sales
  ->Total Profit
  ->Total Orders
Bar Chart:
   ->Monthly Sales
   ->Sales by Sales Channel
Format Visuals:

->Adjust colors, fonts, and formatting for better readability and visual appeal.

->Add data labels and tooltips for additional context.

->Add Tooltips and Data Labels Provide additional context and information to the user.

Arrange Visuals:

->Arrange visualizations neatly and logically on the canvas.

->Add Page Titles and Descriptions Provide context and guidance for each page of the dashboard.

Publish and Share

->Publish to the Power BI service: Share your dashboard with colleagues, stakeholders, or customers.

->Embed in Reports and Websites: Embed the dashboard into reports or websites for easy access and integration.
