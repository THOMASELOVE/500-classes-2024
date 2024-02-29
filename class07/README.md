# 500 Class 07: 2024-02-29

Today's class begins at 9 AM in WRB 1217.

[Main Website](https://thomaselove.github.io/500-2024/) | [Calendar](https://thomaselove.github.io/500-2024/calendar.html) | [Syllabus](https://thomaselove.github.io/500-syllabus-2024) | [Canvas](https://canvas.case.edu) | [Data/Code](https://github.com/THOMASELOVE/500-data) |  [Sources](https://github.com/THOMASELOVE/500-sources) | For help, email
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :------: | :-----------: 
links for everything | deadlines | expectations | zoom, submissions | downloads | to read | `500-help` at `case` dot `edu`

## Today's Slides

Class | Date | PDF | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :-------------:
07 | 2024-02-29 | **[Slides 07](https://github.com/THOMASELOVE/500-slides-2024/blob/main/500_slides07.pdf)** | **[Code 07](https://github.com/THOMASELOVE/500-slides-2024/blob/main/500_slides07.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

## Announcements

1. **By class time**, I should have posted the Sketch for Lab 3 to our Shared Drive.
2. The complete schedule (including second readers) for OSIA presentations available at [the OSIA Claims page](https://github.com/THOMASELOVE/500-osia-2024/blob/main/README.md).
3. The [Right Heart Catheterization example](https://github.com/THOMASELOVE/500-data/tree/master/rhc) is now complete, including the sensitivity analysis material. (We'll use the 2023 version.) We will discuss this a little today. 
    - The original paper is Connors Alfred F et al. 1996 [The Effectiveness of Right Heart Catheterization in the Initial Care of Critically Ill Patients](https://github.com/THOMASELOVE/500-classes-2023/blob/main/sources/articles/Connors%20et%20al%201996%20JAMA%20The%20Right%20Heart%20Catheterization%20Study.pdf) from the *Journal of the American Medical Association*
4. We will discuss sensitivity analysis for matched samples as our main topic for today's class.
5. Our other topic for today is Rosenbaum *Causal Inference* and its brief Chapter 6 on anticipated counter-claims and quasi-experimental devices, but we may also want to revisit Chapter 5 on sensitivity analysis that we talked about on 2024-03-15, in light of today's discussion.
6. Remember that while we do have class next Thursday, we do not have class on the following Thursday 2024-03-14, due to Spring Break.

## Sensitivity Spreadsheet Information is in our Shared Drive

- The Excel sheet (developed in 2008) is available in our Shared Drive in the Sensitivity Spreadsheet folder.
- The PDF description of what the spreadsheet does (with examples) is also in our Shared Drive in the Sensitivity Spreadsheet folder.

## What Should I Be Working On?

1. [Draft 2 of the Project Proposal](https://thomaselove.github.io/500-2024/proj500.html#the-project-proposal), as well as the [Project Scheduling Form](https://bit.ly/500-project-schedule-2024) (now open) are due on **Tuesday 2024-03-05** by 9 AM. Leila and I will each review these drafts, so that she can (with fresh eyes) potentially identify new concerns that I didn't mention the first time.
    - What is different about the second draft?
        - You'll address the issues I raised in my review of your first draft, to the extent possible. Most of you will be able to get by with minor changes. If I've posed something which you are unable to address, you should at least raise that issue as a potential limitation when writing either the study objective, the planned methodology, or in both places.
        - We hope you will have data by now, so that you can fill in details you might not have had earlier about how many subjects are involved, precisely what your inclusion/exclusion criteria will be, precisely how your outcome (which should be quantitative, binary or time-to-event for this project) and exposure (remember you must have a minimum of 100 subjects in each exposure group) will be defined. If not, we hope you'll at least have more information for the "Getting the Data Set" section.
        - For the most part, we are willing to entertain projects with one or two outcomes, and one exposure. If you suggested more than two outcomes or more than one split into exposure groups, we want to see a final decision on these issues.
        - We want to see a more comprehensive list of covariates you will include in your propensity score model, in particular, and we want to see some logic behind why these are covariates - things knowable and measured before the decision to receive the exposure happens, and (definitely) which pre-date the outcome.
        - If you have questions, please ask them via `500-help at case dot edu` or in office hours next Monday evening.
2. Our final Lab, [Lab 4](https://thomaselove.github.io/500-2024/lab4.html) is due to Canvas by the start of class on 2024-03-21, which is also the first day when we'll be hearing OSIA presentations, and the first day of our class after Spring Break.
3. Spring Break is an excellent time to work on your OSIA presentation, and get going on the remaining elements of the Project.
