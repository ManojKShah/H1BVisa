# H1BVisa Case Study
The H1B is an employment-based, non-immigrant visa category for temporary foreign workers in the United States. For a foreign national to apply for H1B visa, an US employer must offer a job and petition for H1B visa with the US immigration department. This is the most common visa status applied for and held by international students once they complete college/ higher education (Masters, Ph.D.) and work in a full-time positio


**Data Set**

- CASE_STATUS: Status associated with the last significant event or decision. Valid values include “Certified,” “Certified-Withdrawn,” Denied,” and “Withdrawn”.
- EMPLOYER_NAME:Name of employer submitting labour condition application
- SOC_NAME:The Occupational name associated with the SOC_CODE. SOC_CODE is the occupational code associated with the job being requested for temporary labour condition, as classified by the Standard Occupational Classification (SOC) System.
- JOB_TITLE:Title of the job
- FULL_TIME_POSITION:Y = Full Time Position; N = Part Time Position
- PREVAILING_WAGE:Prevailing Wage for the job being requested for temporary labour condition. The wage is listed at annual scale in USD. The prevailing wage for a job position is defined as the average wage paid to similarly employed workers in the requested occupation in the area of intended employment. The prevailing wage is based on the employer’s minimum requirements for the position
- YEAR:Year in which the H1B visa petition was filed
- WORKSITE:City and State information of the foreign worker’s intended area of employment
- lon:Longitude of the Worksite
- lat:Latitude of the Worksite

**Problem Statement**

- Which industry has the most number of data scientist position
- Which top 5 employers file the most petitions each year
- Which are the  job positions along with the number of petitions which have the success rate more than 70%  in petitions and total petitions filed more than 1000
- Which are  employers along with the number of petitions who have the success rate more than 70%  in petitions and total petitions filed more than 1000

**Success Rate Calculation**

`SUCCESS RATE % = (Certified + Certified Withdrawn)/Total x 100 Bottom of Form The dataset has nearly 3 million records.`
