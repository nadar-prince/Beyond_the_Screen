# 📱 Gen Z Digital Habits & Psychological Impact

A Business Intelligence project analyzing a massive 1-million-row dataset to uncover the behavioral patterns behind digital platform usage. This project transitions raw, unstructured data into actionable insights, exploring how daily screen habits correlate with psychological well-being and overall digital behavior.

## 📖 Overview

With digital consumption at an all-time high, understanding the true psychological impact of screen time is critical. Raw behavioral data is often siloed, unstructured, or too massive to interpret without the right framework. 

This project tackles that challenge by building a robust data analytics pipeline. By transforming complex survey and usage data into a highly interactive, diagnostic dashboard, this project shifts the focus from simply tracking screen time to conducting deep behavioral analytics. It provides a scalable, data-driven solution for understanding psychological risk thresholds and platform-specific behavioral patterns.

## ✨ Key Features

* **End-to-End ETL Pipeline:** Extracted and transformed raw datasets using Power Query. Standardized data types, resolved inconsistencies, and engineered conditional columns (like optimized `Age Group` categorization) for precise Gen Z demographic analysis.
* **Robust Data Architecture:** Engineered a highly optimized Star Schema data model. Established precise 1-to-many relationships between central fact tables (usage metrics) and dimension tables (demographics, platforms) to ensure seamless cross-filtering and accurate aggregations.
* **Advanced DAX & Interactivity:** Centralized complex business logic using Data Analysis Expressions (DAX) to compute core KPIs, including average daily screen time and psychological risk indicators. Designed a modern, dark-themed UI featuring dynamic bookmarks, multi-level drill-throughs, and action buttons for granular platform exploration.

## 📊 Key Findings & Results

* **The "20-20-20" Correlation:** The data visualizations clearly validated that continuous platform usage for >2 hours without breaks heavily correlates with specific psychological risk factors and digital strain.
* **Platform Deep Dives:** Specialized visual matrices and funnel charts successfully mapped complex user behaviors, directly correlating specific social platform usage with severe nighttime engagement spikes.
* **Big Data Optimization:** Visualized and processed the 1-million-row dataset with zero lag. Extensive testing using the Power BI Performance Analyzer confirmed highly optimized query load times, ensuring a seamless user experience across all interactive dashboard features.

## 🛠️ Technologies

* **Business Intelligence:** Power BI
* **Data Transformation (ETL):** Power Query
* **Analytics & Calculations:** DAX (Data Analysis Expressions)
* **Data Architecture:** Star Schema Modeling
* **Foundational Data Handling:** Microsoft Excel / CSV
