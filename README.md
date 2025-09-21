# 📊 CRM-Sales-Analysis

## 🚀 Project Overview
This project delivers a comprehensive analysis of a CRM sales pipeline using SQL and Python. The objective is to uncover patterns in sales performance, evaluate product success, and monitor quarterly revenue growth.

Through ranking, win-rate analysis, and revenue breakdowns, the project highlights which managers and products drive results and identifies areas for improvement. This showcases how structured analytics can transform raw sales data into actionable business insights.

## 🛠️ Tools & Technologies
- **SQL (SQLite):** Data extraction and transformation
- **Python (Pandas, Matplotlib, Seaborn):** Analysis & visualization
- **Jupyter Notebook:** Workflow and documentation

## 📊 Analysis Components
- **Summary statistics & visualizations:** Overall sales performance distribution
- **Team & agent-level comparisons:** Ranking by revenue, win rate, and deal size
- **Quarterly revenue trends:** Quarter-on-quarter growth & performance dips
- **Product win rates:** Evaluation of product effectiveness in the pipeline
- **SQL queries + Python visualizations:** Seamless integration of data analysis

## 🔑 Key Insights
- **Quarterly revenue growth:** Identified surges followed by declines, pointing to pipeline consistency issues.
- **Team/agent performance:** Contrasts between high-revenue agents and those with higher efficiency (win rate/avg deal size).
- **Product performance:** Some products drive higher success rates, while others underperform.
- **Operational balance:** High revenue does not always align with strong win rates, highlighting the trade-off between deal quantity vs. quality.

## 📌 Recommendations
- Strengthen pipeline stability to sustain growth beyond high-performing quarters.
- Provide targeted training to balance efficiency and revenue among agents.
- Reevaluate low-performing products (pricing, positioning, or training focus).
- Share best practices from top performers across teams.

## 📁 Project Structure
```
CRM-Sales-Analysis/
│
├── data/
│   ├── accounts.csv
│   ├── products.csv
│   ├── sales_pipeline.csv
│   └── sales_teams.csv
├── notebooks/
│   ├── 01_crm_first_stage.ipynb
│   └── 02_crm_analysis.ipynb
└── README.md
```

## 🎯 Conclusion
Combining SQL queries with Python analytics enables deeper visibility into sales performance. By tracking revenue growth, agent productivity, and product success rates, businesses can focus on scalable growth strategies and smarter decision-making.

## ⚡ How to Run

1. **Clone the repo:**
    ```bash
    git clone https://github.com/amrinderk1593/CRM-Sales-Analysis.git
    cd CRM-Sales-Analysis
    ```

2. **Install requirements:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the notebooks in order:**
    ```bash
    jupyter lab notebooks/01_crm_first_stage.ipynb
    jupyter lab notebooks/02_crm_analysis.ipynb
    ```

---

