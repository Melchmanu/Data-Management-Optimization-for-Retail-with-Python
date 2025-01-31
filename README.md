Data Management Optimization for Retail with Python

This project focuses on optimizing the data management processes for a retail store by consolidating multiple data sources, identifying errors, and providing actionable insights. The analysis supports executive decision-making by aligning data with business objectives.

📄 Notebook
Overview

Retail businesses often struggle with disparate data sources and data quality issues. This project addresses these challenges by:

    Phase 1 - Data Consolidation and Cleaning:
        Aggregating data from ERP, e-commerce exports, and a liaison table.
        Identifying and resolving errors such as mismatched keys, outliers, and missing values.

    Phase 2 - Data Analysis:
        Performing sales and stock analysis (e.g., revenue, top products, 20/80 rule, stock rotation).
        Identifying outliers in pricing using statistical methods (e.g., Z-Score, interquartile range).
        Analyzing correlations between key metrics like price, stock levels, and sales.

Files

    Melchiori_Manuel_1_notebook_072024.ipynb: Python notebook that handles data consolidation, error identification, and data analysis.
    Melchiori_Manuel_2_presentation_072024.pptx: Executive presentation summarizing findings and actionable recommendations.
    web.xlsx: E-commerce data export with product descriptions and sales.
    erp.xlsx: ERP system export including product references, prices, and stock levels.
    liaison.xlsx: Liaison table for matching references between ERP and e-commerce exports.

How to Use

    Clone the repository and download the files.
    Open the notebook in Jupyter or any compatible IDE to explore the analysis.
    Review the presentation for a summary of key insights and recommendations.
    Use the datasets (web.xlsx, erp.xlsx, liaison.xlsx) for further exploration or testing.

Key Insights

    Data Cleaning:
        Detected 8+ types of data errors, including mismatches, outliers, and input errors.
        Recommended improvements to ensure consistent data across systems.

    Sales Analysis:
        Identified top-performing products using the 20/80 rule.
        Highlighted sales trends and profitability insights.

    Stock Optimization:
        Evaluated stock rotation and months of inventory.
        Suggested strategies to improve stock management and avoid overstocking.

    Correlations:
        Analyzed relationships between sales, price, stock, and margins to provide actionable recommendations.

Tools and Skills

    Languages: Python
    Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scipy
    Techniques:
        Data Cleaning and Feature Engineering
        Outlier Detection (Boxplots, Z-Score)
        Correlation Analysis
        Visualization of Insights

About

This project not only optimizes data management processes but also lays the foundation for future initiatives, including data visualization and GDPR-compliant workflows.

Feel free to explore, adapt, and improve the project for your needs!
