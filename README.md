# MRPTeam11
# Employment Analytics Project
 
## 1. Project Title
**Employment Analytics Project**  
*A comprehensive Power BI platform developed to help students at Saint Louis University enhance their career success through data-driven insights.*  
 
---
 
## 2. Project Description
This application enables students to track their learning progress and employability using real-time data from platforms like Skillsoft Percipio, Coursera, and Udemy. It aligns their course completions, skill acquisition, and readiness scores with current job market needs—offering personalized career guidance through interactive dashboards.
 
### Key Features:
- Real-time tracking of student progress and career readiness.
- AI-driven career guidance and predictive job matching.
- Personalized skill and job recommendations.
- Interactive data visualization and analysis using Power BI.
- Seamless user experience with high data accuracy and integrity.
 
---
 
## 3. Table of Contents
## 3. Table of Contents
- [Installation / Setup](#4-installation--setup)
- [Usage](#5-usage)
- [Features](#6-features)
- [Ensuring Data Accuracy & Reliability](#7-ensuring-data-accuracy--reliability)
- [Refining Data: From Raw to Ready](#8-refining-data-from-raw-to-ready)
- [Dashboard File](#9-dashboard-file)
- [Team Roles](#10-team-roles)
- [Contributing](#11-contributing)
- [Team Reflection](#12-team-reflection)
- [License](#13-license)
- [Acknowledgements](#14-acknowledgements)

 
## 4. Installation / Setup
### Power BI File Setup:
1. Download the Power BI file (`E learning employability.pbix`).
2. Open the file using Power BI Desktop.
3. Ensure all data connections to Skillsoft, Coursera, and Udemy are verified..
 
### Data Connection:
- Ensure that Skillsoft Percipio, Coursera, and Udemy data sources are properly linked in Power BI.
- Refresh to retrieve updated metrics before usage.
- Verify that credentials and permissions are configured correctly.
 
---
 
## 5. Usage
### To View the Dashboard:
1. Open the `Employbility_Analytics_Project.pbix` file in Power BI Desktop.
2. Refresh the data to pull the latest insights.
3. Navigate through the dashboard to explore:
   - Skill acquisition progress
   - Course completion rates
   - Employment readiness metrics
4. Use filters to drill into:
   - Skill development by platform
   - Selection of courses based on skill
   - Selection of courses based on rating
   - Selection of courses based on level
   - Employability readiness scores
Course completion rates
5. Export reports using the **Export** option in Power BI.
 
### Sample Screenshot:
![image](https://github.com/KavyaSrikatla/MRPTeam11/blob/main/coursera.png)
![image](https://github.com/KavyaSrikatla/MRPTeam11/blob/main/udemy.png)
![image](https://github.com/KavyaSrikatla/MRPTeam11/blob/main/skillsoft.png)
 
---
 
## 6. Features
Employability Readiness Score: Evaluate your job readiness in real-time.
Platform Performance Tracker: Compare course effectiveness across Skillsoft, Udemy, Coursera.
Advisor Ranking: See which advisors produce the best employability outcomes.
Dynamic Filtering: Slice data by department, course, or advisor.
Export & Report: Generate polished, shareable reports directly from Power BI.
Dynamic Dashboard:Real-time overview of student progress, course completion rates, and employment readiness.  

---
 
## 7. Ensuring Data Accuracy & Reliability
- **Duplicate Removal:** Removed duplicate courses from Coursera and Udemy.
- **Missing Data Handling:** Managed missing values using median imputation and "Unknown" placeholders.
- **Referential Integrity:** Ensured primary key relationships between User ID and Course Title.
- **Field-Level Integrity:** Converted all numeric data to the correct types and validated consistency.
- **Data Validation & Preparation:**
   - Null Handling: Replaced missing fields with median or "Unknown".
   - Referential Integrity: Maintained primary key relationships.
-  **Custom Calculations:**
   - Readiness Score: Weighted score based on course completion, platform quality, and advisor engagement.
   - Filtering invalid entries or duplicates.
- **Tools Used:** Power BI DAX, Excel formulas, and manual quality review.
- **Courses That Helped:**
 - Data-Driven Decision Making (user modeling & KPI alignment)
 - Power BI for Business Intelligence (dashboard creation, DAX)
 - Survey Research Methods (Skillsoft survey design & analysis)
 - Data Wrangling (data cleaning, joining, and transformation)

---
 
## 8. Refining Data: From Raw to Ready
- Conducted a manual review of column names and missing values.
- Verified logical user-course connections post-merging.
- Ensured final dataset is clean, structured, and ready for analysis in Power BI.
 
---
 
## 9. Dashboard File  
The following files are submitted as part of the final project:

- [Final Power BI dashboard](https://github.com/KavyaSrikatla/MRPTeam11/blob/98fdee161d937f7d58470f80ef06ed4763bd5f7a/E%20learning%20employability.pbix)
- [Coursera raw data](https://github.com/KavyaSrikatla/MRPTeam11/blob/98fdee161d937f7d58470f80ef06ed4763bd5f7a/Coursera.csv)
- [Skillsoft raw survey responses](https://github.com/KavyaSrikatla/MRPTeam11/blob/8b3fbeed162afb961def17e639bc8fbe1ea75460/Skillsoft%20Percipio.csv)
- [Udemy raw data](https://github.com/KavyaSrikatla/MRPTeam11/blob/98fdee161d937f7d58470f80ef06ed4763bd5f7a/Udemy.csv)
- [Coursera Filtered data](https://github.com/KavyaSrikatla/MRPTeam11/blob/main/Coursera%20Final.xlsx)
- [Skillsoft Filtered data](https://github.com/KavyaSrikatla/MRPTeam11/blob/main/Skillsoft%20Final.xlsx)
- [Udemy Filtered data](https://github.com/KavyaSrikatla/MRPTeam11/blob/main/Udemy%20Final.xlsx)
- [README.md – Complete project documentation](https://github.com/KavyaSrikatla/MRPTeam11/blob/main/README.md)

---
## 10. Team Roles
- Hema: Data preprocessing and validation
- Ayyappa: Power BI modeling
- Kavya Sri & Kavya Reddy: Data integrity checks, UI/UX design, survey analytics
- Subhash & Sahithi: Documentation

## 11. Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to modify.
 
---

## 12. Team Reflection

This project taught us how to:

- Define and refine a clear user-centered problem (students as primary decision-makers).
- Coordinate tasks and timelines across six team members.
- Acquire domain knowledge in employability analytics.
- Manage real datasets across multiple sources.
- Apply visual storytelling to support career guidance.
 
## 13. License
MIT License. See [LICENSE](LICENSE) for details.
 
---
 
## 14. Acknowledgements
Shoutout to **Team 11** for their incredible effort:
- Ayyappa Kalluri  
- Hema Chowdary Kankanala  
- Kavya Sri Katla  
- Sahithi Karnati  
- Subhash Chandra Karuturi  
- Kavya Reddy Rachupalli
