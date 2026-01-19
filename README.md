# black_friday_analysis
Black Friday Sales: Business proposal + production data pipeline (550k rows cleaned) → EDA/modelling roadmap
# 🛒 Black Friday Sales Analysis

## 🎯 Business Objective
See [🛒 proposal PDF](./Black_Friday_Proposal.pdf) for full business context


## 📊 Dataset
- 550,068 transactions from Black Friday sales
- Customer demographics + product categories + purchase amounts
- Challenge: ~58% missing secondary categories

## 🛠️ Data Pipeline (Complete)
✅ **Load** 550k rows  
✅ **Rename** snake_case columns  
✅ **Optimise** categorical dtypes (memory savings)  
✅ **Impute** product_cat2/3 → "Unknown" (preserves all data)  
✅ **Validate** no nulls/duplicates  

## 🔮 Next (WIP)
- EDA: Purchase distributions, customer segments  
- Features: Age numeric, category encodings  
- Model: XGBoost → RMSE prediction  

**Tech**: Pandas, (planned: Plotly, XGBoost)

[Black_Friday_Proposal.pdf](./Black_Friday_Proposal.pdf)
