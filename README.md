# **Employee Work Environment and Well-Being Data Analysis**

## **Project Overview**
This project analyzes a dataset containing detailed information about employees, their work environment, job satisfaction, commute, and well-being. The goal of the analysis is to uncover insights into how various factors such as work-life balance, stress levels, physical activity, and commute influence job satisfaction and employee well-being.

The analysis was conducted using Python in a Jupyter notebook, leveraging popular libraries such as `pandas`, `matplotlib`, `seaborn`, and `numpy` to explore trends, correlations, and key insights from the data.

## **Dataset Description**
The dataset contains employee information, including their demographics, work conditions, and well-being metrics. Below is a description of the columns in the dataset:

### **Columns:**

1. **EmpID**: Unique identifier for each employee.
2. **Gender**: Gender of the employee (Male, Female, Other).
3. **Age**: Age of the employee.
4. **MaritalStatus**: Marital status (Single, Married, Divorced, Widowed).
5. **JobLevel**: Job level (Intern/Fresher, Junior, Mid, Senior, Lead).
6. **Experience**: Number of years of work experience.
7. **Dept**: Department (e.g., IT, HR, Finance, Marketing, Sales, Legal, Operations, Customer Service).
8. **EmpType**: Type of employment (Full-Time, Part-Time, Contract).
9. **WLB (Work-Life Balance)**: Rating of work-life balance (1 to 5 scale).
10. **WorkEnv (Work Environment)**: Rating of the work environment (1 to 5 scale).
11. **PhysicalActivityHours**: Number of hours of physical activity per week.
12. **Workload**: Workload rating (1 to 5 scale).
13. **Stress**: Stress level rating (1 to 5 scale).
14. **SleepHours**: Number of hours of sleep per night.
15. **CommuteMode**: Mode of commute (e.g., Car, Public Transport, Bike, Walk, Motorbike).
16. **CommuteDistance**: Distance traveled during the commute (in kilometers).
17. **NumCompanies**: Number of different companies the employee has worked for.
18. **TeamSize**: Size of the team the employee is part of.
19. **NumReports**: Number of people reported to by the employee (for Senior and Lead levels).
20. **EduLevel**: Highest level of education achieved (High School, Bachelor, Master, PhD).
21. **haveOT**: Indicator if the employee has overtime (True/False).
22. **TrainingHoursPerYear**: Number of hours of training received per year.
23. **JobSatisfaction**: Job satisfaction rating (1 to 5 scale).

## **Key Analysis Performed**

1. **Data Preprocessing**:
   - Cleaned and prepared the dataset, handling missing values and transforming certain columns (e.g., categorical encoding).
   - Converted appropriate columns (e.g., `JobLevel`, `Gender`, `EduLevel`) to categorical data types for more efficient analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Explored key metrics such as **Job Satisfaction**, **Work-Life Balance**, and **Stress Levels**.
   - Created visualizations using **bar charts**, **box plots**, and **line plots** to identify trends and relationships between various factors.
   - Grouped data by departments, job levels, and other demographic variables to compare satisfaction and well-being across employee segments.

3. **Correlation Analysis**:
   - Investigated the correlation between key factors such as **Workload**, **Stress**, **Commute Distance**, and **Job Satisfaction**.
   - Used **heatmaps** to visualize relationships between numerical variables like **Sleep Hours**, **Physical Activity**, and **Training Hours**.

4. **Well-Being and Job Satisfaction**:
   - Analyzed how well-being factors like **Work-Life Balance**, **Sleep Hours**, and **Physical Activity** influence **Job Satisfaction**.
   - Investigated whether **Commute Distance** and **Mode of Commute** affect employee stress and satisfaction levels.

5. **Departmental and Job Level Insights**:
   - Examined job satisfaction across departments and job levels to identify any patterns of dissatisfaction or high stress in specific roles or teams.

## **Results and Insights**

- **Work-Life Balance**: A strong correlation was observed between work-life balance and job satisfaction. Employees with a better work-life balance reported significantly higher satisfaction levels.
- **Stress and Job Satisfaction**: High stress levels negatively impacted job satisfaction, particularly in departments with larger workloads.
- **Commute and Well-Being**: Longer commute distances were linked to lower work-life balance and higher stress levels, particularly for employees commuting via car or public transport.
- **Sleep and Physical Activity**: Employees with more sleep and higher physical activity per week reported better work environment ratings and job satisfaction.

## **Tools and Libraries Used**

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **matplotlib**: For data visualization.
- **seaborn**: For advanced visualizations and statistical analysis.
- **scipy**: For statistical analysis.

## **Usage Instructions**

1. Clone this repository:
   ```bash
   git clone https://github.com/PhilipYaros/Employee_survey_data_analysis.git
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook to explore the analysis:
   ```bash
   jupyter notebook Employee_survey_analysis.ipynb
   ```

## **Conclusion**
The analysis provides valuable insights into employee satisfaction and well-being. Company management can use this information to improve work conditions, reduce stress, and increase overall job satisfaction. Improvements in work-life balance, stress management, and commute strategies could lead to a more engaged and productive workforce.

## **Contact**
For any questions or suggestions, feel free to contact me at [Philus012@gmail.com](mailto:Philus012@gmail.com).

---

### **Note**: Adjust the repository link and contact information to match your actual details.

