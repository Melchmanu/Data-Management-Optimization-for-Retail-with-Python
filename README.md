# Data Management Optimization for Retail with Python

## Overview
This project focuses on optimizing data management for a retail business by consolidating multiple data sources, identifying and correcting errors, and delivering actionable insights. The analysis helps align data with business goals and supports informed decision-making.

## Notebook 📓
- [Data Consolidation, Cleaning, and Analysis](https://github.com/Melchmanu/Data-Management-Optimization-for-Retail-with-Python/blob/main/Melchiori_Manuel_1_notebook_072024.ipynb)

## Data Pipeline
The project is divided into two main phases:

- **Phase 1: Data Consolidation and Cleaning**  
  - Aggregated data from ERP, e-commerce systems, and a liaison table to unify references.  
  - Identified data errors such as mismatches, outliers, and input mistakes.  
  - Proposed solutions to improve data quality and ensure consistency.  

- **Phase 2: Data Analysis**  
  - Performed sales analysis, including revenue by product and overall totals.  
  - Analyzed stock metrics, including turnover rate and inventory coverage.  
  - Detected pricing anomalies using boxplots and statistical methods.  
  - Evaluated correlations between quantitative metrics like price, stock, and sales.  

## Files
- `Melchiori_Manuel_1_notebook_072024.ipynb` : Python notebook containing the full analysis pipeline.
- `Melchiori_Manuel_2_presentation_072024.pptx` : Executive summary and recommendations in a presentation format.
- `web.xlsx` : E-commerce export with product descriptions and sales data.
- `erp.xlsx` : ERP system export containing product references, prices, and stock levels.
- `liaison.xlsx` : Liaison table for matching product references across systems.

## How to Use
1. Clone this repository to your local machine.  
2. Install required Python libraries using `pip install -r requirements.txt`.  
3. Open the notebook in Jupyter or any compatible IDE to explore the analysis.  
4. Review the presentation for a concise summary of key insights and suggestions.

## Key Features
- **Data Cleaning:**  
  - Resolved 8+ types of data errors, including mismatched keys, outliers, and formatting issues.  
  - Formalized processes to ensure a GDPR-compliant and consistent database.  

- **Sales Analysis:**  
  - Identified top products, applied the 20/80 rule, and generated actionable insights.  
  - Highlighted trends in profitability and sales performance.  

- **Stock Optimization:**  
  - Evaluated stock rotation, inventory duration, and pricing anomalies.  
  - Suggested strategies to enhance inventory management and reduce waste.  

- **Correlation Analysis:**  
  - Explored relationships between metrics like price, sales, stock, and margins to uncover patterns.

## Future Improvements
- Develop an interactive data visualization dashboard for real-time insights.  
- Automate the data consolidation process for scalability.  
- Enhance predictive models to forecast sales and stock trends.  
