Maruthi-Prasanth E-Commerce Data Analysis


TABLE OF CONTENTS


ABSTRACT
DATASET
OBJECTIVE
DATA PROCESSING
VISUALIZATION
EXPLORATORY DATA ANALYSIS (EDA)
PREREQUISITES
INSTALLATION GUIDE
HOW TO USE
CONTRIBUTION
LICENSE



ABSTRACT


This project focuses on analyzing e-commerce transaction data using Big Data technologies like Apache Hive, Power BI, and Python-based EDA techniques. The project extracts meaningful insights from large datasets, visualizes business trends, and optimizes decision-making processes.



DATASET


The project uses e-commerce transaction datasets containing details like customer purchases, product categories, sales trends, and revenue generation. The data undergoes cleaning, transformation, and aggregation to derive valuable insights.



OBJECTIVE


The primary goal is to analyze e-commerce data to:


Identify sales trends across different product categories.
Understand customer purchasing behavior.
Generate interactive visualizations for better business insights.
Perform data-driven decision-making using Big Data tools.



DATA PROCESSING


Hive Queries (Hive Queries.docx)


This document contains SQL-like queries for Apache Hive to:


Clean and preprocess raw data.
Aggregate sales, revenue, and customer segmentation.
Perform trend analysis on product demand and seasonal variations.



VISUALIZATION


Power BI Visualization (PowerBi Viusalization.docx)


This document provides a step-by-step guide on creating interactive dashboards using Power BI:


Connecting Power BI to the transformed dataset.
Creating visualizations such as sales trends, revenue distribution, and customer behavior.
Extracting insights for data-driven business decisions.



EXPLORATORY DATA ANALYSIS (EDA)


Jupyter Notebook (r.ipynb)


This Python-based notebook contains EDA scripts using Pandas and Matplotlib:


Data loading and preprocessing.
Statistical analysis and feature engineering.
Visualization of key metrics like sales trends and customer purchase behavior.



PREREQUISITES


To run this project successfully, install the following dependencies:


Required Tools & Software:


Apache Hadoop & Hive (For querying large datasets)
Jupyter Notebook (For exploratory data analysis)
Python Libraries: Pandas, Matplotlib, Seaborn
Power BI Desktop (For data visualization)



INSTALLATION GUIDE


1. Install Hadoop & Hive


# Install Hadoop
sudo apt update && sudo apt install hadoop

# Install Hive
sudo apt install hive



2. Install Jupyter Notebook & Python Libraries


pip install jupyter pandas matplotlib seaborn



3. Install Power BI Desktop (Windows)


Download and install from: Power BI Download



HOW TO USE


Run Hive Queries: Open Hive Queries.docx, execute queries in the Hive CLI.
Perform EDA: Open r.ipynb in Jupyter Notebook and run the Python scripts.
Visualize Data: Use PowerBi Visualization.docx as a guide to create dashboards in Power BI.



CONTRIBUTION


Feel free to fork this repository, raise issues, or submit pull requests to improve the project.



LICENSE


This project is licensed under the MIT License.
