# Operational-Efficiency-Analysis-Root-Cause-Detection-Optimization

This project analyzes financial operations within an educational institution to detect hidden cost anomalies, identify underperforming units, and drive profit-oriented decision-making. The central focus is on detecting the **canteen** as a cost outlier and performing **Root Cause Analysis (RCA)** using Python to transition it from a **cost center to a profit center**.

> 🛑 Note: All data and organization identifiers have been anonymized for confidentiality.

---

## 🎯 Project Objective

- Perform exploratory financial analysis across departments.
- Detect anomalies and outliers in operational spending using data science methods.
- Pinpoint the **canteen** as a significant source of ongoing losses.
- Conduct Root Cause Analysis (RCA) to understand inefficiencies in canteen operations.
- Support transformation from cost center to profit center through corrective strategies.

---

## 🧪 Methodology

### 🔍 1. **Data Cleaning and Preparation**
- Converted date fields, handled missing values, and filtered department-wise transactions.
- Segregated non-operational expenses (e.g., scholarships, investments) to isolate departmental data.

### 📈 2. **Visualization & Outlier Detection**
- Generated department-wise **Total Expense** and **Income vs Expense** plots.
- Used **Seaborn bar charts** and **distribution plots** to visually highlight the canteen's negative margin trend.

### 🧾 3. **Root Cause Analysis (RCA)**
- Extracted line-item records from the canteen's purchase ledger.
- Calculated waste ratio, inventory mismatch, and income variance over time.
- Identified top-contributing causes: inconsistent pricing, oversupply, and underpricing on combo items.

### 💡 4. **Strategic Recommendations**
- Revised supplier contracts to improve unit economics.
- Suggested inventory-level monitoring with cost tracking.
- Introduced price calibration per item category to boost per-unit profitability.

---

## 📊 Sample Findings

| Department      | Net Profit | Expense Trend | Flagged Outlier |
|------------------|-------------|----------------|------------------|
| Science Dept.    | ✔️ Positive | Controlled     | No               |
| Library          | ✔️ Positive | Stable         | No               |
| **Canteen**      | ❌ Negative | Increasing     | **Yes** ✅        |

---

## 📂 Files Included

- `Sarath SIP.ipynb` – Jupyter notebook with full pipeline: data wrangling, visualization, and RCA.
- `canteen_analysis.csv` – Processed CSV (optional).
- `charts/` – PNGs of expense distribution and canteen-specific plots (optional).
- `README.md` – Project overview.

---

## 📚 Tools & Technologies

- **Python 3.9+**
- **Pandas**, **NumPy** – Data handling
- **Matplotlib**, **Seaborn** – Visualization
- **Jupyter Notebook** – Prototyping & output presentation

---

## 💼 Impact

- **Turnaround**: Converted a 5-figure annual canteen loss into a break-even point within 1 quarter.
- **Scalability**: Framework repeatable for analyzing other internal departments.
- **Culture Shift**: Fostered a data-driven approach to operational management.

---

## 📬 Contact

Created by **Sarath Sabu**  
🎓 Graduate Student, M.S. in Decision Analytics, VCU  
📧 ss6@vcu.edu  
🔗 [LinkedIn](https://www.linkedin.com/in/sar-ath-s/)

---

## 📝 Disclaimer

This project is based on real-world consulting experience. All institution names, employee details, and transactional data have been anonymized to respect privacy and confidentiality agreements.
