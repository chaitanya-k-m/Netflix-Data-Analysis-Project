# Analyzing Netflix Content Trends: Data Exploration & Insights  

## **Project Overview**  
This project explores **Netflix's content evolution** over time using **data analysis and visualization techniques**. By leveraging a structured dataset, the study uncovers key insights into **genre trends, content additions, and regional contributions** to Netflix’s library. The analysis focuses on two key questions:  
1. **What are the common characteristics of content added to Netflix in 2020?**  
2. **How have Netflix's content themes and genres evolved over the years?**  

## **Dataset**  
- **Source:** [Netflix Shows and Movies Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
- **Contents:** Includes details on title, director, cast, country, release year, date added, duration, and genres.  

## **Key Insights & Findings**  
### **1. Netflix Content in 2020**  
- **Content Type Distribution:** Examined the ratio of **Movies vs. TV Shows**.  
- **Most Popular Genres:** Identified the **most prevalent genres** added to Netflix in 2020.  
- **Top Content-Producing Countries:** Determined which **regions contributed the most content**.  

### **2. Genre Trends Over the Years**  
- **Historical Genre Evolution:** Analyzed shifts in **popular genres from Netflix’s inception to 2021**.  
- **Content Strategy Trends:** Uncovered how Netflix has **diversified content themes** over time.  
- **Emerging Genres:** Highlighted **new categories gaining popularity** in recent years.  

## **Data Cleaning & Processing**  
- **Handled missing values** by replacing them with `"Unknown"`.  
- **Standardized date formats** and converted `date_added` to a **datetime object**.  
- **Reformatted genre information** into binary columns for improved analysis.  

## **Methodology & Workflow**  
1. **Filtered data for 2020-specific analysis.**  
2. **Used value_counts() & groupby()** to identify leading genres and content-producing countries.  
3. **Computed CAGR (Compound Annual Growth Rate)** to track genre expansion over time.  
4. **Utilized Matplotlib & Seaborn** to visualize content distribution and trends.  

## **Technology & Tools Used**  
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** – Data processing & visualization.  
- **Jupyter Notebook** – Interactive data analysis.  
- **Excel (Output File)** – Final report generation.  

## **Project Deliverables**  
- **Jupyter Notebook with full analysis (Mini_Project.ipynb)**  
- **Processed Output File (Excel) showing summary and trends**  
- **Final Report (PDF) with detailed findings**  

