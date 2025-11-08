# Global Health and Economic Development Analysis

## Project Overview
This project investigates how national health investments, education, and economic factors impact life expectancy worldwide. The analysis highlights global patterns in health spending efficiency, regional disparities, and actionable strategies for improving population well-being.

## Objectives
- Analyze the relationship between health expenditure and life expectancy  
- Examine how GDP per capita and education levels influence health outcomes  
- Identify countries achieving high efficiency (high life expectancy with moderate spending)  
- Detect outliers and regional disparities in health performance  
- Provide policy-level recommendations for improving health outcomes globally  

## Dataset
- Source: World Bank and World Health Organization (Global Health Expenditure Database)  
- Key Columns: Country, Year, GDP_per_capita, Health_Expenditure_per_capita, Life_Expectancy, Schooling, Mortality_rate  

## Tools and Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

## Steps Performed
1. Data loading and inspection  
2. Data cleaning and standardization  
3. Feature engineering (e.g., 3-year rolling averages, efficiency ratios)  
4. Exploratory Data Analysis (EDA)  
5. Correlation and regression analysis between key indicators  
6. Visualization of regional and temporal trends  
7. Policy and economic insights  

## Key Insights
- Countries with **higher GDP per capita** and **greater health expenditure per capita** generally exhibit higher life expectancy.  
- **Diminishing returns** occur after a certain spending level — high-income nations gain less additional life expectancy from extra spending.  
- Some nations achieve strong outcomes with moderate spending, marking them as **efficiency leaders**.  
- A few high-spending countries show **low efficiency**, indicating systemic challenges or inequality in healthcare delivery.  
- Education levels and reduced mortality rates correlate strongly with higher life expectancy.  

## Business and Policy Recommendations
- Reallocate spending from tertiary to **primary and preventive care** for better efficiency.  
- In **low-income countries**, even modest spending increases on essential health programs can yield large gains.  
- **Adopt best practices** from efficient countries that achieve high outcomes with moderate investment.  
- Combine **education and health policy** efforts to improve life expectancy through long-term social development.  
- Use composite metrics (life expectancy, expenditure, efficiency ratio) to monitor global progress.  

## Requirements
To install the required libraries, run:
