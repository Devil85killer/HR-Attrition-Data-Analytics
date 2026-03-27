# 📊 HR Attrition & Performance Analytics

## 🎯 Project Objective
The goal of this project is to analyze HR data to understand why employees are leaving the company (Attrition) and to build a highly interactive dashboard for the HR department to identify key trends and burnout factors.

## 🛠️ Tools & Technologies Used
* **Python (Pandas):** For Data Extraction, Cleaning, and Exploratory Data Analysis (EDA).
* **Power BI:** For Data Visualization and building the final interactive dashboard.

## 📈 Key Insights Discovered
Through Python analysis and Power BI visualization, we found the following critical insights out of 1,470 employees:
1. **Overall Attrition:** 237 employees (approx. 16%) left the company.
2. **The Burnout Factor:** Employees doing **OverTime** have a significantly higher attrition rate. While only 10% of non-overtime employees left, almost 30% of those doing overtime quit.
3. **Department Risk:** Research & Development lost the highest number of people (133), but the **Sales** department has the highest attrition *ratio*.
4. **Role Specifics:** 'Laboratory Technicians' and 'Sales Executives' are the most likely to leave the organization.
5. **Job Satisfaction:** A large portion of employees who left had marked their Job Satisfaction as '1' (Lowest).

## 🖥️ Dashboard Snapshot
![HR Dashboard](Dashboard_Image.png)
*(Note: Ensure your screenshot is named 'Dashboard_Image.png' in the repo for this image to show up!)*

## 💡 How to use this repository
1. `hr_analysis.py`: Contains the Python code used for initial data cleaning and EDA.
2. `Cleaned_HR_Data_For_PowerBI.csv`: The cleaned dataset exported from Python.
3. `HR_ANALYSIS.pbix`: The complete Power BI dashboard file. Download and open in Power BI Desktop to interact with the visual filters.
