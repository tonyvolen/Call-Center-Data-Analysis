# Call-Center-Data-Analysis


## Table of Contents 

- [Project Objective](#project-objective)
- [Dataset Used](#dataset-used)
- [Questions (KPIs)](#questions-kpis)
- [Dashboard Link](#dashboard-link)
- [Steps Followed](#steps-followed)
- [Dashboard](#dashboard)
- [Project Insights](#project-insights)
- [Answered Calls](#answered-calls)
- [Resolved calls](#resolved-calls)
- [Average Speed of Answer](#average-speed-of-answer)
- [Average Customer Satisfaction](#average-customer-satisfaction)
- [Agent Statistics](#agent-statistics)
- [Conclusion](#conclusion)
- [Recommendations](#recommendations)


## Project Objective


The goal of this project is to design an interactive and detailed Power BI dashboard that clearly showcases all relevant Key Performance Indicators (KPIs) and metrics from the call centre dataset. This dashboard will deliver valuable insights into the performance of the customer service team, emphasizing crucial areas such as customer satisfaction, call handling efficiency, and agent performance.


## Dataset used


- <a href = "https://github.com/tonyvolen/Call-Center-Data-Analysis/blob/main/01%20Call-Center-Dataset.xlsx">Dataset</a>


## Questions (KPIs)


- what is the overall customer satisfaction ?
- what is the overall calls answered/abandoned ?
- How many calls by time ?
- what is the average speed of answer by agents ?
- what is the agent’s performance quadrant ie average handle time (talk duration) vs calls answered ?

  ## Dashboard Link


- <a href = "https://github.com/tonyvolen/Call-Center-Data-Analysis/blob/main/Call%20Center.pbix">View Dashboard</a>



## Steps Followed


- Load data into Power BI Desktop, dataset is a csv file.
- Verified data for any missing values and anomalies and sort out the same.
- Made sure data is  consistent and clean with respect to data types , data format and values used.
- Used DAX to create calculated measures for KPIs such as Total number of answered calls, Average talk duration and total number of resolved calls.
- Visual filters (Slicers) were added for Three fields named "Agent", "Topic" and "Date".
- In the Report view, I selected and customized appropriate visualizations from the Visualizations pane to effectively represent the KPIs. This process involved tailoring each visualization to accurately display the data, ensuring clarity and alignment with the project's objectives
  



  ## Dashboard




 ![Call Center 3_3_2025 11_57_36 AM](https://github.com/user-attachments/assets/55096a67-684b-469f-b866-373a0f76c131)










## Project Insights 

### Answered Calls


I utilized a doughnut chart to visualize the distribution of total calls, revealing that 81.08% were answered, while 18.92% were abandoned. This indicates that approximately 19% of incoming calls were terminated by customers before reaching an agent, which is a critical metric for assessing customer service efficiency. A high call abandonment rate can suggest issues such as long wait times or inadequate staffing, potentially leading to decreased customer satisfaction.

  


A snapshot of answered calls(Y/n).


![Answered calls](https://github.com/user-attachments/assets/0c86d138-6112-4fb5-804f-b9672e49173a)



I employed a stacked column chart to visualize the total number of calls answered over a three-month period. In January, the data revealed 1,455 answered calls and 317 abandoned calls. February showed 1,298 answered calls and 318 abandoned calls, while March recorded 1,301 answered calls and 311 abandoned calls.

Upon assessment of call abandonment rate for each month, we obtained the following results:


- January:  17.9%
- February: 19.7%
- March:  19.3%

  
These figures indicate that, on average, approximately 19% of calls were abandoned each month.


A snapshot of number of calls per month




![Number of call per month](https://github.com/user-attachments/assets/3989004f-b006-4408-bc57-4f3540f529ec)





### Resolved calls


I employed a doughnut chart to visualize the distribution of total calls, revealing that 72.92% were resolved, while 27.08% remained unresolved. This indicates that approximately 27% of customer inquiries or issues required follow-up interactions, which can impact customer satisfaction and operational efficiency. A high unresolved call rate may suggest challenges in resolving customer issues on the first contact, potentially leading to increased operational costs and decreased customer satisfaction. Improving the resolution rate is crucial for enhancing customer experience and reducing the need for repeat contacts.


A snapshot of Resolved calls(Y/n).



![Resolved calls](https://github.com/user-attachments/assets/ff50e5b1-971a-4e12-8616-7fb7393bd787)






### Average Speed of Answer


Upon visualizing the average speed of answering calls, I found that it was 67.52 seconds. This metric indicates the average duration customers wait before their calls are answered by an agent. Industry standards typically aim for an average speed of answer (ASA) between 20 to 30 seconds.Therefore, an ASA of 67.52 seconds is significantly higher than the recommended benchmark, suggesting that customers are experiencing longer wait times than ideal. Extended wait times can lead to increased customer frustration and higher call abandonment rates, potentially impacting overall customer satisfaction. Addressing this issue may involve optimizing staffing levels, improving call routing processes, or enhancing the efficiency of the interactive voice response (IVR) system to reduce wait times. 

Snapshot of Average Speed of answer


![Average speed of answer](https://github.com/user-attachments/assets/73543ebe-7dbf-4d84-ad06-9397908183ce)






###  Average Customer Satisfaction


An analysis of the average customer satisfaction score revealed a rating of 3.40, falling short of the target of 4.50. This indicates that, on average, customers were neither satisfied nor dissatisfied, suggesting a neutral perception of the service provided. The satisfaction scale ranged from 1 to 5, with 1 representing 'extremely dissatisfied' and 5 representing 'extremely satisfied'. 


The minimum satisfaction score recorded was 1, indicating instances where customers were extremely dissatisfied with the service. Such low satisfaction levels can be indicative of significant service issues, including long wait times, unresolved inquiries, or unhelpful interactions. Addressing these concerns is crucial to enhance customer satisfaction and loyalty.


A snapshot of Average Customer Satisfaction


![Average satisfaction](https://github.com/user-attachments/assets/2657bf5f-68fd-4298-8032-9943fc0167c5)






###  Agent Statistics


I analyzed agent performance statistics and found the following:

- Call Handling: Jim answered the highest number of calls at 536, while Steward answered the fewest at 477.

- Call Resolution: Jim also led in resolved calls with 485, whereas Steward had the lowest at 424.

- Customer Satisfaction: Martha achieved the highest average satisfaction rating of 3.47, while Joe had the lowest at 3.33.

- Response Time: Joe had the highest average speed of answer at 70.99 seconds, while Becky had the lowest average speed of answer at 65.33 seconds.

These findings highlight variations in agent performance across key metrics, indicating areas for potential improvement in call handling efficiency and customer satisfaction.

A snapshot of Agent Statistics


![Agent Statistics](https://github.com/user-attachments/assets/8e2cf4e6-2536-4395-90c1-10fda0925526)




## Conclusion


The analysis of the customer service team's performance has provided valuable insights into key operational metrics. While certain agents, such as Jim, demonstrated high call handling and resolution rates, others, like Steward, exhibited lower performance in these areas. Additionally, the average customer satisfaction score of 3.40 fell short of the target of 4.50, indicating a need for improvement in service quality. The variation in average speed of answer among agents further highlights inconsistencies in response times. 


## Recommendations


1. Implement tools such as Interactive Voice Response (IVR) systems to streamline call routing and reduce wait times, enhancing customer experience. 

2. Offer regular performance reviews and constructive feedback to agents, coupled with coaching sessions to support their professional development. 

3. Establish achievable targets for agents, allowing flexibility to accommodate varying workloads and reduce stress, thereby improving overall performance. 

4.  Develop and promote self-service channels, such as online FAQs and chatbots, to empower customers and reduce call volumes, allowing agents to focus on more complex inquiries.

5. Continuously track metrics like average handle time, first call resolution, and customer satisfaction scores to identify areas for improvement.
