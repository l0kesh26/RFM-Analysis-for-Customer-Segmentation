# Customer Segmentation using RFM Analysis

## 📌 Overview
This project segments customers using **RFM (Recency, Frequency, Monetary)** analysis to help businesses target the right customers with the right marketing strategies.

## 📊 Dataset
- Source: [Kaggle – Online Retail Dataset](https://www.kaggle.com/datasets/vijayuv/onlineretail)
- Contains transaction data for an online store between 2010–2011.

## 🛠 Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

## 📈 Key Insights
- **Champions**: High-spending, frequent, recent buyers → Reward loyalty
- **At Risk**: Haven’t purchased recently but used to buy frequently → Re-engage with offers
- **Potential Loyalists**: Recent buyers but not yet frequent → Encourage repeat purchases

## 📂 Project Structure
RFM_Analysis_Project/
│
├── 📄 main.py                  # Main script to run the whole analysis
├── 📄 requirements.txt         # Python dependencies (pandas, seaborn, matplotlib, etc.)
├── 📄 README.md                # Project overview & instructions
│
├── 📂 data/
│   ├── raw_data.csv            # Original dataset
│   ├── cleaned_data.csv        # Cleaned dataset (optional)
│   └── rfm_results.csv         # RFM score results
│
├── 📂 notebooks/
│   ├── rfm_analysis.ipynb      # Jupyter notebook for analysis & testing
│   └── exploratory_data.ipynb  # Optional EDA notebook
│
├── 📂 scripts/
│   ├── data_preprocessing.py   # Data cleaning & transformation
│   ├── rfm_calculation.py      # RFM scoring functions
│   ├── segmentation.py         # Segment assignment logic
│   └── visualization.py        # All plots & charts
│
├── 📂 outputs/
│   ├── plots/                  # Saved PNG/JPG plots
│   │   ├── customer_segments.png
│   │   └── rfm_distribution.png
│   └── reports/                # PDF/HTML reports
│
└── 📂 utils/
    └── helpers.py              # Reusable helper functions
