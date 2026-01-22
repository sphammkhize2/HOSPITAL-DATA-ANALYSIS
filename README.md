**Background Overview**
Massachusetts General Hospital (MGH) generates complex healthcare data spanning clinical, administrative, and financial domains, typically organized across multiple relational tables. This data includes patient encounters, admissions and readmissions, procedures, payer information, and claims, reflecting the full lifecycle of care delivery and reimbursement.

The objective of this multi-table data analysis is to integrate encounter-, procedure-, and claim-level datasets to evaluate admissions and readmissions, payer coverage, and cost structures. Key financial measures analyzed include base costs, base encounter costs, and claim costs, enabling detailed cost attribution by encounter class and payer type.

By linking encounters with procedures and payer data, the analysis supports classification by encounter class and enables assessment of utilization patterns, payer mix, and cost drivers. This integrated approach provides a technical foundation for evaluating care utilization, financial performance, and reimbursement dynamics at Massachusetts General Hospital.

**Executive Summary**

This analysis leverages multi-table healthcare data from Massachusetts General Hospital (MGH) to examine patient utilization, payer coverage, and cost performance across care settings. Relational datasets encompassing encounters, admissions and readmissions, procedures, payer information, and claims are integrated to enable encounter-level and patient-level analysis.

The key performance indicators show that there are 27891 total encounters over the years 2011 - 2022, with total payer coverage of 31.10 million dollars, total base encounter cost of 3.24 million dollars and total claim cost of 101.51 million dollars, as shown below. 

<img width="979" height="95" alt="Image" src="https://github.com/user-attachments/assets/4aea07a7-259f-4955-8a20-578a7af643f9" />

The encounter class category is broken down into different years, to see which encounter class had the most interaction over the years and the aim was to see which year has more encounters and which one performed in contrast.

 <img width="578" height="304" alt="Image" src="https://github.com/user-attachments/assets/d9c16c83-4c56-4216-8afd-80db88da15c2" />


The study focuses on identifying admissions and readmissions across defined encounter classes, while evaluating payer coverage and payer mix and their impact on utilization and reimbursement. Financial metrics including base costs, base encounter costs, and claim costs are analyzed by encounter, procedure, and payer to isolate cost drivers and cost variation. Through finding admissions and readmissions, the analysis showed that 4.13% of encounters were over 24 hours, meaning, those were total admissions out of 27891 encounters.

<img width="273" height="236" alt="Image" src="https://github.com/user-attachments/assets/51664de1-0a5b-47a4-a5e1-648da242e06a" />

Overall, the analysis provides a consolidated view of encounters, procedures, and financial outcomes at MGH, supporting data-driven insights into care utilization, reimbursement patterns, and operational efficiency.

**Structure Overview**
There are multiple tables in the Massachusetts General Hospital (MGH) datasets, and relationships were established within those respective tables

<img width="1455" height="713" alt="Image" src="https://github.com/user-attachments/assets/a4492a7e-a99c-4ee3-8caa-d9a31b341830" />

<img width="1470" height="705" alt="Image" src="https://github.com/user-attachments/assets/3b00a5c2-c187-4580-8ec5-efc7c191e013" />

**Insights and Analysis**
Through analysis in Power BI, some of the trends and insights were drawn to find an in depth analysis of what has happened over the years. 

<img width="1261" height="709" alt="Image" src="https://github.com/user-attachments/assets/61c66f17-835a-4c86-86a9-9c0c57f7db88" />

In the in depth analysis, it was found that an ambulatory encounter was the top among all encounter classes and it was the one with the most costs in the classes. 
Medicaid is one of the top payers in encounters, over the years with an average of 6200 US Dollars on total claim cost.

<img width="1262" height="712" alt="Image" src="https://github.com/user-attachments/assets/6fd8fcff-9ef7-4edb-9ba6-fd6a94e94ab1" />

Combined chemotherapy and Radiation therapy is the top procedure in terms of costs and amount at which it was performed (with a base cost of 5237596 US Dollars)

<img width="1262" height="706" alt="Image" src="https://github.com/user-attachments/assets/fc90afb3-bd7d-4d3a-b281-8105513659f0" />

The in depth analysis revealed the encounters in days  of the week, days of the month as well as months of the year. Out of 974 patients, 154 died over the years, leaving 820 active patients.

**Recommendations**
In this analysis, recommendations were made to be:
1. Improve efficiency and effectiveness of procedures and encounters.
2. Expand in terms of bed and wards, so that more patients can be admitted over time.
3. Improve in terms of affordability and costs so that more people can get access to healthcare facilities.
