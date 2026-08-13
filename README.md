# 🎯 Customer Segmentation using RFM Analysis — Project 1

A customer analytics project that segments customers based on their purchasing behavior using **RFM Analysis** (Recency, Frequency, Monetary), enabling targeted marketing strategies.

## 🎯 Objective
Analyze transactional customer data to segment customers into meaningful groups (e.g., loyal, churn risk, new) based on their purchase behavior, and provide targeted marketing recommendations for each segment.

## ✅ Project Tasks
- Clean and prepare transactional customer data
- Calculate RFM metrics (Recency, Frequency, Monetary)
- Segment customers into groups (loyal, churn risk, new, etc.)
- Analyze behavior patterns of each segment
- Provide targeted marketing recommendations
- Visualize segments using charts or dashboards

```

## 🛠️ Tools & Technologies
- **Python** (pandas, numpy, matplotlib, seaborn) — data cleaning & RFM computation
- **Jupyter Notebook** — analysis workflow
- **Power BI / Tableau** — segment visualization dashboard (optional)

## 🔍 Workflow
1. **Import Libraries & Load Raw Transaction Data**
2. **Data Cleaning** — remove duplicates/nulls, standardize customer IDs, fix invalid values
3. **Calculate RFM Metrics**
   - **Recency** — days since the customer's last purchase
   - **Frequency** — number of purchases in the period
   - **Monetary** — total amount spent
4. **Score & Segment Customers** — assign RFM scores (e.g., 1–5) and map to segments (Loyal, At Risk, New, Champions, Churned, etc.)
5. **Analyze Segment Behavior** — compare spend, frequency, and recency patterns across segments
6. **Marketing Recommendations** — targeted actions per segment (e.g., win-back offers for churn risk, loyalty rewards for champions)
7. **Visualization** — charts/dashboard showing segment sizes, revenue contribution, and behavior patterns

## 📈 Dashboard
Visual breakdown of customer segments, their share of revenue, and behavior patterns — built on top of the RFM-scored dataset.

## 🚀 How to Run
1. Clone the repo
   ```bash
   git clone https://github.com/<your-username>/customer-segmentation-rfm.git
   cd customer-segmentation-rfm
   ```
2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Open `notebooks/Project_1.ipynb` in Jupyter Notebook / JupyterLab and run the cells
4. (Optional) Open the dashboard file in Power BI Desktop / Tableau to explore the visuals

## 📌 Notes
- Update the raw data source path in the notebook if you re-run it with your own dataset.
- RFM scoring thresholds (quartiles/quintiles) can be adjusted in the notebook depending on your customer base size.
