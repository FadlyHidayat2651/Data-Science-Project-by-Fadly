# Employee Attrition EDA & Machine learning Modeling in Healthcare Company 

  ## I. Business Understanding and Research Objective 
  ### I.1. Background
  
    Attrition is a condition or state where employee leave company because of several reason and can be categorized into two types: 
    1. Non-Voluntary Attrition: Employee leaves company but it doesn’t come from him.
    2. Voluntary Attrition: Employee leaves company and it comes from him
    Non-Voluntary attrition can also called as Lay-off. When companies are conducting attrition, 
    companies didn't find a replacement for his employees. This point can be differentiator between Attrition and Turnover
    
    There are several reasons why employee attrition happen: 
    1. Attrition is often called a hiring freeze or layoff and is seen as a less disruptive way to trim the workforce and reduce payroll than layoffs
    2. Merger and Acquisition from several companies to adapt new system
    3. Cancellation of project and technology enablement
    4. Decreased operation and outsourcing options
    5. Need to pay debts and lost of investor
    6. Complex condition when Voluntary Attrition are combined with Non-Voluntary Attrition
    
    Currently, healthcare company become one of industry sectors that experience attriton such as in Cedar Healthcare Center, 
    they are need to layoff 3000 people, also there are several factors that create attrition in healthcare company:
    1. Stressful nature of the healthcare work industry
    2. High work hours and experience high burnout
    3. Impact quality of care and the speed to care are often negatively impacted
    
  ### I.2. Project Scope
  
    1. Dataset used is a dataset from Kaggle which provides employee attrition data for healthcare companies with 1600 datas
    2. Project conducted for my learning purposes as an aspiring  data scientist, if you find any misleading information, 
    don’t hesitate to contact me, we are going to focus on voluntary attrition since data gives more variable from employe perspective

  ### I.3. As-is condition and Research Goals 
  
    Currently, there are lot of datas that tells about the importance of attrition, however there are still lack information 
    about main factors from employee to leave their companies along with model to predict attrition in companies, based on background, project scopes, and as-is condition, we can define the research goals as: 
    1. Define factors that create voluntary employee attrition
    2. Giving Recommendation to prevent voluntary employee attrition
    3. Develop a machine learning model to predict voluntary employee attrition
  
## II. CRISP DM Model Development including EDA
    1. Data Understanding and Data Cleansing
    2. Exploratory Data Analysis
    3. Data Preprocessing
    4. Modelling
    5. Evaluation
    
 ### II.1. Exploratory Data Analysis Insight
    1. The number of attritions in this healthcare industry is still quite low (11.9%) of all data.
    2. Employees who  experience attrition have a younger average age of 29 years and those who survive at 36 years,
    indicating that they still want to seek some career opportunity
    3. Lower salary, Lower Hourly rate, and the further a person lives from his office become a factor for someone leave their company
    4. People with low job satisfaction rating (below 2.5/4) have a tendency to leave their jobs
    5. Employees with a salary increase percentage below 15% have a tendency leave the company
    6. People with a salary of less than 2500 (unit of money)/month  have a tendency to leave the company.
    7. People with an average training time from the office of less than 2 hours per agreed time period are more likely to leave the company.
    8. Employees who have worked longer in a an average 3 years at their current position have the possibility to stay in their jobs
    9. Nurse is the job with the highest number of jobs in the hospital and has a higher number of attritions (52% from total attrition data)
    10. People with average work shift below 2 have a tendency to leave their company
    11. An unmarried person has a bigger tendency (25%) to leave the company

## III. Summary and Recommendation

  ### III.1. Summary
  
    1. Based on feature importances and EDA there are several factor that give big impact to Employee Attrition at Hospital you can refer EDA and Feature Importance Analysis
    2. Recommendation already given in Recommendation section based on EDA and Feature Importance Analysis
    3. Model already develop using Random Forest Regressor with HP tuning by Accuracy around 95%
    
  ### III.2. Recommendation
  
    1. Employee with younger age should be given several method to keep them stay at this company, 
    such as: Job enlargement, Job Enrichment, Job Involvement, using Mentor and Buddies system to make them can explore more opportunity jobs at your company.
    2. Defining KPI and clear job role, including the segmentation of work shifts that must be more regular to every employee to make them still performing and after that you should define clear job career process for every division and team.
    3. The payroll system must be improved on a certain basis such as hourly payment system, KPI based salary, and structural based salary. 
    4. Creating good work environment to increase job satisfaction index
    5. Creating competency dictionary for every job role with change management and improvement management process and executing the process by creating several sharing session, coaching session and training for employee.
    6. Should conduct deep dive analysis for several features that still gives not clear information



