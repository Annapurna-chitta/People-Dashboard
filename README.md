# People Dashboard
## Project Overview
This Power BI dashboard provides a comprehensive view of workforce analytics, focusing on employee demographics, performance, training, engagement, and risk assessment. It enables data-driven decision-making by identifying key workforce trends, attrition risks, and opportunities for retention and training improvement.

## Metadata
The database is obtained from Kaggle. https://www.kaggle.com/datasets/hopesb/hr-analytics-dataset. 
Removed 2 columns Unnamed and exit reason(no proper response captured). 37 columns 
Dataset divided into multiple Fact tables – Employee, Training, Survey, Performance, Job
Employee Table: Email, DOB, Employee ID, Start date, Exit Date, First Names, Gender, Last Name, Location, Location code, Maritasl Desc, Race Desc, State
Training: Employee ID, Training Date, Training Program Name, Training Type, Training Outcome, Trainer, Training Duration, Trainin Cost
Survey: Empoyee Id, Survey Date, Engagement Score, Satisfaction Score, Work Life Balance Score
Performance: Performance Score, Current Rating, Employee Id
Job: Title, Supervisor, Business Unit, Status, Type, PayZone, Termination Type, Department Type, Division, Job Function Description, Employee ID
Obtained relationships based on employee id in each table. 

## Key Features
* **Demographics & Workforce Distribution:** Displays employee count, gender distribution, and employment types (full-time, part-time, contract).

* **Risk Score Analysis:** Categorizes employees into High, Medium, and Low risk based on engagement and performance metrics.

* **Performance & Training Insights:** Tracks performance distribution, training costs, and effectiveness.

* **Attrition & Termination Analysis:** Visualizes attrition rates and termination type counts for workforce planning.

* **Engagement & Satisfaction Trends:** Highlights scores for engagement, work-life balance, and satisfaction.

* **Actionable Recommendations:** Includes insights for talent retention, training investment, and engagement improvement.

## Recommendations
* Evaluate Contract-to-Full-Time Conversion Opportunities to Enhance Retention and Workforce Stability
  - A significant portion of employees are in contract roles (33.6%), which may impact long-term retention and organizational stability.
  - Assess the feasibility of converting high-performing contract employees to full-time roles to improve engagement and reduce turnover.

* Address High-Risk Departments with Targeted Interventions
  - The risk score analysis highlights certain departments with higher risk levels, potentially due to performance gaps, workload issues, or attrition trends.
  - Implement customized strategies such as mentorship programs, workload distribution, and targeted support to mitigate these risks.

* Track Performance Before & After Training to Justify Costs
  - Training investments should directly impact employee performance and productivity.
  - Establish key metrics to evaluate pre- and post-training performance to assess effectiveness and optimize future learning programs.

* Conduct Pulse Surveys to Understand Low Engagement/Satisfaction
  - Engagement and satisfaction scores indicate areas of improvement, but deeper insights are required.
  - Implement frequent, short employee surveys to capture real-time feedback and address concerns proactively.

* Foster a Balanced Workforce by Recruiting Across Age Groups
  - The workforce demographic data suggests potential gaps in age diversity, which can impact team dynamics and innovation.
  - Develop hiring strategies that encourage applications from diverse age groups to foster a well-rounded, experienced, and adaptable workforce.
  
* Capture Exit Data Well
  - Understanding why employees leave is crucial for refining retention strategies.
  - Improve exit interview processes and collect structured feedback on reasons for attrition, allowing for data-driven improvements in workforce planning.
