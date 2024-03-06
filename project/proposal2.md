# Project Proposal, Draft 2 for Spring 2024

## General Notes

- Please check Canvas for additional feedback from Leila and myself.
- In many cases, I have adjusted your title to improve it, and/or to meet the 80 character limit. Use this version of the title, or another I will like better that remains at a maximum of 80 characters.
- The next project-related deliverable is the [project update](https://thomaselove.github.io/500-2024/proj500.html#the-project-update) due Tuesday 2024-04-02 at 9 AM to Canvas. Some of you did an update as part of the second draft, for which I am grateful, but you'll need to submit a revised one by the April deadline.
- Don't miss the [analysis tips](https://thomaselove.github.io/500-2024/proj500.html#analysis-tips) within our project instructions.
- In preparing your **presentation**, follow [the outline and advice](https://thomaselove.github.io/500-2024/proj500.html#the-presentation) provided in the project instructions, please. Your slides and abstract need to be posted to our **Shared Drive** by Noon on the day **before** your presentation.

## Table of Contents

The [schedule of project presentations is found here](https://github.com/THOMASELOVE/500-classes-2024/blob/main/project/schedule.md).


[Sara Alqahtani](#sara-alqahtani) || [Naji Ayyash](#naji-ayyash) | [John Barron](#john-barron) | [Seth Bauer](#seth-bauer) | [Chris Benson](#chris-benson) | [Jesse Chen](#jesse-chen) 

[Sid Dugar](#sid-dugar) | [Ava Fan](#ava-fan) | [Lent Mantshonyane](#lent-mantshonyane) | [Marie Masotya](#marie-masotya) | [Morgan McLoughlin](#morgan-mcloughlin) | [Lydia Mitchell](#lydia-mitchell) 

[Hala Nas](#hala-nas) | [Anya Nazarenko](#anya-nazarenko) | [Anthony Orsino](#anthony-orsino) | [Aman Pande](#aman-pande) | [Justin Robinson](#justin-robinson) | [Sam Rodgers-Melnick](#sam-rodgers-melnick) 

[Miza Salim Hammoud](#miza-salim-hammoud) | [Akhil S.G.](#akhil-sg) | [Sriram Satyavolu](#sriram-satyavolu) | [Karlo Toljan](#karlo-toljan)

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
*Colleagues* | None
*Format* | Word/PDF
*Research ?* | Do US counties with smaller levels of income inequality have lower infant mortality rates compared to those with higher levels of income inequality? (**Edited a bit by TEL**)
*Outcome* | Infant Mortality based on what is reported in CHR 2023 (**Note: This should not be, in fact, a cross-sectional study, in that your outcome should be measured later than your exposure or covariates.**)
*"Treated"* | 304 counties in the top 25% of county level income inequality (most unequal) based on what was reported in CHR 2021
*"Control"* | 607 counties in the bottom 50% of county level income inequality (least unequal) based on what was reported in CHR 2021
*Covariates* | Outcome from CHR 2023, exposure and 8 covariates taken from CHR 2021 report. **You need to verify the years when the data were actually gathered, not the years when they were included in CHR. The 2023 CHR report shows [Infant Mortality describing data from 2014-2020](https://www.countyhealthrankings.org/health-data/county-health-rankings-measures). The 2021 CHR report (see <https://www.countyhealthrankings.org/sites/default/files/media/document/2021%20Analytic%20Documentation.pdf>) measures income inequality based on data from the American Community Survey in 2015-2019. So that's a problem, right? You either need a new outcome, or you need to find covariates based on a long, long time ago, and CHR data only go back to 2010 - see <https://www.countyhealthrankings.org/explore-health-rankings/rankings-data-documentation/national-data-documentation-2010-2019>.**
*Data Source* | County Health Rankings in various years
*Also...* | 

[Back to Top](#table-of-contents)

### Jesse Chen

Jesse Chen | Hypertension and Non-Alcoholic Fatty Liver Disease (NAFLD) Among Non-Obese US Adults
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 12) 2024-04-11 from 8:35 to 9:00 AM
*Colleagues* | None
*Format* | Word/PDF
*Research ?* | Is hypertension an independent risk factor for NAFLD among non-obese US adults? **I don't really know what you mean by an independent risk factor - ideally we'd be looking at a causal effect estimate here.**
*Outcome* | NAFLD diagnosis (binary) based on whether the US Fatty Liver Index is 30 or higher (index depends on age, race/ethnicity, waist circumference, gamma-glutamyl transferase (GGT) level, fasting insulin level and fasting glucose) **I still don't know why you're not also looking at the actual index as a quantitative outcome.**
*"Treated"* | 699 non-obese subjects with hypertension (mean SBP > 130 or mean DBP > 90 based on three readings.)
*"Control"* | 1215 non-obese subjects without hypertension as defined in the "treated" group
*Covariates* | Survey weights, Sex, BMI, Albumin, Serum Creatinine, LDL and HDL, Alkaline Phosphatase, Blood Urea Nitrogen, Triglyceride, Aspartate Transaminase, Globulin, Alanine Transaminase, Uric Acid, Total Cholesterol. (**except you cannot include both Total Cholesterol and the set of measurements (HDL/LDL/Triglycerides) that make up total cholesterol.) Also, while you are welcome to include the weights as a covariate in your propensity score in Project A, I do not want you to incorporate the survey weights into your models - that will leave you with a difficult-to-manage project. If you want to publish the work later, then work out how to weight in this way after matching after the class.**
*Data Source* | NHANES data in 2015-2016 and 2017-2018
*Also...* | 

[Back to Top](#table-of-contents)

### Sid Dugar

Sid Dugar | Do early echocardiograms during sepsis and septic change outcomes?
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 14) 2024-04-25 from 9:55 to 10:20 AM
*Colleagues* | Yes, 1
*Format* | Word/PDF
*Research ?* | Does performing an echocardiogram early in the course of sepsis and septic shock alter hospital mortality?
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
*Colleagues* | Yes, 2
*Format* | Word/PDF
*Research ?* | 1. Does the presence of iENE lead to increased rates of disease recurrence? 2. Does the presence of iENE lead to worse overall survival?
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
*Colleagues* | Yes, 3
*Format* | Quarto (thanks!)
*Research ?* | 1. What is the causal effect of tobacco smoking on TB disease? <br /> 2. What is the causal effect of exposure to biomass smoke through cooking on developing TB?
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
*Colleagues* | Yes, 4
*Format* | Quarto (thanks!)
*Research ?* | Do children with an active asthma diagnosis meaningfully differ from those without such a diagnosis in (1) chronic school absenteeism (2) preventative care utilization?
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
*Colleagues* | Yes, 3
*Format* | Word/PDF
*Research ?* | 1. Does depression predict decreased likelihood of participating in the Family Check-Up intervention? <br /> 2. Does depression predict decreased engagement time among parents who do participate in the Family Check-Up intervention?
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
*Colleagues* | None
*Format* | Word/PDF
*Research ?* | Does a lack of health insurance for adults living in America change the likelihood of experiencing premature death?
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
*Colleagues* | None
*Format* | Quarto (thanks!)
*Research ?* | Is bronchoscopic lung volume reduction associated with a higher risk of developing post-procedural (1) acute respiratory failure or (2) pneumothorax in adult patients with emphysema undergoing bronchoscopic lung volume reduction, compared to lung volume reduction surgery?
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
*Colleagues* | None 
*Format* | **Both?**
*Research ?* | Are men less likely than women to report seeing a mental health professional in the past year?
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
*Colleagues* | **None listed, but don't you have collaborators on this?**
*Format* | Quarto (thanks!)
*Research ?* | Are high school students with strong social ties to peers meaningfully more or less likely to encounter drugs at school compared to those who lack those ties?
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
*Colleagues* | Yes, 1
*Format* | Word/PDF
*Research ?* | Does treatment with immunosupressant medication in patients with interstitial lung disease other than IPF alter (1) the rate of developing Progressive Pulmonary Fibrosis (PPF) or (2) the trajectory of forced vital capacity?
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
*Colleagues* | Yes, 6
*Format* | Quarto (thanks!)
*Research ?* | Is a biventricular repair strategy more useful in patients diagnosed with unbalanced AVSD as compared to those diagnosed with balanced AVSD?
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
*Colleagues* | Yes, 8
*Format* | Word/PDF
*Research ?* | Are patients who receive at least 2 MT interventions during their hospitalization (1) discharged from the hospital sooner or (2) exposed to less opioid pain medication than similar patients who did not receive MT?
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
*Colleagues* | None
*Format* | Word/PDF
*Research ?* | How does gender influence longitudinal patient-perceived health-related quality of life outcomes (HR-QoL) in adults with congenital heart disease (ACHD) following cardiac surgery?
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
*Colleagues* | Yes, 2
*Format* | Word/PDF
*Research ?* | Does the mode of encounter (telemedicine vs. in-person visit) have a causal effect on the time taken to close a case after the patient leaves?
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
*Colleagues* | None
*Format* | Word/PDF
*Research ?* | Are depression rates similar in US adults who experience low vs. high food insecurity? **You really need to write your research question as a question, that ends with a question mark. All you have here is an objective that I've tried to build into an RQ.**
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
*Colleagues* | Yes, 4
*Format* | Word/PDF
*Research ?* | In adults diagnosed with PRES, is a history of immunosuppression use at the time of diagnosis associated with fewer discharges to home following the hospitalization during which PRES was diagnosed?
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 

[Back to Top](#table-of-contents)
