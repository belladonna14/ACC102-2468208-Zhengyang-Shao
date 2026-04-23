
# ACC102-2468208-Zhengyang-Shao
My individual python work for ACC102 assignment
# ACC102 Track 2: Foreign Banks in China USD Deposit Rates Analysis (2018-2026)
## Impact of US Federal Reserve Monetary Policy

### 1. Analytical Problem
This project explores how US Federal Reserve (Fed) interest rate policy impacts USD time deposit rates of major foreign banks operating in China (Standard Chartered, HSBC, Citi). The goal is to:
- Quantify the correlation between Fed rates and foreign banks' USD rates
- Build a reusable predictive model for USD deposit rate forecasting
- Provide insights for USD depositors and banking analysts

### 2. Dataset (Professional Grade)
| Data Category                | Source                                                                 |
|------------------------------|------------------------------------------------------------------------|
| SCB/HSBC/Citi USD Rates      | Official bank announcements (2018-2026)                                |
| US Federal Reserve Rate      | Federal Reserve Economic Data (FRED) via Wharton Research Data Services (WRDS) |
| Time Range                   | 2018-2026 (covers COVID rate cuts, Fed hike cycle, post-hike easing)   |

### 3. Python Workflow (Reusable Structure)
1. `load_data()`: Load and structure multi-bank + Fed rate data
2. `clean_data()`: Standardize and validate financial data
3. Visualization Functions: 4 professional trend/comparison charts
4. `calculate_correlation()`: Quantitative correlation verification
5. `rate_prediction_model()`: Reusable predictive tool
6. `show_conclusions()`: Automated insight generation

### 4. Key Findings
- **Extreme Correlation**: All 3 foreign banks show >0.95 correlation with Fed rate (WRDS data verified)
- **Policy Synchronization**: 2020 COVID rate cuts and 2022 Fed hikes are fully reflected in banks' USD rates
- **Predictive Power**: Linear regression model achieves >95% accuracy in predicting bank rates using Fed data
- **Market Consistency**: Minimal differences between foreign banks' USD rate pricing

### 5. Demo Video Link
[Your Video Link Here]

### 6. How to Run (Reusable Instructions)
1. Install dependencies: `pip install pandas matplotlib scikit-learn`
2. Run the Jupyter Notebook (one-click execution)
3. All charts and analysis will generate automatically

### 7. Limitations & Future Improvements
- Limitation: Excludes promotional rates and exchange rate impacts
- Future: Add more foreign banks + macroeconomic factor analysis
