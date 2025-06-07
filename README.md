# Coffee Sales Excel Project

### Project Overview


This is an Excel dashboard I built to analyze coffee sales data across different countries, customers, and time periods. The goal was to practice cleaning data from multiple sheets, connecting them using lookup formulas, and visualizing business performance with PivotTables, slicers, and charts.






### Data Sources
- `Coffee Sales Project.xlsx` – contains three sheets: `Orders`, `Customers`, and `Products`, used to create the dashboard.
- Note: This is a simulated dataset used for academic and skill development purposes.
 

### Tools

- Excel - Data Cleaning, Analysis, Visuialization, and Reporting
- [Download here](https://lccuny-my.sharepoint.com/:x:/g/personal/ali_jabbi_lc_cuny_edu/EaOrhkt5S2lEiRSjQ64pNewBbFTCszjP7dur-7Vp6EEeQA?e=KbfGb1)

### Data Cleaning/Preparation

- Cleaned data by removing duplicates and checking for missing values
- Standardized column names and added a new column for detailed coffee type names
- Converted raw data into Excel Tables for easier filtering and referencing
- Linked the `Orders`, `Customers`, and `Products` sheets using:
  - `XLOOKUP` for customer and product info
  - `INDEX-MATCH` for alternative lookups and deeper practice








### Exploratory Data Analysis
- What are the total coffee sales over time?
- Who are our top 5 customers?
- How do sales break down by country?
- Which products are driving revenue?


### Data Analysis


Used Excel PivotTables and formulas to analyze key metrics:

- **Sales Over Time** – Line chart with a timeline slicer
- **Top 5 Customers** – Bar chart of highest revenue customers
- **Sales by Country** – Bar chart comparing total sales per region
- **Slicers** – Added interactive slicers for Product Type, Country, and Customer

#### Example Formulas Used:
- `=XLOOKUP(C2,customers!$A$1:$A$1001,customers!$G$1:$G$1001,,0)`
- `=INDEX(products!$A$1:$G$49,MATCH(orders!$D2,products!$A$1:$A$49,0),MATCH(orders!J$1,products!$A$1:$G$1,0))`





---

![Dashboard Screenshot](dashboard-screenshot.png)

---





### Results/Findings

- Total sales steadily increased year-over-year from 2019–2020 to 2022–2023  
- Each year had a different top-performing coffee type:
  - **2019–2020:** Excelsa led in sales  
  - **2020–2021:** Arabica became the top seller  
  - **2021–2022:** Arabica continued as the top-performing coffee  
  - **2022–2023:** Liberica took the lead  
- **Robusta consistently had the lowest sales** across all four years 






### 💡 Recommendations

📈 Prioritize Liberica — top seller in 2022–2023 with strong growth potential.

🔁 Continue supporting Arabica — best performer in 2020–2022 showing consistent demand.

📉 Reevaluate Robusta — consistently lowest sales; explore ways to boost interest or reduce inventory.

📊 Monitor sales trends regularly to stay aligned with customer preferences and update marketing and inventory strategies.





### Limitations

- Some missing values in the original dataset
- Data is fictional and meant for educational use only


