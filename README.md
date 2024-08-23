
## **Employee Salary Analysis of San Francisco**

### **Project Overview**
This project aims to analyze the salary data of employees in San Francisco to identify trends, patterns, and anomalies. The analysis was conducted using Python for data cleaning and exploratory data analysis (EDA), with visualizations created in both Python and Tableau. The project was managed and version-controlled using Git and GitHub.

### **Project Workflow**

1. **Data Loading and Initial Exploration**
   - The project begins with loading the dataset using Pandas and conducting an initial exploration to understand its structure and contents.
   - Key columns include `EmployeeName`, `JobTitle`, `BasePay`, `OvertimePay`, `Benefits`, and `TotalPay`.

2. **Data Cleaning**
   - Missing values were identified and handled appropriately:
     - Columns with excessive missing values (`Notes` and `Status`) were dropped.
     - Missing values in numeric columns (`BasePay`, `OvertimePay`, `OtherPay`, and `Benefits`) were filled with their respective median values.
   - The cleaned dataset ensures integrity and readiness for analysis.

3. **Exploratory Data Analysis (EDA)**
   - Descriptive statistics were generated to understand the central tendencies and variability in the data.
   - Visualizations, including histograms and KDE plots, were created to explore the distributions of `BasePay`, `OvertimePay`, `OtherPay`, and `Benefits`.
   - A correlation matrix was used to identify relationships between salary components, providing insights into how different pay factors interact.

4. **Advanced Visualization with Tableau**
   - The cleaned dataset was exported to CSV and further visualized in Tableau to create interactive and dynamic dashboards.
   - Tableau enabled deeper insights and allowed for exploration of the data from various perspectives.

5. **Version Control with Git and GitHub**
   - The entire project was managed using Git for version control, with the final version pushed to GitHub.
   - This approach ensures that the project is well-organized, trackable, and easily shareable.

### **Tools and Technologies Used**
- **Python**: Data cleaning, EDA, and initial visualizations.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib & Seaborn**: Data visualization in Python.
- **Tableau**: Advanced and interactive data visualization.
- **Git & GitHub**: Version control and project management.

### **Conclusion**
The analysis provides valuable insights into how San Francisco compensates its employees, highlighting key areas such as base pay disparities, reliance on overtime, and variability in benefits. These findings can inform policy decisions and contribute to a more equitable and efficient compensation strategy.

