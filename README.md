# 📊 Customer Behavior Analysis

## 📌 Overview
This project explores customer shopping behavior using Python, SQL, and Power BI. It demonstrates an end-to-end data analytics workflow — from data cleaning and feature engineering to SQL querying and dashboard creation. The goal is to uncover actionable insights and present them through interactive visuals and a formal report.

## 📁 Dataset
- **File**: `customer_shopping_behavior.csv`  
- **Size**: ~3,900 customer records  
- **Description**: Includes customer demographics, purchase patterns, product preferences, and transaction details  
- **Note**: Column headers were cleaned and standardized during preprocessing

## 🛠️ Tools & Technologies
| Tool | Purpose |
|------|--------|
| Python (Pandas, SQLAlchemy) | Data loading, cleaning, feature engineering |
| PostgreSQL / MySQL / SQL Server | SQL querying and data storage |
| Power BI | Dashboard creation and visualization |
| Jupyter Notebook | Development and documentation |
| PDF Report | Summary of insights and recommendations |

## 🔍 Workflow Summary
1. **Data Preparation**
   - Loaded and inspected the dataset
   - Cleaned duplicated headers and missing values
   - Standardized column names
   - Created new features: `age_group`, `purchase_frequency_days`

2. **SQL Integration**
   - Loaded cleaned data into PostgreSQL, MySQL, and SQL Server
   - Executed queries for customer segmentation, purchase trends, and product performance

3. **Dashboard Creation**
   - Connected Power BI to SQL database
   - Built visuals: KPIs, charts, filters
   - Saved as `customer_behavior_dashboard.pbix`

4. **Reporting**
   - Summarized findings in `Customer_Shopping_Behavior_Analysis.pdf`
   - Included business insights and recommendations

## 📈 Dashboard Highlights
- Customer segmentation by age and location  
- Purchase frequency and value distribution  
- Product category performance  
- Seasonal shopping trends  
- Interactive filters for dynamic exploration

> 📎 Open `customer_behavior_dashboard.pbix` in Power BI Desktop to explore.

## ✅ Key Outcomes
- Cleaned and structured raw customer data  
- Engineered meaningful features for analysis  
- Demonstrated SQL integration across multiple platforms  
- Delivered a professional dashboard and report

## ▶️ How to Run
1. **Clone the repository**
   ```bash
   git clone https://github.com/kidnan/customer_behavior_analysis.git
   cd customer_behavior_analysis
   ```

2. **Install dependencies**
   ```bash
   pip install pandas sqlalchemy psycopg2-binary pymysql pyodbc
   ```

3. **Run the notebook**
   Open `Customer_Shopping_Behavior_Analysis.ipynb` in Jupyter and run all cells.

4. **Set up SQL database**
   - Choose PostgreSQL, MySQL, or SQL Server
   - Update credentials in the notebook
   - Run the SQL cells to load data

5. **Open Power BI Dashboard**
   - Launch `customer_behavior_dashboard.pbix` in Power BI Desktop
   - Update data source credentials if needed

6. **Review the Report**
   - Open `Customer_Shopping_Behavior_Analysis.pdf` for a summary of findings
