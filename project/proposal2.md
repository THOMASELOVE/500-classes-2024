# Project Proposal, Draft 2 for Spring 2024

## General Notes

- Please check Canvas for additional feedback from Leila and myself.
- In many cases, I have adjusted your title to improve it, and/or to meet the 80 character limit. Use this version of the title, or another I will like better that remains at a maximum of 80 characters.
- The next project-related deliverable is the [project update](https://thomaselove.github.io/500-2024/proj500.html#the-project-update) due Tuesday 2024-04-02 at 9 AM to Canvas. Some of you did an update as part of the second draft, for which I am grateful, but you'll need to submit a revised one by the April deadline.
- Don't miss the [analysis tips](https://thomaselove.github.io/500-2024/proj500.html#analysis-tips) within our project instructions.
- In preparing your **presentation**, follow [the outline and advice](https://thomaselove.github.io/500-2024/proj500.html#the-presentation) provided in the project instructions, please. Your slides and abstract need to be posted to our **Shared Drive** by Noon on the day **before** your presentation.

## Table of Contents

The [schedule of project presentations is found here](https://github.com/THOMASELOVE/500-classes-2024/blob/main/project/schedule.md).

1. [Sara Alqahtani](#sara-alqahtani)
2. [Naji Ayyash](#naji-ayyash)
3. [John Barron](#john-barron)
4. [Seth Bauer](#seth-bauer)
5. [Chris Benson](#chris-benson)
6. [Jesse Chen](#jesse-chen)
7. [Sid Dugar](#sid-dugar)
8. [Ava Fan](#ava-fan)
9. [Lent Mantshonyane](#lent-mantshonyane)
10. [Marie Masotya](#marie-masotya)
11. [Morgan McLoughlin](#morgan-mcloughlin)
12. [Lydia Mitchell](#lydia-mitchell)
13. [Hala Nas](#hala-nas)
14. [Anya Nazarenko](#anya-nazarenko)
15. [Anthony Orsino](#anthony-orsino)
16. [Aman Pande](#aman-pande)
17. [Justin Robinson](#justin-robinson)
18. [Sam Rodgers-Melnick](#sam-rodgers-melnick)
19. [Miza Salim Hammoud](#miza-salim-hammoud)
20. [Akhil S.G.](#akhil-sg)
21. [Sriram Satyavolu](#sriram-satyavolu)
22. [Karlo Toljan](#karlo-toljan)

### Sara Alqahtani

Sara Alqahtani | Cybersecurity Breaches, Corporate Governance and Operational Performance
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 13) 2024-04-18 from 10:45 to 11:10 AM
*Colleagues* | None
*Format* | Word/PDF
*Research ?* | 1. How do cybersecurity breaches affect the likelihood of leadership changes within companies? <br /> 2. What is the impact of cybersecurity breaches on the effectiveness of internal and disclosure controls?
*Outcome* | 1. Leadership change (binary) within a year of a breach (**but how do you measure that in non-breach companies?**) <br /> 2. Control Effectiveness (binary) within a year of a breach (**but how do you measure that in non-breach companies?**)
*"Treated"* | 876 companies that have experienced at least once cybersecurity breach
*"Control"* | 92395 companies which have not experienced a cybersecurity breach
*Covariates* | Revenue, Net Income, Book Value, Total Assets, Altman Z-score indicator of distress, Beneish M-score indicator of earnings manipulation risk, Market capitalization, Stock price, significant change in audit fees (**most are specified as one year prior to the breach, which again leaves me wondering how you assess this for the "untreated" group.**)
*Data Source* | Audit Analytics 2000-Feb 2024 records
*Also...* | -

[Back to Top](#table-of-contents)

### Naji Ayyash

Naji Ayyash | High air quality and its impact on physical and mental health
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 14) 2024-04-25 from 8:30 to 8:55 AM
*Colleagues* | None
*Format* | Word/PDF
*Research ?* | Do counties with 85th percentile good air days or higher have fewer age-adjusted potential years of life lost and average reported mentally unhealthy days when compared to those in the 80th percentile and lower?
*Outcome* | 1. Age-adjusted potential years of life lost per 100,000 people (quant) <br /> 2. Average # of reported mentally unhealthy days per month (quant)
*"Treated"* | 147 counties with air quality in the top 15% of counties (good air day 92.58% of the time or more)
*"Control"* | 789 counties with air quality in the bottom 80% of counties (good air day 91.23% of the time or more)
*Covariates* | 11 covariates from CHR 2020 and 2021, Outcomes from CHR 2023. **You need to verify the years when the data were actually gathered, not the years when they were included in CHR. To do so, you need to look at each year's Analytic Data Documentation. The 2023 report shows Poor Mental Health Days [obtained from BRFSS in 2020](https://www.countyhealthrankings.org/health-data/county-health-rankings-measures). The Years of potential life lost measure in 2023 actually is derived from data in 2018-2020. So your covariates need to (at the least) be measured no earlier than 2018, and ideally not after 2017, and so that might require data reported even earlier than in CHR 2020 or 2021.**
*Data Source* | County Health Rankings in various years and EPA Air Quality System for 2018
*Also...* | -

[Back to Top](#table-of-contents)

### John Barron

John Barron | Lung Transplant Survival in Veterans of the US Armed Forces
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 15) 2024-05-02 from 10:25 to 10:50 AM
*Colleagues* | Yes, 4
*Format* | Quarto (thanks!)
*Research ?* | How does overall survival from the time of lung transplant among veterans transplanted through the VA transplant program compare to that of non-veterans that underwent transplant through non-VA programs? **You aren't just doing matching, so you shouldn't have a research question that implies that you are just doing matching.**
*Outcome* | 1. Overall survival (time to event, with censoring) <br /> 2. Reintubation with 72 hours of transplant (binary)
*"Treated"* | 268 veterans who received their transplant through one of three VA-associated centers
*"Control"* | 2200 non-veterans who received their transplant somewhere else
*Covariates* | More than two dozen, gathered in a table 1 nicely. **You should probably adjust the labels on EducationStatus from 1-6 to something more meaningful.**
*Data Source* | UNOS via CCF
*Also...* | This wasn't actually the time for the Project Update. That comes on April 2. I'm grateful for the effort, though.

[Back to Top](#table-of-contents)

### Seth Bauer

Seth Bauer | Vasopressor Cessation Order in the De-escalation Phase of Septic Shock
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 15) 2024-05-02 from 9:25 to 9:50 AM
*Colleagues* | Yes, 1
*Format* | Quarto (thanks!)
*Research ?* | Do adults with septic shock receiving concomitant norepinephrine and vasopressin have a shorter subsequent duration of vasopressors when vasopressin is ceased first, compared to when norepinephrine is ceased first?
*Outcome* | Duration of time a patient received a vasopressor infusion after the first of the two drugs is ceased (quant)
*"Treated"* | 101 subjects where norepinephrine was ceased first
*"Control"* | 216 subjects where vasopressin was ceased first
*Covariates* | More than two dozen. **As Seth has already figured out, the unique categorical identifier for the hospital of admission with 31 categories isn't going to be a good thing to put in your propensity score.**
*Data Source* | eICU-CRD via PhysioNet
*Also...* | -

[Back to Top](#table-of-contents)

### Chris Benson

Chris Benson | Income inequality and Infant mortality in US counties
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 14) 2024-04-25 from 8:55 to 9:20 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)

### Jesse Chen

Jesse Chen | Hypertension and Non-Alcoholic Fatty Liver Disease (NAFLD) Among Non-Obese US Adults
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 12) 2024-04-11 from 8:35 to 9:00 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)

### Sid Dugar

Sid Dugar | Do early echocardiograms during sepsis and septic change outcomes?
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 14) 2024-04-25 from 9:55 to 10:20 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)

### Ava Fan

Ava Fan | Imaging extranodal extension (iENE) as a prognostic factor in HPV+ oropharyngeal cancer
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 13) 2024-04-18 from 8:30 to 8:55 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)

### Lent Mantshonyane

Lent Mantshonyane | The causal effect of tobacco smoking and biomass smoke on TB disease
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 13) 2024-04-18 from 9:20 to 9:45 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)

### Marie Masotya

Marie Masotya | Asthma and School Absenteeism in Children on Medicaid in Cuyahoga County
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 15) 2024-05-02 from 9:00 to 9:25 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)

### Morgan McLoughlin

Morgan McLoughlin | Maternal Depression and Parent-Training Participation and Engagement
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 12) 2024-04-11 from 9:25 to 9:50 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)

### Lydia Mitchell

Lydia Mitchell | Health insurance and premature death in US adults
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 14) 2024-04-25 from 10:45 to 11:10 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)

### Hala Nas

Hala Nas | Acute Respiratory Failure and Pneumothorax in Bronchoscopic Lung Volume Reduction
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 14) 2024-04-25 from 10:20 to 10:45 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)

### Anya Nazarenko

Anya Nazarenko | Are men less likely to seek mental health treatment services?
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 13) 2024-04-18 from 10:20 to 10:45 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)

### Anthony Orsino

Anthony Orsino | High School Drug Distribution and Social Health
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 12) 2024-04-11 from 10:00 to 10:25 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)

### Aman Pande

Aman Pande | Interstitial lung diseases and immunosuppressant medications
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 14) 2024-04-25 from 9:20 to 9:45 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)

### Justin Robinson

Justin Robinson | Biventricular Repair across the Spectrum of Atrioventricular Septal Defects (AVSD)
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 13) 2024-04-18 from 9:55 to 10:20 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)

### Sam Rodgers-Melnick

Sam Rodgers-Melnick | Effectiveness of Music Therapy (MT) on Length of Stay and Opioid Utilization
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 15) 2024-05-02 from 10:00 to 10:25 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)

### Miza Salim Hammoud

Miza Salim Hammoud | Gender-Specific Quality of Life in Adults with Congenital Heart Disease (ACHD)
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 13) 2024-04-18 from 8:55 to 9:20 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)

### Akhil S.G.

Akhil S.G. | Telemedicine vs. Closing Time
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 12) 2024-04-11 from 9:00 to 9:25 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)

### Sriram Satyavolu

Sriram Satyavolu | Food Insecurity and Depression Among U.S. Adults
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 12) 2024-04-11 from 10:25 to 10:50 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)

### Karlo Toljan

Karlo Toljan | Posterior reversible encephalopathy syndrome (PRES) and immunosuppressant history
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 15) 2024-05-02 from 10:25 to 10:50 AM
*Colleagues* | 
*Format* | 
*Research ?* | 
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)
