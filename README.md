
![task4](https://github.com/user-attachments/assets/7337d078-7b8f-437f-b13e-f8984b0d45e0)

# ✨ Customer Trends and Insights Dashboard with Power BI | Infosys Springboard Task 4 




## Objective:
Build a Power BI dashboard to analyze customer behavior and trends based on sales data. Focus on creating meaningful visuals, applying drill-through functionality, and identifying patterns.

## Dataset Overview:
You will use a dataset containing the following columns:
- **Customer ID**
- **Customer Name**
- **Age Group**
- **Gender**
- **Region**
- **Product Category**
- **Sales Amount**
- **Profit**
- **Purchase Date**

## Instructions:

### 1. Data Import and Preparation
- Load the dataset into Power BI.
- Create a **calculated column** for **Customer Lifetime Value (CLV)** using the following formula:
- Ensure all columns have appropriate data types and formats (e.g., numerical values for Sales Amount and Profit, Date for Purchase Date, and text for Customer Name, Age Group, etc.).

### 2. Visualizations
Build the following visuals:

#### 2.1 Bar Chart:
- Create a **bar chart** showing the **total Sales Amount** by **Age Group** to analyze sales trends across different customer age groups.

#### 2.2 Stacked Column Chart:
- Create a **stacked column chart** showing **Sales Amount by Gender**, further split by **Product Category**, to explore how gender influences product preferences.

#### 2.3 Map Visual:
- Create a **map visual** to show **Sales Amount by Region**, providing geographic insights into where most sales are occurring.

#### 2.4 Scatter Chart:
- Create a **scatter chart** to show **Profit vs. Sales Amount** for each customer, with the **size of the bubble** representing the **Customer Lifetime Value (CLV)**. This will help identify high-value customers and their performance.

### 3. Drill-Through Functionality
- Create a **drill-through page** to allow in-depth analysis of individual customers:
- Include a **table** with the customer’s details:
  - **Customer Name**
  - **Region**
  - **Product Category**
  - **Sales Amount**
  - **Profit**
  - **CLV**
- Ensure that users can **right-click** on any visual to access the drill-through page for further details.

### 4. Filters and Slicers
Add the following filters and slicers to enhance the analysis:

#### 4.1 Region and Gender Slicers:
- Add **slicers** for **Region** and **Gender** to filter the data based on these attributes.

#### 4.2 Date Range Slicer:
- Add a **date range slicer** for **Purchase Date** to analyze customer behavior over a selected period.

### 5. Formatting and Customization
- Use a **consistent theme** across all visuals to maintain visual harmony.
- Add a **title** to your dashboard: `"Customer Trends and Insights Dashboard"`.
- Utilize **tooltips** to show additional information, such as CLV, when hovering over the visuals for detailed insights.

### 6. Insights
- Add a **text box** summarizing at least 3 key insights based on your analysis. Examples include:
- Which **age group** spends the most.
- **Regional trends** and where the highest sales occur.
- Identifying **high-value customers** with the highest CLV.

## Submission Guidelines:
- Save your Power BI file as `StudentName_CustomerTrends.pbix`.


