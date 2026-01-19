# 🛒 Black Friday Sales Analysis

Business proposal + production-style data pipeline (550k rows cleaned) with EDA and modelling roadmap.

## 🎯 Business Objective
Maximise Black Friday profit by identifying high-value customers for targeted promotions based on spending behaviour and customer demographics.

See [🛒 proposal PDF](./Black_Friday_Proposal.pdf) for full business context.

## 📊 Dataset
- 550,068 Black Friday transactions
- Customer demographics, product categories, and purchase amounts
- Data challenge: ~58% missing secondary product categories

## 🛠️ Data Pipeline (Complete)
✅ Loaded and validated 550k rows  
✅ Standardised columns to snake_case  
✅ Optimised categorical dtypes for memory efficiency  
✅ Imputed product_cat_2/3 as `"Unknown"` to preserve all records  
✅ Verified no nulls or duplicates post-cleaning  

## 🔮 Next (Work in Progress)
- **EDA**: Purchase distributions, demographic trends, customer segments  
- **Feature engineering**: Age encoding, category transformations  
- **Modelling**: Predict customer purchase value using XGBoost (RMSE)

**Tech stack**: Python, Pandas  
*(Planned: Plotly, XGBoost)*

📄 [Black_Friday_Proposal.pdf](./Black_Friday_Proposal.pdf)
