# Retail Sales Data Analysis with Excel

## Project Overview
This project showcases my learning journey in Microsoft Excel through the analysis of a retail sales dataset containing 1,000 customer transactions.

The project focused on transforming raw sales data into meaningful insights using Power Query, Pivot Tables, Pivot Charts, and Excel data analysis techniques.

## Dataset Information

The dataset contains:

- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Sales

I also created an additional field called **Age Group** to categorise customers as:

- Junior
- Adult
- Senior

based on customer age. 

## Skills Demonstrated

### Cell Referencing

Developed a strong understanding of Excel cell referencing techniques and their importance in building accurate and dynamic spreadsheets.

#### Relative Cell Referencing
Used relative references to create formulas that automatically adjust when copied across rows and columns.

Example:
=B2*C2

This enabled efficient calculations across large datasets without manually editing formulas.

#### Absolute Cell Referencing
Used absolute references to lock specific cells within formulas when copying calculations.

Example:
=B2*$G$2

This ensured that fixed values such as tax rates, percentages, or constant values remained unchanged across calculations.

#### Mixed Cell Referencing
Applied mixed references to lock either a row or a column while allowing the other to change.

Examples:
=$B2=B$2

This technique was useful when creating structured calculation tables and repeating formulas across multiple rows and columns.

#### Key Learning Outcomes
- Understood the differences between relative, absolute, and mixed references.
- Applied the appropriate reference type based on calculation requirements.
- Improved formula accuracy and consistency.
- Increased efficiency when working with large datasets.
- Developed the ability to create scalable and reusable spreadsheet models.
### Power Query

Used Power Query to automate the process of importing, cleaning, and transforming retail sales data before analysis.

#### Data Import and Preparation
- Imported the retail sales dataset into Power Query.
- Reviewed the dataset structure and identified key fields including Transaction ID, Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit, and Total Sales.
- Ensured data was organised in a tabular format suitable for analysis.

#### Data Transformation
- Changed column data types to ensure consistency and accuracy.
- Validated numerical and date fields.
- Renamed and managed columns where necessary.
- Structured the dataset for reporting and analysis.

#### Creating an Age Group Column
Created a custom column called **Age Group** to segment customers into:
- Junior
- Adult
- Senior

This helped make customer analysis more meaningful and allowed sales performance to be examined across different age demographics.

#### Benefits Gained
- Improved data quality and consistency.
- Reduced manual data preparation.
- Created a repeatable data transformation process.
- Prepared the dataset for Pivot Table analysis and reporting.


### Pivot Tables

Used Pivot Tables to summarise, organise, and analyse large volumes of retail sales data.

#### Sales Analysis by Product Category
Created Pivot Tables to compare total sales across product categories:

- Electronics (£156,905)
- Clothing (£155,580)
- Beauty (£143,515)

This helped identify the highest-performing category and compare category performance. 【1-ca6690】

#### Customer Demographic Analysis
Used Pivot Tables to analyse sales by:

- Age Group
- Gender
- Product Category

This enabled deeper insights into customer purchasing behaviour and spending patterns.

#### Sales Performance Analysis
Used Pivot Tables to:

- Calculate total sales.
- Compare category performance.
- Summarise customer transactions.
- Identify trends and patterns within the dataset.
- Generate business insights from raw data.

#### Skills Developed
- Grouping and summarising data.
- Creating calculated summaries.
- Organising large datasets into meaningful reports.
- Analysing business performance metrics.
- Extracting insights from transactional data.

### Pivot Charts

Used Pivot Charts to transform Pivot Table outputs into visual reports and dashboards.

#### Data Visualisation
Created charts to visualise:

- Product category sales performance.
- Customer demographic trends.
- Sales distribution across categories.
- Comparative sales performance.

#### Reporting and Presentation
Used Pivot Charts to:

- Present findings clearly and professionally.
- Simplify complex datasets.
- Highlight key trends and patterns.
- Support data-driven decision-making.

#### Business Insights
Pivot Charts made it easier to:

- Identify top-performing product categories.
- Compare sales results visually.
- Spot patterns that may not be immediately obvious in tabular data.
- Communicate analytical findings effectively to stakeholders.

#### Skills Developed
- Chart creation and formatting.
- Data storytelling.
- Dashboard reporting.
- Trend analysis.
- Visual communication of business insights.

## Reflection
Completing this project helped me move beyond basic Excel usage and develop practical data analysis skills. I gained hands-on experience using Power Query and Pivot Tables to transform raw retail sales data into meaningful insights and professional reports.
