# 500 Class 08: 2024-03-07

Today's class begins at 9 AM in WRB 1217.

[Main Website](https://thomaselove.github.io/500-2024/) | [Calendar](https://thomaselove.github.io/500-2024/calendar.html) | [Syllabus](https://thomaselove.github.io/500-syllabus-2024) | [Canvas](https://canvas.case.edu) | [Data/Code](https://github.com/THOMASELOVE/500-data) |  [Sources](https://github.com/THOMASELOVE/500-sources) | For help, email
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :------: | :-----------: 
links for everything | deadlines | expectations | zoom, submissions | downloads | to read | `500-help` at `case` dot `edu`

## Today's Slides

Class | Date | PDF | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :-------------:
08 | 2024-03-07 | **[Slides 08](https://github.com/THOMASELOVE/500-slides-2024/blob/main/500_slides08.pdf)** | **[Code 08](https://github.com/THOMASELOVE/500-slides-2024/blob/main/500_slides08.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

## Announcements

1. The [Calendar](https://thomaselove.github.io/500-2024/calendar.html) has been rearranged so that March is at the top, and all of the OSIA and Project deadlines have been included, with your name identifying when your work is to be submitted and presented.
2. Next week (March 11-15) is CWRU Spring Break.
    - There are no TA office hours on 2024-03-11 or 2024-03-13, and no class on 2024-03-14.
    - Our next class (Class 09) will be held on Thursday 2024-03-21.
3. Refer to our [OSIA Schedule page](https://github.com/THOMASELOVE/500-osia-2024/tree/main), to verify your presentation and submission deadlines for OSIA.
    - Our first presentations will be at our next class (2024-03-21) and involve Sid, Hala and Sriram as first readers, and Jesse, Aman and Marie as second readers. Be sure that the six of you meet [all deadlines and specifications for submitting your work](https://thomaselove.github.io/500-2024/osia.html#presentation-submission-details-for-the-in-class-talks).
    - In particular, the first reader slides (Sid, Hala, Sriram) should be on our **Shared Google Drive** in the appropriate folder (`osia / 2024-03-21 (Class 9) Submit OSIA slides for Live Presentations here`) no later than 1 PM on Wednesday 2024-03-20.
    - The second reader slides (Jesse, Aman, Marie) should be on our **Shared Google Drive** in that same folder (`osia / 2024-03-21 (Class 9) Submit OSIA slides for Live Presentations here`) no later than 7:30 AM on Thursday 2024-03-21.
4. [Lab 4](https://thomaselove.github.io/500-2024/lab4.html) is also due (submit to Canvas) at the start of class on Thursday 2024-03-21.
5. The [Project Presentation Schedule is now available](https://github.com/THOMASELOVE/500-classes-2024/blob/main/project/schedule.md). Please note your time and date for submitting materials and for giving your presentations. I expect every student to provide feedback on all projects except their own for the sessions they can attend (there will be no Zoom in the last four classes.)
    - If you are not marked under *Planned Absences* on that page, I expect you to be in WRB 1217 from 8:30 AM until we are finished (see schedule for details.) Your colleagues deserve your attendance and feedback.
6. In-class attendance has been disappointing recently. Do everything you can to make it to class in person after Spring Break, as Zoom will stop being a good option as I get quieter, starting with our next class. Thank you.

## Today's Agenda

Time | Topic(s)
-----------: | :-------------------------------------------------------------------------------------------
9 - 9:30 | Discussion of Announcements, [OSIA setup](https://github.com/THOMASELOVE/500-osia-2024/tree/main) <br /> Comments on Lab 3 from Leila, Project Proposals (draft 2) comments (on **Shared Drive**)
9:30 - 10:10 | (1) Some Extensions to Propensity Matching <br /> (2) Elbadawi A et al. 2021 [Contemporary Revascularization Strategies and Outcomes Among Patients With Diabetes With Critical Limb Ischemia: Insights from the National Inpatient Sample](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Elbadawi%202021.pdf), with [Supplement](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Elbadawi%202021_supplement.pdf) *J Am Coll Cardiol Intv* 14: 664-74. <br /> (3) Tanenbaum Joseph E et al. 2017 [Propensity Matched Analysis of Outcomes and Hospital Charges for Anterior versus Posterior Cervical Fusion for Cervical Spondylotic Myelopathy](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Tanenbaum_2017_extra.pdf) *Clin Spine Surgery*
10:10 - 10:20 | Break
10:20 - 11:00 | Rosenbaum Chapter 7 (Natural Experiments, Discontinuities and Instruments) discussion 

## Additional readings about instruments (and instruments vs. propensity scores) from our [Sources page](https://github.com/THOMASELOVE/500-sources) include: 

- Whitehouse Mark 2007 [Is an Economist Qualified to Solve Puzzle of Autism?](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Whitehouse%202007%20WSJ%20Economics%20and%20Autism.pdf) *Wall Street Journal*
- Posner Micheal A. et al 2001 [Comparing Standard Regression, Propensity Score Matching and Instrumental Variables Methods for Determining the Influence of Mammography on Stage of Diagnosis](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Posner%20et%20al%202001%20Comparing%20Methods%20in%20a%20Mammography%20Study.pdf) *Health Services & Outcomes Research Methodology*
- Stukel Therese A. et al. 2007 [Analysis of Observational Studies in the Presence of Treatment Selection Bias: Effects of Invasive Cardiac Management on AMI Survival Using Propensity Score and Instrumental Variable Methods](https://github.com/THOMASELOVE/500-sources/blob/main/articles/Stukel%20et%20al%202007%20JAMA.pdf) *Journal of the American Medical Association*

## Some Notes on Lab 3 from Leila Hojat

- Most people are consistently doing very well!
- A couple of people are including outcomes in the propensity score - that's never something you can do, ever.
- One person had some very different results due to using the matched sample from the end of lab 2 to start lab 3 instead of the original canc3 dataset 
- Several students struggled with calculating Rubin's rule 2 from the `bal.table` results
- Several students went with the twang ATT weights, and those that provided rationales gave me the impression that they didn't have a good understanding of the effective sample sizes
- Other problems: forgetting to exponentiate and misinterpreting the results, calculating ATE instead of ATT, forgetting to use quasibinomial family
