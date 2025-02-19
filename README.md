# **SQL Data Cleaning & Exploratory Data Analysis (EDA) Projects**  

This repository contains two **SQL projects** that showcase my expertise in **data cleaning, transformation, and analysis using MySQL**. The projects focus on a **layoffs dataset**, where I applied various techniques to prepare the data for analysis and uncover insights into **layoff trends, patterns, and anomalies**.  

---

## **Project 1: Data Cleaning in MySQL**  

### **Objective:**  
- Prepare a **raw layoffs dataset** for analysis by **removing duplicates, standardizing values, handling nulls, and converting data types**.  

### **Key Steps:**  
- **Created staging tables** by duplicating the original layoffs table.  
- **Removed duplicate records** by assigning row numbers and keeping only the first occurrence.  
- **Standardized text fields** by:  
  - Trimming extra spaces.  
  - Unifying industry and country name variations.  
  - Converting date strings to proper **DATE** format.  
- **Handled null values** and removed unnecessary records to produce a **clean, structured dataset** ready for analysis.  

---

## **Project 2: Exploratory Data Analysis (EDA)**  

### **Objective:**  
- Perform **in-depth analysis** on the cleaned layoffs dataset to uncover key trends, patterns, and anomalies.  

### **Key Analyses Performed:**  

#### **1. Data Overview:**  
- Previewed the dataset to understand its structure and key attributes.  

#### **2. Layoff Metrics:**  
- Identified the **largest single layoff event** and examined layoff percentage ranges.  

#### **3. Company & Location Analysis:**  
- Determined **companies that experienced 100% layoffs**.  
- Ranked companies based on:  
  - **Largest layoffs in a single event.**  
  - **Total layoffs across all events.**  
- Analyzed **layoffs by location and country**.  

#### **4. Temporal Trends:**  
- Examined **yearly and monthly layoff patterns**.  
- Calculated a **rolling total of layoffs over time**.  

#### **5. Industry & Stage Analysis:**  
- Summarized **total layoffs by industry and company funding stage**.  
- Applied **window functions** to identify top companies with the most layoffs per year.  

---

## **Insights Gained:**  
- Uncovered **major layoff events** and **companies with drastic workforce reductions**.  
- Revealed **geographic and industry-specific** layoff trends.  
- Detected **time-based patterns**, highlighting **periods of high layoff activity**.  

---

## **Final Thoughts:**  
These SQL projects highlight my **ability to clean, transform, and analyze real-world datasets**. By leveraging **MySQL functions and queries**, I successfully extracted valuable insights into **layoff trends across industries, companies, and time periods**. The techniques used in these projects form the foundation for **advanced data analytics and reporting**.  

👉 **Check out the SQL scripts and insights in this repository!** 🚀
