# Supermarket Sales Analysis using Data Analytics and AI

**Student:** Fiza Khan  
**Program:** AICTE | IBM SkillsBuild Data Analytics with AI Internship

## Project overview
This project uses Python to inspect supermarket transaction data, calculate sales KPIs, compare product lines/branches/payment methods, visualize sales patterns, and demonstrate a Random Forest regression model for customer-rating estimation.

## Dataset
- Dataset page: https://github.com/selva86/datasets/blob/master/supermarket_sales.csv
- Direct CSV: https://raw.githubusercontent.com/selva86/datasets/master/supermarket_sales.csv

The notebook attempts to load the public CSV. If it cannot access the internet, it generates clearly labelled synthetic demonstration data. If synthetic data is used, do not present its outputs as real-world findings.

## Files
- `FizaKhan_SupermarketSalesAnalysis.ipynb` — code and analysis notebook
- `requirements.txt` — Python dependencies
- `FizaKhan_ProjectReport.docx` — project documentation
- `README.md` — setup and project overview

## Technologies
Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, and Scikit-learn.

## Run the project
1. Install Python 3.10 or newer.
2. Download/clone this repository.
3. Open a terminal in the project folder.
4. Install packages: `pip install -r requirements.txt`
5. Start Jupyter: `jupyter notebook`
6. Open `FizaKhan_SupermarketSalesAnalysis.ipynb`.
7. Select **Kernel → Restart & Run All** and confirm all cells run. If using the public CSV, internet access is required.

## Analysis steps
1. Load dataset and inspect columns.
2. Check missing values and duplicates.
3. Calculate revenue, gross income, transaction count, average bill, and units sold.
4. Compare sales by product line, branch, customer type, payment method, hour, and month.
5. Train a basic model to estimate customer ratings and calculate MAE, RMSE, and R².
6. Interpret results cautiously and describe limitations.

## Limitations
The dataset is a sample and may not represent all supermarkets. The model is educational and should not be used for business decisions without validation. Do not claim that the internship provider has approved the project unless it confirms this.

## Author
Fiza Khan
