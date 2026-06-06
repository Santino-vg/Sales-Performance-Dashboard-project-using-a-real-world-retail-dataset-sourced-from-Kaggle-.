💡 Data without structure is just noise.

I took a Kaggle dataset, cleaned every flaw, and built a dashboard that speaks for itself. Here's the breakdown 👇
The Project:

I recently worked on a Sales Performance Dashboard project using a real-world retail dataset sourced from Kaggle — specifically to sharpen my data analytics skills and push my Excel expertise further.
The dataset contained 9,994 customer records across multiple U.S. regions, covering sales, profit, shipping modes, product categories, and more.

What I Found in the Raw Data (Problems Identified):

The raw dataset had several issues that needed fixing before any analysis could begin:

❌ Inconsistent text formatting (mixed cases like "united states" vs "United States", "SOUTH" vs "South")

❌ Numbers stored as fractions or corrupted values (e.g., "957 4/7", "######" overflow errors)

❌ Extra blank rows scattered throughout the dataset

❌ Truncated column widths hiding actual data

❌ Discount values stored as decimals without consistent formatting

❌ Missing "Customer" ID column present in the cleaned version

What I Did — Step by Step:

🔹 Data Cleaning:
Removed all extra blank rows and whitespace using TRIM() and PROPER() functions
Standardized all text fields (Country, Region, Category, Sub-Category) to consistent formatting
Fixed number formatting — converted fractional/corrupt values to proper decimals
Removed duplicate entries

Applied CLEAN() and text normalization formulas across key columns
Ensured all columns were properly formatted (currency, percentage, number)

🔹 Pivot Table Analysis:
After cleaning, I selected the entire dataset and built multiple Pivot Tables on a dedicated sheet to prepare for the dashboard.

🔹 Dashboard Built (from the visuals):

The final dashboard includes:
 
📊 KPI Cards — Total Customers (9,994), Total Sales (2.3M), Total Cost (2.0M), Total Profit (286.4K)

🏆 Top 3 Sub-Categories bar chart — Phones ($330K), Chairs ($328.4K), Storage ($223.8K)

📈 Sales & Profit Margin by Ship Mode — combo line + bar chart

🥧 Sales by Region pie chart — West 32%, East 29%, Central 22%, South 17%

🥧 Profit by Region pie chart

📊 Top 10 Cities by Total Sales bar chart

🎛️ Interactive Slicers — Region, State, and City filters for dynamic analysis

Skills Used (Microsoft Excel — 100%):

Pivot Tables | Pivot Charts | Slicers | TRIM() | PROPER() | CLEAN() | Data Validation | Conditional Formatting | Number Formatting | Duplicate Removal | Dashboard Design | Data Cleaning | KPI Cards

Result & Value:

This project allowed me to simulate a real-world data analyst workflow — from messy raw data to a decision-ready dashboard. Any business could use a dashboard like this to instantly track regional performance, identify top-selling products, and optimize shipping strategies.
