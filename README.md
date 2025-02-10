**GenZ Dating App Data Analysis**

**Overview**
This dataset captures the dating behaviors, preferences, and challenges faced by **Gen-Z users** (ages 18-25) across various dating apps. It includes demographic information, app usage patterns, satisfaction levels, and user preferences, providing a comprehensive view of how Gen-Z interacts with digital dating platforms.

**Dataset Details**
- **File Name:** `GenZ_DatingApp_Data.csv`
- **Total Rows:** 500
- **Total Columns:** 16

 **Column Descriptions:**

| **Column Name**               | **Description**                                                | **Type**     |
|-------------------------------|----------------------------------------------------------------|--------------|
| `User_ID`                     | Unique identifier for each user                                | Numerical    |
| `Age`                         | Age of the user in years (18-25)                               | Numerical    |
| `Gender`                      | Gender identity of the user (e.g., Male, Female, Non-binary)   | Categorical  |
| `Location`                    | City or region where the user lives                            | Categorical  |
| `Education`                   | Education level (e.g., Undergraduate, Graduate)                | Categorical  |
| `Occupation`                  | Employment status (e.g., Student, Freelancer, Full-time Job)   | Categorical  |
| `Primary_App`                 | Main dating app used by the user                               | Categorical  |
| `Secondary_Apps`              | Other dating apps the user engages with                        | Categorical  |
| `Usage_Frequency`             | Frequency of app usage (e.g., Daily, Weekly, Monthly)          | Categorical  |
| `Daily_Usage_Time`            | Time spent on dating apps daily (e.g., 30 minutes, 1 hour)     | Categorical  |
| `Reason_for_Using`            | Reason for using dating apps (e.g., Casual Dating, Finding a Partner) | Categorical  |
| `Satisfaction`                | Satisfaction rating on a scale from 1 (Very Dissatisfied) to 5 (Very Satisfied) | Numerical    |
| `Challenges`                  | Issues faced while using dating apps (e.g., Safety Concerns, Time-Wasting) | Categorical  |
| `Desired_Features`            | Features users wish to see in dating apps (e.g., Video Calls, AI Recommendations) | Categorical  |
| `Preferred_Communication`     | Preferred communication method (e.g., Text, Video Calls)       | Categorical  |
| `Partner_Priorities`          | Traits prioritized in a partner (e.g., Appearance, Values, Personality) | Categorical  |

---

 **Data Cleaning Steps**
1. **Duplicate Removal:**
   - No duplicate rows were detected in the dataset.

2. **Missing Values:**
   - **`Primary_App`** had **21.4% missing values**.
     - Missing values were filled with **"Unknown"** to maintain data integrity.

3. **Categorical Inconsistencies:**
   - Standardized values for case sensitivity (e.g., "Male" and "male" were unified).
   - Removed extra spaces and corrected any spelling errors.

4. **Outlier Detection:**
   - No outliers were found in the **`Age`** and **`Satisfaction`** columns using the IQR method.

---

 **Project Goals**
1. **Analyze Demographic Influences:**
   - How do gender, age, and location affect dating app preferences?

2. **Usage Patterns:**
   - Are Gen-Z users engaging with multiple dating apps simultaneously?
   - Which age group is the most active on dating apps?

3. **Urban vs. Rural Analysis:**
   - Do users in urban areas show different dating behaviors compared to rural users?

4. **Challenges and Feature Demands:**
   - Identify the most common challenges faced by users.
   - Highlight desired features that could improve dating apps.

---

 **Version Control & Collaboration**
This project is managed using **Git** and **GitHub** to ensure version control and collaboration.

- **Initial Commit:** `Initial dataset upload: GenZ Dating App Data`
- **Subsequent Changes:**
  - `Cleaned dataset: Removed duplicates, handled missing values, standardized categories.`
  - `Feature engineering: Added 'active_app_count' feature.`
  
Branches are used for specific tasks:
- `feature-data-cleaning`: For data cleaning and preprocessing.
- `feature-EDA`: For exploratory data analysis.

---

 **How to Use the Dataset**
1. **Exploratory Data Analysis (EDA):** Analyze usage patterns, demographic influences, and challenges.
2. **Machine Learning Modeling:** Use cleaned data to predict satisfaction levels or app preferences.
3. **Feature Engineering:** Create new features like "active app count" for enhanced modeling.
4. **Business Insights:** Inform dating app companies about Gen-Z preferences and potential areas for improvement.

---

 **Contact**
For questions or collaboration, please contact:

**Name:** Abdulazeez Raheem
**Email:** abdazeezraheem6@gmail.com  
**GitHub:** [(https://github.com/Papiiii01/ML-EDA.git)]

---

