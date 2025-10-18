
# Data visualization and story telling

This repository is dedicated to exploring the data visualization and storytelling using powerful tools like Power BI and Tableau.

We’ll begin our journey with [Power BI](https://powerbi.microsoft.com/), diving deep into data modeling, DAX functions, dashboards, and reports.
Once we have mastered Power BI, we’ll move on to [Tableau](https://www.tableau.com/) to explore its capabilities in visual analytics and interactive storytelling.

The goal of this repository is to:

- Understand how to transform raw data into meaningful insights.  
- Learn the best practices for visual design and storytelling.  
- exploring features of Power Bi  and many more

---

# Introducation and Installation (Power Bi)

**Download Power BI Desktop**

Visit the official Microsoft Power BI page: https://powerbi.microsoft.com/desktop/

Click on Download Free or install it directly from the Microsoft Store.

**Installation**

Installation Steps : 

- Run the downloaded installer (PBIDesktopSetup.exe).

- Follow the on-screen instructions to complete the setup.

- Launch Power BI Desktop and sign in with your Microsoft account.


## Features of Power BI

- AI Powered tool. (we have sells data and we want to find the next month sells (prediction) using past data).
- real time analytics (changes based on input data).
- cloud integration (initially these reports in company server and we can publish it using cloud).

## Applications 

- visualization of data
- real time data analysis
- predictive analysis

## Components 

1. Power BI Desktop  => real time running application in our  machine.
2. Power BI Service => to share it other individuals / publish reports and it will be possible using this service.
3. Power BI Gateway => acts as a Bridge between power BI Service and On- premises data source.
4. Power BI Mobile => to look report good on large screen we can easily use it.
5. Power BI report server => if anyone don't want to place report on cloud they can place it on server(for security).

## Workflow of Power BI

1. Load the data.
2. transform the data
3. data modelling
4. creating report
5. Publish report

## 1. Load Data in Power BI

This section covers how to load data into Power BI Desktop.

### Steps:
1. Open **Power BI Desktop**.
2. Click on **Get Data** from the Home tab.
3. Select the data source (Excel, CSV, SQL Server, Web, etc.).
4. Browse and select your file or connect to the database.
5. Click **Load** to import the data into Power BI.

---

## 2. Transform Data in Power BI

After loading, the data may need cleaning and preparation.

### Steps:
1. Click **Transform Data** to open **Power Query Editor**.
2. Remove unnecessary columns and rows.
3. Rename columns for clarity.
4. Filter, sort, and clean data as required.
5. Apply changes and close the editor to update the dataset.

---

## 3. Data Modeling in Power BI

Data modeling helps establish relationships blw the Queries (Tables) and prepare data for reporting.

### Steps:
1. Identify tables and key columns.
2. Create relationships between tables (one-to-many, many-to-many).
3. Define hierarchies (e.g., Year → Month → Day).
4. Create calculated columns and measures using **DAX**.
5. Organize tables into **fact** and **dimension** tables.

---
## 4. Creating Reports in Power BI

This step is about building interactive dashboards.

### Steps:
1. Drag fields into the report canvas.
2. Choose visualizations (charts, tables, maps, etc.).
3. Apply filters and slicers for interactivity.
4. Format visuals for clarity and storytelling.
5. Save the report in Power BI Desktop.

---
## 5. Publish Reports in Power BI

Sharing your reports with stakeholders is the final step.

### Steps:
1. Sign in to **Power BI Service** (app.powerbi.com).
2. Click **Publish** in Power BI Desktop.
3. Choose the destination workspace.
4. Share dashboards with users or groups.
5. Set permissions and access levels as needed.

---
## Creating Our First Report

using sample data here we go with our first report you can also download it the link is given below.


### **Preview of the Report**

![First Power BI Report](Images/report1)  

> Screenshot of the report showing basic visualizations and layout.


### **Download Links**

- **Dataset:** [Download sample dataset](Datasets/covid)  
- **Power BI Report (.pbix):** [Download the report](Reports/report.pbix)  

