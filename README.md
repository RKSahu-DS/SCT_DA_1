# SCT_DA_1
# SkillCraft Technology - Data Analytics Internship
## Task 01: Excel Sales Dashboard 📊
<img width="1366" height="727" alt="image" src="https://github.com/user-attachments/assets/d019da54-db6a-4473-ad52-09fb786ee42e" />


**Repository:** `SCT_DA_1`

### 📝 Project Objective
The goal of this project is to use Microsoft Excel to clean, analyze, and visualize a provided dataset (Superstore Sales Data). The core objective is to create an interactive dashboard using Pivot Tables and Charts to visualize **Total Sales, Profit by Category, and Sales Trends over time**, while utilizing **Conditional Formatting** to highlight high and low performers.

### 🛠️ Tools & Approach
* **Tool Used:** Microsoft Excel 2013
* **Structure:** A professional 4-sheet architecture was implemented to ensure data integrity and clean backend processing:
  1. **Raw Data:** The original, untouched dataset.
  2. **Helper Data:** Working sheet where new calculations and transformations were made.
  3. **Summary:** Backend engine containing all Pivot Tables.
  4. **Dashboard:** The final interactive frontend visual interface.

### 💡 Key Highlights & Problem Solving
* **Missing Data Handling:** The original dataset lacked a 'Profit' column. To fulfill the task objectives, I engineered a new `Estimated Profit` column in the Helper Data sheet using nested `IF` formulas, assuming realistic category-wise profit margins:
  * *Technology:* 25% Margin
  * *Office Supplies:* 15% Margin
  * *Furniture:* 10% Margin
* **KPI Setup:** Created quick summary cards for Total Sales ($2.26M), Total Orders, and YoY Growth.
* **Trend Analysis:** Mapped out overall sales trends over the years (2015-2018) to identify seasonality and growth.
* **Conditional Formatting:** Ranked Sub-Categories by Sales and applied conditional formatting to visually distinguish the top-performing and low-performing products.
* **Interactivity:** Integrated Slicers mapped to all Pivot Charts to allow dynamic, one-click filtering across the entire dashboard.

### 📂 How to View
To interact with the dashboard, download the `Superstore Sales Dataset (Recovered).xlsx` file from this repository and open it in Microsoft Excel.
