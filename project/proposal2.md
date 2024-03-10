# Project Proposal, Draft 2 for Spring 2024

## General Notes

- Please check Canvas for additional feedback from Leila and myself.
- In many cases, I have adjusted your title to improve it, and/or to meet the 80 character limit. Use this version of the title, or another I will like better that remains at a maximum of 80 characters.
- The next project-related deliverable is the [project update](https://thomaselove.github.io/500-2024/proj500.html#the-project-update) due Tuesday 2024-04-02 at 9 AM to Canvas. Some of you did an update as part of the second draft, for which I am grateful, but you'll need to submit a revised one by the April deadline.
- Don't miss the [analysis tips](https://thomaselove.github.io/500-2024/proj500.html#analysis-tips) within our project instructions.
- In preparing your **presentation**, follow [the outline and advice](https://thomaselove.github.io/500-2024/proj500.html#the-presentation) provided in the project instructions, please. Your slides and abstract need to be posted to our **Shared Drive** by Noon on the day **before** your presentation.

## Table of Contents

The [schedule of project presentations is found here](https://github.com/THOMASELOVE/500-classes-2024/blob/main/project/schedule.md).

Class 12 (2024-04-11) Speakers: [Jesse Chen](#jesse-chen) || [Akhil S.G.](#akhil-sg) || [Morgan McLoughlin](#morgan-mcloughlin) || [Anthony Orsino](#anthony-orsino) || [Sriram Satyavolu](#sriram-satyavolu)

Class 13 (2024-04-18) Speakers: [Ava Fan](#ava-fan) || [Miza Salim Hammoud](#miza-salim-hammoud) || [Lent Mantshonyane](#lent-mantshonyane) || [Justin Robinson](#justin-robinson) || [Anya Nazarenko](#anya-nazarenko) || [Sara Alqahtani](#sara-alqahtani)

Class 14 (2024-04-25) Speakers: [Naji Ayyash](#naji-ayyash) || [Chris Benson](#chris-benson) || [Aman Pande](#aman-pande) || [Sid Dugar](#sid-dugar) || [Hala Nas](#hala-nas) || [Lydia Mitchell](#lydia-mitchell) 

Class 15 (2024-05-02) Speakers: [Karlo Toljan](#karlo-toljan) || [Marie Masotya](#marie-masotya) || [Seth Bauer](#seth-bauer) || [Sam Rodgers-Melnick](#sam-rodgers-melnick) || [John Barron](#john-barron) 

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
*Also...* | After class, we discussed how to adjust this work, and Sara wrote back with some details on a revised plan, which I think will work.
*Leila's <br /> Comments* | This sounds like a study that would generate interest across many groups, though I think it would be more compelling to know what types of companies are being included. Is there a sector variable that could be included? <br /> I am unclear about the time point you are using for the companies in the control group that did not experience a breach. Is there a variable you could include that would somehow allow you to match companies at a similar time point, maybe something like year company began submitting data? Also seems that you would want to include the year as a covariate since broader economic or political changes may play a role in your outcomes. <br /> This doesn't fix your problem regarding choosing a starting timepoint for controls, but I wonder if it makes more sense to look at your outcomes as time-to-event. In other words, do companies experiencing security breach change leadership sooner? I guess I don't know the significance of 1 year, maybe it is meaningful from a business perspective to look at it this way.

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
*Also...* | I've spoken to Naji, and he's done what we want him to do, but just needs to make that clearer in the later versions of this work.
*Leila's <br /> Comments* | Agree with Dr. Love that you want to be sure that the covariates to be included in your PS model were collected before your outcomes and at the same time or (perhaps ideally) before your exposures. Would it help to use the older county health rankings reports? Otherwise you might consider dropping the YPLL variable and looking for a different physical outcome measure like poor physical health days that came from 2020 data. Otherwise, I don't think it would hurt to include as many variables as you can in your PS model within the constraints of timing, since I think you could come up with arguments for how most of these could be connected.

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
*Leila's <br /> Comments* | Really excellent proposal. I think your covariates are good, not sure what else is available in UNOS but if available it would be helpful to have information on the indication/underlying disease. Consider in particular that the VA will not have any patients with CF, whereas patients with CF might make up a reasonably large proportion of your non-veteran group especially in the younger age range. I actually would exclude CF altogether if you can identify those patients.
You may also want to include the state or center if available, though perhaps more relevant to the outcome than exposure. <br />
For the 2 borderline variables you mention double lung and ischemic time, I think I would err on the side of including in your outcome model only and not in your ps model. <br /> Might be too much for the class assignment, but you mentioned several other outcomes that might be interesting to describe if you plan to publish (which you should). You could also consider rehospitalizations or total days of hospitalization following transplant.

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
*Leila's <br /> Comments* | 

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
*Leila's <br /> Comments* | 

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
*Also...* | -
*Leila's <br /> Comments* | 

[Back to Top](#table-of-contents)

### Sid Dugar

Sid Dugar | Do early echocardiograms during sepsis and septic change outcomes?
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 14) 2024-04-25 from 9:55 to 10:20 AM
*Colleagues* | Yes, 1
*Format* | Word/PDF
*Research ?* | Does performing an echocardiogram early in the course of sepsis and septic shock alter hospital mortality?
*Outcome* | (1) In-hospital mortality (binary), (2) Time in ICU
*"Treated"* | 654 subjects where an echocardiogram was performed within 24 hours after admission to Medical ICU with sepsis or septic shock (**have I got this description of the "treated" and "control" groups right?**)
*"Control"* | 1702 subjects where no echocardiogram was performed during the entire hospitalization after admission to MICU with sepsis or septic shock
*Covariates* | Age, Sex, APACHE III Score, History of heart failure, cirrhosis, diabetes and Malignancy, maximum lactate level in first 24 hours of sepsis or septic shock, maximum vasopressor dosage in first 24 hours, presence of bacteremia, Race and Ethnicity, Primary Care Physician (yes/no)
*Data Source* | CC Sepsis Registry
*Also...* | -
*Leila's <br /> Comments* | Can you clarify whether this is TTE only or could be TEE? Also are these all formal echo performed by a tech and read by cardiology or bedside by provider as well? I think there are a lot more of the sepsis bundle components that you will want to include like fluid resuscitation, early antibiotics, labs drawn in time, etc. <br /> My main concern as mentioned above is the missing variables that would be considered important for sepsis related outcomes. Do you have data available regarding whether the 1-hour sepsis bundle components were completed? If not it's ok but would recognize this as a limitation. <br /> Do you have data regarding whether patients were ventilated or not? <br /> Your background makes it seem as if you doubt that echo should make a difference. This is fine, but would clarify if your hypothesis is that echo does not have a benefit on mortality. <br /> Could you clarify if your bacteremia variable is bacteremia identified within 24 hours of ICU admission? <br /> If you have information on history of other cardiac conditions other than HF this might be worth including. For example if a patient has a history of CAD, they might have been more likely to get an echo performed but not necessarily because of sepsis

[Back to Top](#table-of-contents)

### Ava Fan

Ava Fan | Imaging extranodal extension (iENE) as a prognostic factor in HPV+ oropharyngeal cancer
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 13) 2024-04-18 from 8:30 to 8:55 AM
*Colleagues* | Yes, 2
*Format* | Word/PDF
*Research ?* | 1. Does the presence of iENE lead to increased rates of disease recurrence? <br /> 2. Does the presence of iENE lead to worse overall survival?
*Outcome* | 
*"Treated"* | 
*"Control"* | 
*Covariates* | 
*Data Source* | 
*Also...* | 
*Leila's <br /> Comments* | 

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
*Leila's <br /> Comments* | 

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
*Leila's <br /> Comments* | 

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
*Leila's <br /> Comments* | 

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
*Also...* | This wasn't actually the time for the Project Update. That comes on April 2. I'm grateful for the effort, though.
*Leila's <br /> Comments* | 

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
*Also...* | This wasn't actually the time for the Project Update. That comes on April 2. I'm grateful for the effort, though.
*Leila's <br /> Comments* | 

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
*Leila's <br /> Comments* | 

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
*Leila's <br /> Comments* | 

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
*Also...* | This wasn't actually the time for the Project Update. That comes on April 2. I'm grateful for the effort, though.
*Leila's <br /> Comments* | 

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
*Also...* | This wasn't actually the time for the Project Update. That comes on April 2. I'm grateful for the effort, though.
*Leila's <br /> Comments* | 

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
*Leila's <br /> Comments* | 

[Back to Top](#table-of-contents)

### Miza Salim Hammoud

Miza Salim Hammoud | Gender-Specific Quality of Life in Adults with Congenital Heart Disease (ACHD)
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 13) 2024-04-18 from 8:55 to 9:20 AM
*Colleagues* | **None? Really?**
*Format* | Word/PDF
*Research ?* | How does gender influence longitudinal patient-perceived health-related quality of life outcomes (HR-QoL) in adults with congenital heart disease (ACHD) following cardiac surgery?
*Outcome* | Derived from a set of HR-QoL (Health-Related Quality of Life) questionnaires, specifically PROMIS 10 Mental and PROMIS 10 Physical subscales. **What does Location Tested mean in your table? Why are there footnote symbols in the table?**
*"Treated"* | 198 females who underwent congenital heart surgery (**at the Cleveland Clinic?**) and have a diagnosis of ACHD and completed the HR-QoL questionnaires (**when did they do the questionnaires? Before or after the surgery, or a mix?**)
*"Control"* | 378 males who underwent congenital heart surgery and have a diagnosis of ACHD and completed the HR-QoL questionnaires
*Covariates* | Age, Race, Hispanic ethnicity, Hospital Length of Stay, Diagnosis (**are these yes/no or a multi-categorical set of options?**), Cardiopulmonary bypass time, BMI (**and also BMI categories?**), **Area Deprivation Index state deciles and national percentiles?** Comorbidities, Insurance Type (**may need to collapse**), Family History of CAD, Ejection fraction at discharge, Pre-operative NY Heart Functional Classification (I-IV).
*Data Source* | CC Retrospective Chart Review involving patients from January 2022 to (**through?**) September 2023 (**STS CHSD registry role?**)
*Also...* | **Where's your description of propensity matching in the Methods?** This wasn't actually the time for the Project Update. That comes on April 2. I'm grateful for the effort, though. 
*Leila's <br /> Comments* | 

[Back to Top](#table-of-contents)

### Akhil S.G.

Akhil S.G. | Telemedicine vs. Closing Time
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 12) 2024-04-11 from 9:00 to 9:25 AM
*Colleagues* | Yes, 2
*Format* | Word/PDF
*Research ?* | Does the mode of encounter (telemedicine vs. in-person visit) have a causal effect on the time taken to close a case after the patient leaves?
*Outcome* | Closing time after patient in cardiology has "checked out" (in hours) - mean appears to be 96, with a **minimum of -5 (?)** and maximum of 914
*"Treated"* | In-person encounter (422 subjects)
*"Control"* | Telemedicine encounter (1165 subjects)
*Covariates* | *Patient* information: age, sex, insurance, distance from hospital in miles (**calculated from zipcodes? how do you have this if data are de-identified?**), race, language (**will you have meaningful variation?**) <br /> *Encounter* information: new/recurring visit, appointment scheduled time, duration of patient visit, diagnosis code (**ICD-10? Won't there be multiple codes?**) <br /> *Provider* information: type (nurse, physician, PA), clinician gender (M/F), experience (**via GradYear?**) specialty (**2 categories?**) and clinic ID (unique for each of 80 clinicians - this is **not** something you'll include in a propensity score.) **The thing that is definitely missing is any sense of how the provider feels about technology.**
*Data Source* | A little vague. These are data from some EHR in the Western US on about 80 care providers (**not all physicians**) in a Department of Cardiology over a one-month period (February 2021.)
*Also...* | This wasn't actually the time for the Project Update. That comes on April 2. I'm grateful for the effort, though. **Don't create null and alternative hypotheses - you're estimating an effect size here, and that should be the focus**.
*Leila's <br /> Comments* | 

[Back to Top](#table-of-contents)

### Sriram Satyavolu

Sriram Satyavolu | Food Insecurity and Depression Among U.S. Adults
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 12) 2024-04-11 from 10:25 to 10:50 AM
*Colleagues* | None
*Format* | Word/PDF
*Research ?* | Are depression rates similar in US adults who experience low vs. high food insecurity? **I've tried to build your study into an RQ. A real RQ ends with a question mark.**
*Outcome* | Depression assessed using the PHQ-9, with scores of 10 or greater indicating depression (binary). **I think you should also use PHQ-9 as a quantitative outcome, assuming you have it.**
*"Treated"* | **This is a problem, as I don't know what you're doing. I assume you will derive the exposure from the four categories of food insecurity at the household level that you mention, but you need to (1) specify your "treatment" and "control" groups in terms of subjects, not households, and also (2) tell me how many subjects fall into each of your exposure categories.**
*"Control"* | **See "Treated"**
*Covariates* | 8 (age, sex, race, family poverty-to-income ratio, body mass index, marital status, educational attainment, and smoking status) are listed, **but there are many, many more in NHANES - a more appropriate list could certainly be much more inclusive.**
*Data Source* | NHANES 2017-2020 (pre-pandemic)
*Also...* | You should already have the data in R, if you're using NHANES data. **Do you need help in this regard?**. <br /> **In the methods section, you mention exploring potential effect modification by testing interaction terms. That's beyond the scope of this project. What I don't see is enough (or really any) detailed information about how you're going to use propensity score analyses.**
*Leila's <br /> Comments* | 

[Back to Top](#table-of-contents)

### Karlo Toljan

Karlo Toljan | Posterior reversible encephalopathy syndrome (PRES) and immunosuppressant history
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 15) 2024-05-02 from 10:25 to 10:50 AM
*Colleagues* | Yes, 4
*Format* | Word/PDF
*Research ?* | In adults diagnosed with PRES, is a history of immunosuppression use at the time of diagnosis associated with fewer discharges to home following the hospitalization during which PRES was diagnosed?
*Outcome* | Disposition to home vs. all other (AR, SNF, LTAC, death) - binary
*"Treated"* | 69 subjects who were on immunosuppression medications immediately prior to the hospitalization in which PRES was diagnosed
*"Control"* | 200 subjects who were not on immunosuppression medications immediately prior to the hospitalization in which PRES was diagnosed
*Covariates* | Age, Sex, Race (**This will need to be collapsed, probably just into White vs. Other, and do you have Hispanic ethnicity as well?**), Hypertension, Diabetes, Tobacco Use, Obesity (**can this be actual BMI rather than just BMI >= 30?**), Transplant Receipient, Seizure (**during hospitalization - can this be a covariate?**), MRI Brain with Ischemic Stroke, MRI Brain with Hemorrhagic Stroke - **ideally, you'd like to keep your covariates as granular as possible**. **Is type of insurance available?**
*Data Source* | EHR data forming a retrospective cohort of adults hospitalized at CC in 2008-2018 with a PRES diagnosis
*Also...* | -
*Leila's <br /> Comments* | 

[Back to Top](#table-of-contents)
