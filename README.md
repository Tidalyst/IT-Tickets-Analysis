# IT-Help_Desk-Analysis

## Project Overview 

The IT Department, responsible for managing internal support requests, aims to improve service delivery by strengthening how tickets are monitored and resolved. This project analyzes IT ticket data to uncover workload patterns across days, identify recurring issue types, evaluate SLA compliance, and assess agent efficiency. The findings provide actionable insights to optimize resource allocation, improve accountability, and enhance end-user satisfaction.



## Project Statement

The IT Department faces challenges such as uneven ticket inflow, recurring request backlogs, and inconsistent SLA compliance. Some agents are overburdened while others handle fewer tickets, creating inefficiencies and delays in resolution. Without a structured framework for analyzing support tickets, management lacks the visibility needed to optimize performance, ensure SLA adherence, and deliver timely, reliable IT support.



## Data Source: 

The dataset was sourced from the **FP20 IT Help Desk Analysis Challenge 8**. It is provided in a workbook containing two sheets:

• **Tickets:** 97,498 records with 10 fields.

• **IT Agents:** 50 records with 6 fields. 

🔗 [Link to dataset](https://fp20analytics.com/datasets/)



## Business Questions

• On which days of the week do we experience the highest volume of IT tickets?

• Is ticket inflow evenly distributed, or are there peak workload periods?

• Which System Request Categories and Issue Types generate the most tickets?

• Are there recurring issues that account for a majority of support requests?

• What percentage of tickets meet the Service Level Agreement (SLA) benchmark?

• Which categories or issue types are most likely to breach SLA compliance?

• Are delays linked to specific days, request types, or agents?

• How are tickets distributed among support agents?

• Which agents resolve tickets most efficiently?

• Are there gaps in workload allocation that affect team performance?

• How can insights from ticket analysis help the IT Department allocate resources better?

• What steps can be taken to improve SLA compliance and reduce delays?

• Which recurring issues should be prioritized for process or system improvements?



## Tools & Methodology

## Tools Used:

• Power Query for data cleaning, transformation, and preparation.

• Power BI for building interactive dashboards and visualizing insights.

• DAX (Data Analysis Expressions) to create calculated measures and apply custom business logic.

• Data modeling in Power BI to optimize performance and maintain relational integrity.

## Methodology:

## Data Cleaning and Preparation:

• Assigned correct data types to all fields.

• Transformed the dataset as needed.

• Split the Severity field into two columns: Severity and Severity Category.

• Split the Priority field into two columns: Priority and Priority Category.

## Exploratory Analysis:

• Analyzed ticket inflow by days to identify workload distribution.

• Grouped System Request Categories with Issue Types to detect high-frequency issues.

• Evaluated Agent Performance based on workload and resolution speed.

• Designed an SLA Compliance Benchmark to measure tickets resolved within defined service targets. 

## Visualization (Power BI):

• Developed interactive dashboards with filters for category, issue type, and agent.

• Built KPIs for SLA compliance % and average resolution time.

• Created charts to visualize ticket trends and agent comparisons.



## Key Insights 

• **Ticket Growth (2016–2020):** Total tickets increased from 13,051 to 29,088. % SLA Compliance Met fluctuated but remained generally steady.

• **Ticket Volume by Category:** System Request had the highest total tickets (~39,002), with IT Request contributing 75% of issue types, Normal accounting for 90.89% in Severity, and High for 36.7% in Priority. Hardware Request had the lowest ticket volume across all years.

• **SLA Compliance Met:** Login Access had the highest compliance across issue type, severity, and priority (~99.4%) from 2016–2020.

• **Tickets Closed Same Day:** Login Access had the highest percentage of same-day closures (~78.03%), while System had the lowest (~3.10%).

• **SLA Compliance Breach:** Hardware had the highest SLA breach rate, and Login Access had the lowest.

• **Average Resolution Time:** Hardware tickets took the longest to resolve (avg. 8 days), while Login Access was mostly resolved the same day.

• **Average Satisfaction Rate:** Despite fast resolution, Login Access had the lowest average satisfaction (~4.09).



## Dashboard 





## Limitation

• **Missing Temporal Patterns:** The dataset lacked timestamps, limiting the analysis of ticket trends by time of day.

• **Limited Agent Information:** The IT Agents sheet contained minimal details, which restricted deeper analysis of agent performance factors such as experience, role, or workload capacity.



## Recommendations 

• **Optimize Resource Allocation:** Adjust staffing levels based on ticket volume patterns by day to ensure timely responses during peak periods.

• **Address Recurring Issues:** Focus on high-frequency issue types, especially within the System Request category, to reduce overall ticket volume and improve efficiency.

• **Ensure Proper Staff Training**: Provide targeted training and segment certain staff to specialize in handling specific issue types, improving resolution efficiency and expertise.

• **Improve SLA Compliance:** Monitor categories with high SLA breaches, such as Hardware Requests, and implement process improvements to reduce delays.

• **Enhance Agent Performance:** Redistribute workload to balance efficiency across all agents.

• **Track Temporal Patterns:** Collect timestamps for tickets to analyze trends by time of day and improve response planning.

• **Increase Satisfaction:** Investigate factors affecting satisfaction for fast-resolved tickets, such as Login Access, and refine processes to improve user experience.

• **Optimize Ticket Submission:** Implement alerts and automated triggers for critical or recurring issues to ensure faster detection and resolution.


