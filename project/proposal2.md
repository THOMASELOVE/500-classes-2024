# Project Proposal, Draft 2 for Spring 2024

## General Notes

- Canvas may or many not contain additional feedback from Leila and myself at this point.
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
*Leila's <br /> Comments* | Really excellent proposal. I think your covariates are good, not sure what else is available in UNOS but if available it would be helpful to have information on the indication/underlying disease. Consider in particular that the VA will not have any patients with CF, whereas patients with CF might make up a reasonably large proportion of your non-veteran group especially in the younger age range. I actually would exclude CF altogether if you can identify those patients. <br /> You may also want to include the state or center if available, though perhaps more relevant to the outcome than exposure. <br /> For the 2 borderline variables you mention double lung and ischemic time, I think I would err on the side of including in your outcome model only and not in your ps model. <br /> Might be too much for the class assignment, but you mentioned several other outcomes that might be interesting to describe if you plan to publish (which you should). You could also consider rehospitalizations or total days of hospitalization following transplant.

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
*Also...* | I don't see any reason not to treat this time to receive an infusion as quantitative, rather than as a survival (time-to-event) outcome, so long as there is no censoring.
*Leila's <br /> Comments* | thanks for the very well-organized and thorough report. Would it be worthwhile to include the use of other pressors as well as covariates? Eventually you will want to make sure you have good definitions for all your variables, for example how you defined AKI and how you obtained APACHE (mAPACHE from this Fortis paper is a nice tool to be aware of though was validated in the VA https://pubmed.ncbi.nlm.nih.gov/30243204/). It seems more information about hospital diagnosis or concomitant conditions would be helpful but will review more and let you know. Great work. <br /> The main question I have is whether you want to consider a survival analysis rather than linear regression given you are interested in a time to event outcome. Would be interested in Dr. Love's thoughts about this. (**see above**) <br /> If feasible, it would be nice to describe or have a flowchart describing where patients dropped out of the inclusion/exclusion criteria given out of 200k patients only 300 qualified. <br /> I didn't follow why you are excluding death within 3 hours of stopping vasopressor cessation, does this have to do with the half life? May just clarify when you present. <br /> Other than hospital ID and ICU type, do you have any other information about the hospitals? ICU bed count, hospital bed count, hospital setting (urban/ suburban/ rural), hospital type (academic/ community/ women's,/ cancer/VA), region (state/ census region/country if not all US)? Also while you don't plan to include hospital ID in the propensity model, but you can still mention somewhere in your results that your data came from 31 hospitals. Many of your covariates are defined as at the time of first vasopressor cessation. <br /> I do not know the data set but it seems that some of these would be hard to confirm the status of at exactly that time, would make sure to confirm you do have these data. The no chronic health conditions variable seems kind of sketchy and maybe not needed with the other chronic conditions you are including. <br /> Any more collaborators you are planning to include?

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
*Also...* | - 
*Leila's <br /> Comments* | This is an important question and good use of CHR data, though as Dr. Love says you'll need to go back and choose exposure and covariates occurring before the outcome which will likely require using prior CHR data sets. Only other comment is that I would suggest including additional covariates other than the 8 you listed, again ensuring that these were earlier data.

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
*Also...* | Jesse wrote back to discuss why he's not looking at the US FLI, and it's his project, so he's in charge of the plan, but I don't think binarizing NAFLD in this way is an ideal strategy for clinical care, let alone research.
*Leila's <br /> Comments* | This is an interesting association to study and I think you have been thoughtful in how to use NHANES data despite its limitations. I understand your logic for using NAFLD as a binary variable for your primary outcome and agree, though it could be interesting to include the index as a secondary outcome and wouldn't really be any extra work. I noted that there were some minor differences in your inclusion and exclusion criteria and those used in the NAFLI validation study, which is fine but you may want to discuss your rationale if you write this up. Also for publication purposes a reviewer might call you out for using the term hypertension for this cohort which was defined by elevated BPs at one visit, given typically the hypertension diagnosis would be confirmed with ambulatory readings or separate encounters. You could still define your groups the same way but could say something like they meet the hypertension definition BP threshold. <br /> Are there other variables in NHANES that are worth including in the ps model even if they haven't been shown to be associated with your exposure or outcome? Age at least seems worth including, and consider maybe just for purposes of the class assignment experimenting with covariates from other sections of the survey such as self-reported measures, comorbidities, socioeconomic factors, diet, etc. but up to you. <br /> I would probably exclude HCV antibody positive, not just RNA positive given that patients with treated or even spontaneously cleared HCV may still have some level of liver disease.

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
*Outcome* | 1. Overall survival (time to event) and 2. Distant metastasis (time to event)
*"Treated"* | 137 subjects who were iENE-negative
*"Control"* | 284 subjects who were iENE-positive.
*Covariates* | patient demographics (age, sex) and comoboridities (smoking history, and alcohol use status), disease characteristics (oropharynx subsite site, tumor stage, nodal stage). I don’t have other characteristics such as insurance status or zip code available to me in the data (**a shame**).
*Data Source* | CC Head and Neck Cancer registry.
*Also...* | In terms of whether or not to treat an outcome based on time as binary or time-to-event, that really depends as much as anything on how much information you have available to you about times and (in particular) censoring, related to your secondary outcome (distant mets.) How long are these people followed? What do you think?
*Leila's <br /> Comments* | Your research questions don't seem to match your outcomes exactly. Are you interested in disease recurrence or distant mets in addition to overall survival? Also, I'm more used to seeing the outcome as all-cause mortality rather than survival, but maybe this is something in oncology literature I'm not familiar with. Any way for you to get some additional baseline data to include in your ps model? Will review more and let you know if I have additional comments, good work.- Including distant mets as a time to event outcome seems odd to me since I usually consider survival analysis more applicable to situations in which the outcome is expected to occur for most or all patients eventually. Would defer to Dr. Love on this approach vs logistic regression (**see my comments in Also above**).  <br /> Can you clarify whether the iENE negative patients are also ENE negative? I would expect yes given that ENE patients probably have more advanced disease but wanted to confirm. <br /> Do you have the information on whether the iENE was identified by CT vs MRI? I would expect that MRI would be more sensitive and thus may potentially pick up patients earlier. <br />
- Do you have any data regarding other comorbidities? These may affect things like ability to tolerate or be offered treatment or likelihood of developing other complications. Chronic kidney, liver, heart disease would seem important at least.

[Back to Top](#table-of-contents)

### Lent Mantshonyane

Lent Mantshonyane | The causal effect of tobacco smoking and biomass smoke on TB disease
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 13) 2024-04-18 from 9:20 to 9:45 AM
*Colleagues* | Yes, 3
*Format* | Quarto (thanks!)
*Research ?* | 1. What is the causal effect of tobacco smoking on TB disease? <br /> 2. What is the causal effect of exposure to biomass smoke through cooking on developing TB?
*Outcome* | Developed TB disease vs. were latently infected. (**I'm still not sure I understand this - it needs to be clearer.**)
*"Treated"* | 239 subjects with smoking history = "Used to smoke but not currently smoking" or "Is actively smoking"
*"Control"* | 2437 subjects with smoking history "Has never smoked"
*Covariates* | 13 items from the survey that can be used are listed. All are categorical (and most binary) except age, weight and height. **Do not include BMI if you're including both weight and height**.
*Data Source* | 
*Also...* | I really think you should simplify this plan for your Project, and simply **look at one or the other of your two planned exposures**. The problem is that each of them is such a small percentage of the cohort. I have written the treated and control groups above to describe what you've called your primary exposure of interest, although it was confusing because you mislabeled 1, 2 and 3 in section 1.8 (1 and 3 cannot both be non-smokers). Subjects are "index TB cases and their household members/contacts who consented and were enrolled in the Kawempe Community Health TB study between 2002 and 2012 in Kampala, Uganda. A contact/household member was defined as anyone who has spent at least 7 consecutive days with the index case patient in the same household in the preceding 2 weeks before the index TB patients diagnosis." <br /> "Participants were followed for 24 months at which point they were all additionally tested for TB infection using the tuberculin skin test."
*Leila's <br /> Comments* | You describe several different cohorts in your data source. It seems that the LTBI outcome group screened positive at baseline. Is this the case for the TB disease/active TB group as well? In other words, are you excluding the patients that were negative at baseline from your study? And then if the only possible outcomes are TB infection or TB disease, are you also excluding the group who never developed infection (resistors)? <br /> For your exposure, was there no response option for currently smoking? Wouldn't you expect that some of the individuals in the do not smoke group actually do not/have never smoked? If so, it might be worth dropping this group since it may dilute the effect of the exposure. If there is a currently smoking group that isn't mentioned, I would include those. If you do plan to include the do not smoke group, perhaps you could drop the group for a stability analysis at least. <br /> For the biomass exposure, any idea about what the others group might include? How large is this group? Again, I would consider dropping perhaps depending on the size of the group or else doing a stability analysis without this group. <br /> You **definitely** don't want to include height and weight separately if you are including BMI. <br /> Do you have information on other comorbidities which could contribute to increased risk of developing active TB disease? These could include DM, renal disease, on immunosuppressants, chronic lung disease, malignancy. It's ok if not but might consider this a limitation.

[Back to Top](#table-of-contents)

### Marie Masotya

Marie Masotya | Asthma and School Absenteeism in Children on Medicaid in Cuyahoga County
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 15) 2024-05-02 from 9:00 to 9:25 AM
*Colleagues* | Yes, 4
*Format* | Quarto (thanks!)
*Research ?* | Do children with an active asthma diagnosis meaningfully differ from those without such a diagnosis in (1) chronic school absenteeism (2) preventative care utilization?
*Outcome* | (1) Chronic absenteeism (binary: missing more than 10% of school days in a term) (2) Preventative care visit (encounter code Z00.129)
*"Treated"* | 500 children ages 6-12 attending school in Cuyahoga County with at least one Medicaid Claims encounter diagnosis of asthma (J45) during the study period (2021-2022)
*"Control"* | 2000 children ages 6-12 attending school in Cuyahoga County with Medicaid insurance, but who do not have a diagnosis of asthma during the study period
*Covariates* | 26 listed elements, **although I don't understand why you wouldn't use all of them that pre-date the time of exposure in your propensity score. If they are actually covariates, then they should usually be in the propensity model**.
*Data Source* | University Hospitals (UH) Medicaid Claims data and Cuyahoga County administrative data within the Child Household Integrated Longitudinal Data (CHILD) System
*Also...* | Is it clear that chronic abseenteeism is the only interesting outcome - should you in fact also look at percentage of absences as a quantitative variable?
*Leila's <br /> Comments* | I really like the concept of merging these 2 databases and think this will be a great study. I assume you don't know how many of the 9314 patients with asthma in the medicaid database have school records since you don't have that database yet, but assuming you have more than the 500 and 2000 you are looking for, you'll want to specify that you took a random sample. <br /> I was trying to look up additional data that you might want to use from the claims dataset and came across this CDC page that seems like they wrote for you: https://www.cdc.gov/asthma/data-analysis-guidance/medicaid-claims-data.htm. <br /> Additional data points I would be really interested in are asthma controller meds, hospitalizations, non primary care visits, pulmonary or allergy/immunology specialist visits (you noted specialty but not sure if this is any specialists), any more specific asthma diagnoses like severe or persistent, infections especially upper respiratory infections and pneumonia, concomitant chronic conditions especially allergies, eczema, and immune deficiency. You are including prematurity so you might also consider prior diagnosis of bronchopulmonary dysplasia. Finally I would also consider vaccine history other than flu. Again, not sure what's feasible, what you have available, and most of this would be things to consider longer term for publication purposes. <br /> Regarding your outcome, in addition to the binary 10% cutoff it could also be interesting to look at the percentage as a continuous variable. Are there specific established outcomes associated with the 10% rate, for example standardized test scores, college acceptance, completing school?

[Back to Top](#table-of-contents)

### Morgan McLoughlin

Morgan McLoughlin | Maternal Depression and Parent-Training Participation and Engagement
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 12) 2024-04-11 from 9:25 to 9:50 AM
*Colleagues* | Yes, 3
*Format* | Word/PDF
*Research ?* | 1. Does depression predict decreased likelihood of participating in the Family Check-Up intervention? <br /> 2. Does depression predict decreased engagement time among parents who do participate in the Family Check-Up intervention?
*Outcome* | (1) Participation in the intervention (more than half of families completed at least one session of the intervention) <br /> (2) Level of engagement in the intervention among those who participate (so the two models require different propensity scores and different samples of families, since in the latter case, we're restricting to families who meet the standard of the first outcome.)
*"Treated"* | about 150 families where Mom is clinically depressed (mom CES-D score of 16 or higher)
*"Control"* | about 200 families where Mom is not clinically depressed
*Covariates* | Seven at the moment. Although all of these seem reasonable, and there are no serious concerns with any of them, I still wish there was more information available to use in this concept.
*Data Source* | The Family Check-Up study - some of the data are in hand.
*Also...* | Is depression assessed prior to the intervention?
*Leila's <br /> Comments* | My main question is when the maternal depression was assessed. I would expect that this probably occurred during the first visit? If so, then you may need to modify the primary outcome since all patients would have included at least one visit. <br /> For the level of engagement, how is this measured? Is this a total visit length? <br /> Any way for you to be able to pull in more covariates for your ps model? Will eventually need more detailed description of some of the covariates you already have, as well, primarily the behavior problems and level of father involvement.

[Back to Top](#table-of-contents)

### Lydia Mitchell

Lydia Mitchell | Health insurance and premature death in US adults
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 14) 2024-04-25 from 10:45 to 11:10 AM
*Colleagues* | None
*Format* | Word/PDF (**you also submitted a Quarto file but not the HTML result of rendering it, which we need to see, and it's insufficient anyway**)
*Research ?* | Does a lack of health insurance for adults living in America change the likelihood of experiencing premature death?
*Outcome* | Age-adjusted years of premature death (at the county level) - although I think this is actually a ratio
*"Treated"* | County with a level of insurance in the top 25% of eligible counties
*"Control"* | County with a level of insurance in the bottom 50% of eligible counties
*Covariates* | **None specified** in either the Word/PDF or Quarto file.
*Data Source* | County Health Rankings, but as noted below, you will need to pull earlier CHR data for your exposure and covariates than you use for your outcome, and you need to review the CHR documentation to determine the years in which various measures are collected for each report.
*Also...* | This wasn't actually the time for the Project Update. That comes on April 2. I'm grateful for the effort, though. You probably want to change the heading on page 2-4 of your update.
*Leila's <br /> Comments* | Biggest issue I see is that you are not going to be able to use the 2023 data set alone with these variables. The 2023 report collected premature death data between 2018 and 2020, and the uninsured data came from 2020. You'll need to refer back to an earlier report and use the uninsured county level data from then if that is going to be your exposure. You might also want to get some of your other covariates from earlier reports as well. <br /> Otherwise it looks like you talked with Dr. Love about identifying specific treatment and control groups by including a high uninsured rate group and a low uninsured rate group, which sounds fine. I would like to see a stronger rationale for the exposure and the outcome. Right now it reads that you are interested in seeing what the exposure does to the outcome and that you wanted to pick things that could be compared across states, but that doesn't tell us why you think these are meaningful. Also we need a specific list of covariates that you plan to include in the propensity model. There are many more to include than only the 4 you mentioned (household income, employment, food insecurity, obesity). <br /> It feels odd to say in your research question that there may be an increased or decreased likelihood of premature death; maybe rephrase as something like: Are US counties with a greater proportion of uninsured adults associated with having a higher rate of age-adjusted premature death? <br /> Refer to the word "data" as plural (i.e., "the data are" instead of "the data is") <br /> Your primary exposure is high level uninsured status, not percentage of adults that are uninsured <br /> I would not say that "the project will resemble an observational, population-based descriptive study." This is an observational study and you are doing more than just descriptive analysis.

[Back to Top](#table-of-contents)

### Hala Nas

Hala Nas | Acute Respiratory Failure and Pneumothorax in Bronchoscopic Lung Volume Reduction
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 14) 2024-04-25 from 10:20 to 10:45 AM
*Colleagues* | None
*Format* | Quarto (thanks!)
*Research ?* | Is bronchoscopic lung volume reduction associated with a higher risk of developing post-procedural (1) acute respiratory failure or (2) pneumothorax in adult patients with emphysema undergoing bronchoscopic lung volume reduction, compared to lung volume reduction surgery?
*Outcome* | (1) Acute respiratory failure (binary) (2) pneumothorax (binary) **over what period of time**?
*"Treated"* | 243 subjects who received Bronchoscopic lung volume reduction (BLVR)
*"Control"* | 253 subjects who received surgical lung volume reduction (LVRS)
*Covariates* | Age, sex, race, insurance type, teaching hospital status, hospital size, hospital ownership, hospital region, patient’s income quartile, year of the procedure and presence of chronic respiratory failure.
*Data Source* | National Inpatient Sample via HCUP from AHRQ for 2018-2020.
*Also...* | This wasn't actually the time for the Project Update. That comes on April 2. I'm grateful for the effort, though. Hala has responded in detail to several of Leila's comments already on Canvas, and thanks for that. Your subtitle misspells the word "from" as "form", and you've misspelled HIPAA as HIPPA in section 5.7 and maybe elsewhere.
*Leila's <br /> Comments* | Interesting study, nice diagrams. What is the time frame in which you are evaluating the occurrence of the outcomes of interest? Would time to event outcomes be helpful here instead of looking at them as binary? Any collaborators? 

[Back to Top](#table-of-contents)

### Anya Nazarenko

Anya Nazarenko | Are men less likely to seek mental health treatment services?
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 13) 2024-04-18 from 10:20 to 10:45 AM
*Colleagues* | None 
*Format* | Both? (proposal is Word/PDF, some code in Quarto)
*Research ?* | Are men less likely than women to report seeing a mental health professional in the past year?
*Outcome* | Seen a mental health professional in the past year? (binary)
*"Treated"* | 1195 male participants in NHANES
*"Control"* | 1305 female participants in NHANES
*Covariates* | Age in years (continuous), Race (6 categories), Marital status (3 categories), Education level (5 categories), Country of birth (US or not), Household food security category (4 categories), Ever received SNAP/Food Stamps (binary categorical), Income/Poverty index (3 categories), General health condition (5 categories), Health insurance status (binary categorical), Ever had a drink of any kind of alcohol, Sampling weights (**I would definitely try to include some additional quantitative covariates, and (especially) a measure of self-reported overall health, and also Leila's suggestions below.**)
*Data Source* | NHANES 2017-2020
*Also...* | It's fine to incorporate the sampling weight as a covariate included in the propensity score model, but I would not, for this project, incorporate the sampling weights into either your matched or double robust outcomes analyses.
*Leila's <br /> Comments* | Cool conceptual model. You use both sex and gender in the report, need to specify which one you mean especially given that this is the specific exposure of interest. I think Dr. Love will not want you to use the sampling weights but will let him comment (see **Also above**. Agree with your comments about the timeline but seems you did your best to mitigate this. I will review more and let you know if I have additional comments. Good job. <br /> I see country of birth is binary, is this US vs not US? Would consider ethnicity in addition to race. Other variables could be interesting to include for example regarding access to care, other preventative care.

[Back to Top](#table-of-contents)

### Anthony Orsino

Anthony Orsino | High School Drug Distribution and Social Health
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 12) 2024-04-11 from 10:00 to 10:25 AM
*Colleagues* | **None listed, but don't you have collaborators on this?**
*Format* | Quarto (thanks!)
*Research ?* | Are high school students with strong social ties to peers meaningfully more or less likely to encounter drugs at school compared to those who lack those ties?
*Outcome* | If students have ever been offered, sold, or given illegal drugs on school property. This question is ordinal multi-categorical, but will likely be binarized for the purposes of this project. 
*"Treated"* | Whether or not an individual feels like they are able to talk to a friend about their feelings at least most of the time
*"Control"* | No strong social ties in that regard.
*Covariates* | **You don't want to use all 300+ variables in your propensity score. You'll need to select 10-30 of them as covariates for your model once you have the codebook.**
*Data Source* | Youth Risk Behavior Survey (YRBS)
*Also...* | Need to get the codebook as quickly as possible, so you can move on to identifying the final outcome, exposure details and selecting covariates. Please let us know by the Monday after break if you still do not have this information.
*Leila's <br /> Comments* | It might be nice interesting to include a proposed DAG/conceptual framework, maybe for publication purposes (even though **Dr. Love never understands them.**) There are so many potential competing factors here which the 304 variables might be helpful in sorting out, but at the same time I think it's unlikely that including all of them would be the best strategy. I would take the time to make sure you understand what they all mean, how they are derived, their utility for your study.

[Back to Top](#table-of-contents)

### Aman Pande

Aman Pande | Interstitial lung diseases and immunosuppressant medications
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 14) 2024-04-25 from 9:20 to 9:45 AM
*Colleagues* | Yes, 1
*Format* | Word/PDF
*Research ?* | Does treatment with immunosupressant medication in patients with interstitial lung disease other than IPF alter (1) the rate of developing Progressive Pulmonary Fibrosis (PPF) or (2) the trajectory of forced vital capacity?
*Outcome* | (1) Development of PPF (binary) during the study period. This is defined based on the percentage decline of forced vital capacity (FVC) over time. (2) The change in the FVC (measured in Liters) over time.
*"Treated"* | 261 subjects with ILD who are treated with immunosuppressant therapy
*"Control"* | 640 subjects (**note: you'll be using all the subjects, not just a 1:1 matched group, in your double robust analysis**) with ILD who did not receive immunosuppressant medications
*Covariates* | About two dozen, plus five potential co-interventions that occur over the course of follow-up care.
*Data Source* | CC Interstital Lung Disease (ILD) registry
*Also...* | This wasn't actually the time for the Project Update. That comes on April 2. I'm grateful for the effort, though. Aman has already responded to most of Leila's concerns expressed below. Thank you for being responsive.
*Leila's <br /> Comments* | I am mainly concerned about your primary outcome being binary for the development of PPF if the follow-up time might be different for different patients, since there are no requirements for when the second PFT has to occur. For example, it doesn't sound like there would be a way to distinguish a patient who only had a second PFT at 3 months who is likely going to be PPF negative from a patient whose follow-up was a year or more later. Also, you mention that the rate of developing fibrosis in your cohort is estimated as 25-35%, but over what time frame? Seems that the window might be relatively short for the time period you are considering. Your secondary outcome may address some of these issues, but I think this would assume that development of fibrosis is linear. In other words, it's ok if you think that you can use the change in FVC over 3 months to extrapolate the change at 12 months, but you would be assuming that the change occurs at a steady rate over that time and this may be hard to justify unless you have studies to support this. <br /> Given that you have a relatively large cohort still, would it be possible to identify patients who had follow-up PFTs within a similar time frame, for example 1 year, and focus on those?

[Back to Top](#table-of-contents)

### Justin Robinson

Justin Robinson | Biventricular Repair across the Spectrum of Atrioventricular Septal Defects (AVSD)
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 13) 2024-04-18 from 9:55 to 10:20 AM
*Colleagues* | Yes, 6
*Format* | Quarto (thanks!)
*Research ?* | Is a biventricular repair strategy more useful in patients diagnosed with unbalanced AVSD as compared to those diagnosed with balanced AVSD?
*Outcome* | Death during the study period (binary)
*"Treated"* | 45 infants diagnosed with unbalanced AVSD
*"Control"* | 563 infants diagnosed with balanced AVSD (**almost definitely going to want to look at a 1:k with k>1 match**)
*Covariates* | patient age, BSA (expressed in meters-squared), sex (male/female), institutional diagnosis (balanced, unbalanced AVSD), actual surgical strategy (no surgery, single ventricle repair, biventricle repair, pulmonary artery banding, hybrid, or palliative shunt), prmtr (born premature), avvi (atrioventricular valve index), total area (of common AV valve), asd size, cavv_o (common AV valve in open position), aoannulus (aortic annulus), sinusofv (sinus of valsalva), pstjse (sinotubular junction), minor index, cpbtime (cardiopulmonary bypass time), and cclampt (cross-clamp time)
*Data Source* | CHSS Cohort study describing infants diagnoses with AVSD at <3 months, with AV and VA concordance, in 2012-2021.
*Also...* | This wasn't actually the time for the Project Update. That comes on April 2. I'm grateful for the effort, though. <br /> In your propensity model at the moment you have a warning that `fitted probabilities numerically 0 or 1 occurred` and **that is a serious red flag that you'll need to work out**. Contact us if you need help.
*Leila's <br /> Comments* | Agree that all-cause mortality makes more sense. If part of your research question is to determine if age, BSA, sex, baseline echo variables influences outcomes, perhaps you would want to include these in your outcome model so that you can provide odds ratios. I'm a little confused by your groups. Is the exposure the surgery or the presence of balanced vs unbalanced AVSD? It sounds like maybe you want the exposure to be surgery, and that AVSD type is something you want to include as a covariate in your ps model, and likely also in your outcome model. Though you might run into some challenges with your propensity model with only 45 in the unbalanced AVSD group (that is, the unbalanced group might be unbalanced :/ ). <br /> Other questions/comments: Would help to provide more background on the difference between balanced and unbalanced AVSD. Do you have more specifics about premature, as in number of weeks premature? You mention genetic abnormalities such as Down syndrome, so might be helpful to include this information if you have it. Any other complications or exposures during pregnancy that would be important to include or mention? For example nicotine use or cocaine use, excessive bleeding or other labor complications? Is the timing of surgery important, or does the procedure usually occur around the same time if surgery is decided on?

[Back to Top](#table-of-contents)

### Sam Rodgers-Melnick

Sam Rodgers-Melnick | Effectiveness of Music Therapy (MT) on Length of Stay and Opioid Utilization
:--------------: | :--------------------------------------------------------------------------------------------------
*Presenting* | (Class 15) 2024-05-02 from 10:00 to 10:25 AM
*Colleagues* | Yes, 8
*Format* | Word/PDF
*Research ?* | Are patients who receive at least 2 MT interventions during their hospitalization (1) discharged from the hospital sooner or (2) exposed to less opioid pain medication than similar patients who did not receive MT?
*Outcome* | (1) Length of Stay (quant), (2) average MME of opioid medications per day in hospital (quant)
*"Treated"* | X hospital admissions where the patient received at least 2 MT interventions
*"Control"* | 2500 - X hospital admissions where the patient received 0 MT interventions
*Covariates* | Demographics, SDOH, Clinical Characteristics
*Data Source* | MT EHR data at UH, approved by the UH IRB.
*Also...* | You've misspelled "Planned" in your heading for "Planned Methods". We'll discuss the details further on the 15th, as you note.
*Leila's <br /> Comments* | I would consider additional factors which may affect the outcomes if you can get the data, for example dispo (dispo to SNF vs home might delay discharge), primary team, duration of hospital stay at the time of the exposure, primary reason for hospitalization. Also I think you would want to know about any chronic pain regimen if you haven't already accounted for that. Great work, looking forward to your findings.

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
*Leila's <br /> Comments* | Interesting topic, I haven't seen much about gender in this context. I noticed you go back and forth between talking about sex and gender, but it is critical that you decide which one you are talking about and describe how you define it, given that this defines your exposure. Unless the patients are specifying their gender in the survey, I'm guessing this is sex, also since it says the PROMIS score is compared to age and sex matched controls. I don't fully understand your outcome or what the table is showing; what is location tested? Are these the mean scores for the full cohort across all pre and post-op surveys, or a specific survey? If this came from a publication or presentation, please reference. Doing a longitudinal analysis seems out of the scope of the class assignment, consider if you want to aggregate the results or choose one of the time points. But if you have repeated measures it would be great to analyze those for publication purposes. <br /> It sounds like you have a study group you are working with, so please identify these collaborators. <br /> For your final portfolio (**although this may or may not make your slides**) it will be good to get more info on how the survey was distributed, were there reminders, incentives, etc. Note that a survey embedded in the mychart app/website is likely going to be more likely to be accessed and completed by some patient populations vs others, so there is going to be some bias to acknowledge. <br /> It would be great to have more information on the surgical indication as well as prior surgeries and original congenital defect (it may be that left, right, or complex shunt lesion is the only information you have available). If you don't have the data regarding prior surgeries, it might be worth discussing since I would imagine adults with CHD undergoing cardiac surgery for the first time would be a very different patient population from adults who had one or more surgeries as a child or infant.

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
*Leila's <br /> Comments* | I am interested in this study given that I do a fair amount of telehealth myself. As we discussed extensively in office hours, please clarify all the variables that Dr. Love is mentioning and describe the setting of this practice a little better. Also work with your colleague/mentor/collaborator on seeing if there is a way to consolidate the ICD codes perhaps into the most common cardiac diagnoses and non-cardiac diagnoses, and clarify if this is just the first or primary visit code (I neglected to mention that at least in our EMR, you do specify the primary diagnosis for outpatient visits, so I bet this is the code they are using for this column). I like your idea of including provider-described affinity for telehealth if you can get that information, and not including the specific provider ID. Actual visit length might be questionable to include in your ps model but at least could go in your outcome model. Make sure to remove the zip codes since this is considered PHI and since you just are using it to calculate distance which you said your collaborator could do for you. If you plan to write this up using a longer time frame, it's probably worth keeping the year and month or quarter since all of this sort of early-post-COVID timing. Looking forward to your results and happy to help further.

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
*Leila's <br /> Comments* | I think you have chosen an interesting exposure and outcome. For exposure, you could compare "no food insecurity" to "any food insecurity" by comparing the FFS to the other 3 groups, or alternatively you might consider comparing "high" and "low" food security by grouping FFS with MFS and LFS with VLFS. It may depend on how many individuals fall into these groups. Either way, this will allow you to have clear control and treatment groups. Agree with including PHQ9 as a quantitative outcome. Also agree with including many more covariates available in NHANES; let me know if you are having trouble coming up with these. Would note the limitations of NHANES we have discussed previously which is that it's difficult to say with certainty that your ps model covariates occurred before the exposure and your exposure occurred before the outcome given the cross sectional nature of the data.


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
*Leila's <br /> Comments* | My main concern is how you are defining immunosuppressant, as there are a wide range of drugs that fit into this category, each of which also may have important nuances to consider. For example corticosteroids would have different potencies and different durations of exposure, certain immunosuppressants may have very specific targets and have less of an impact, others may have broad affects on whole cell lines, some have important additional toxicities to consider other than the effect on the immune system alone. Finally, I think the indication for the immunosuppression would be important. Transplant status is included which is a major important category but would also want to know about malignancy, autoimmune conditions. Also other comorbidities might be relevant, for example any cardiac history that could contribute to underlying vascular insufficiency to the brain. <br /> I recognize you may not have most or even any of these data, which is fine but you might need to discuss as a limitation (unless you feel these are not relevant). <br /> When you present, it will also help to have more context. Were there prior studies suggesting that immunosuppression might affect PRES outcomes? <br /> If you have it, I think it would be worth including admission BP.

[Back to Top](#table-of-contents)
