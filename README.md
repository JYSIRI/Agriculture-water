# Agriculture-water
Overview 
This Jupyter notebook analyzes global agricultural freshwater withdrawal data to identify trends, regional disparities, and correlations with economic factors. The analysis includes data cleaning, feature engineering, statistical summaries, and visualizations to highlight key patterns in water usage.  

Contents 
1. Data Preparation 
   - Loading datasets (agricultural withdrawal data and country metadata)  
   - Reshaping data from wide to long format  
   - Merging with regional/income group metadata  
   - Handling missing values  

2. Feature Engineering
   - Calculating latest withdrawal values per country  
   - Computing percentage changes (1990–2020)  
   - Normalizing withdrawal values  

3. Statistical Analysis  
   - Summary statistics by income group  
   - Identifying top/bottom 10 countries by withdrawal percentages  

4. Visualizations
   - Distribution of agricultural water withdrawal (histogram)  
   - Income group comparisons (descriptive statistics)  
   - Trend analysis for selected countries  


Requirements 
- Python 3.x  
- Libraries:  
  *python
  pandas, numpy, matplotlib, seaborn, warnings
    
Data Files:  
  - `API_ER.H2O.FWAG.ZS_DS2_en_csv_v2_14593.csv` (agricultural withdrawal data)  
  - `Metadata_Country_API_ER.H2O.FWAG.ZS_DS2_en_csv_v2_14593.csv` (metadata)  

Installation  
pip install pandas numpy matplotlib seaborn
  

Launch Jupyter Notebook  
jupyter notebook Agricultural_Freshwater_Withdrawal_Analysis.ipynb  

# Key Insights 
1.Income Correlatio: Low-income countries average ~90% agricultural water use vs. ~30% in high-income nations.  
2.Regional Trends: Sub-Saharan Africa and South Asia show the highest dependencies on agricultural water.  



# Future Work  
1. Advanced Analysis 
   - Integrate climate datasets to study drought/rainfall impacts.  
   - Compare with industrial/domestic water withdrawal trends.  

2. Predictive Modeling  
   - Time-series forecasting for water usage trends:  
     - ARIMA/SARIMA for seasonal pattern analysis  
     - Machine Learning (e.g., Random Forests, Gradient Boosting)  
   - Geospatial analysis using GDP/population growth data.  

3. Policy Impact Evaluation  
   - Model scenarios for sustainable water management.  
   - Compare with UN Sustainable Development Goals (SDGs).  
