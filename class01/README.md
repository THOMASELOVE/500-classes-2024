# 500 Class 01: 2024-01-18

Today's class begins at 8:30 AM in Wolstein Research Building, room 1217.

[Main Website](https://thomaselove.github.io/500-2024/) | [Calendar](https://thomaselove.github.io/500-2024/calendar.html) | [Syllabus](https://thomaselove.github.io/500-syllabus-2024) | [Canvas](https://canvas.case.edu) | [Data/Code](https://github.com/THOMASELOVE/500-data) |  [Sources](https://github.com/THOMASELOVE/500-sources) | For help, email
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :------: | :-----------: 
links for everything | deadlines | expectations | zoom, submissions | downloads | to read | `500-help` at `case` dot `edu`

## Today's Slides

Class | Date | PDF | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :-------------:
01 | 2024-01-18 | **[Slides 01](https://github.com/THOMASELOVE/500-slides-2024/blob/main/500_slides01.pdf)** | **[Code 01](https://github.com/THOMASELOVE/500-slides-2024/blob/main/500_slides01.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

## Welcome to 500!

- Instructor: Thomas E. Love, Ph.D., Professor of Medicine and of Population and Quantitative Health Sciences, CWRU.
- Office Hours: By appointment, after class, or via email. Email address for the class is **500-help at case dot edu**.
- Teaching Assistant: Leila Hojat. Her office hours start next Monday, and are held via Zoom on Mondays and Wednesdays 5 - 6 PM. Details on Zoom office hours are provided in our **Shared Google Drive**.
- Be sure you are registered with SIS for the course. My list of registrants [is posted here](registered.md).

Need help? Contact us with your questions. We want to hear from you!

## Shared Google Drive

You should have access to the **500 Spring 2024 Dr. Love and Students** shared drive. Find it by logging into Google via CWRU and then visiting the Shared Drives section under Google Drive. Let us know at **500-help at case dot edu** if you have any problems.

## References from Today's Class

Articles posted on our [Sources page](https://github.com/THOMASELOVE/500-sources)

- Concato John et al. 2000 [Randomized, Controlled Trials, Observational Studies and the Hierarchy of Research Designs](https://github.com/THOMASELOVE/500-classes-2023/blob/main/sources/articles/Concato%20Shah%20and%20Horwitz%202000%20OS%20vs%20RCTs%20and%20Hierarchy%20of%20Research%20Design.pdf) *New England Journal of Medicine*
- Gum Patricia A Thamailarasan Maran Watanabe Junko et al. 2001 [Aspirin Use and All-Cause Mortality among Patients being Evaluated for Known or Suspected Coronary Artery Disease](https://github.com/THOMASELOVE/500-classes-2023/blob/main/sources/articles/Gum%202001%20JAMA%20Aspirin%20Use%20Propensity%20Analysis.pdf) *JAMA* 2001 286(10): 1187-1194.
- Smith Gordon C S and Pell Jill P 2003 [Parachute use to prevent death and major trauma related to gravitational challenge: Systematic review of randomized controlled trials](https://github.com/THOMASELOVE/500-classes-2023/blob/main/sources/articles/Smith%20and%20Pell%202003%20BMJ%20Parachutes.pdf) *The BMJ*
- STROBE Guidelines are available at <https://www.strobe-statement.org/>.

You might be interested as well in [The Book of Why](http://bayes.cs.ucla.edu/WHY/) by Judea Pearl and Dana Mackenzie in 2018.

Other articles I refer to in the slides, if you're interested in tracking down further details...

- Multiple risk factor intervention trial. Risk factor changes and mortality results. Multiple Risk Factor Intervention Trial Research Group. *JAMA* 1982 Sep 24;248(12):1465-77. [PubMed](https://pubmed.ncbi.nlm.nih.gov/7050440/)
- [USPSTF Grade Definitions](https://www.uspreventiveservicestaskforce.org/Page/Name/grade-definitions) including links to definitions prior to July 2012.
- Veterans Administration Coronary Artery Bypass Surgery Cooperative Study Group. Eleven-year survival in the Veterans Administration randomized trial of coronary bypass surgery for stable angina. *N Engl J Med* 1984 Nov 22;311(21):1333-9. doi: 10.1056/NEJM198411223112102. [PubMed](https://pubmed.ncbi.nlm.nih.gov/6333636/)

## Learning about Quarto (and making the switch from R Markdown)

1. Virtually any code you have written in R Markdown can be run using Quarto instead, by simply switching the file extension from .Rmd to .qmd.
2. It's still worth it to learn about how Quarto works, and why it differs from R Markdown when it does.

Here are some suggestions:

- <https://quarto.org/> is the main website for all things Quarto, will help you get started making the transition, and has a detailed set of guides and references.
    - Here's the start of the [Tutorial, including Hello, Quarto](https://quarto.org/docs/get-started/hello/rstudio.html) that shows you how to use Quarto with RStudio, which is what you'll be doing in this class.
    - This [FAQ for R Markdown users](https://quarto.org/docs/faq/rmarkdown.html) might be a good starting point.
    - Alison Hill wrote a great blog post [We don't talk about Quarto](https://www.apreshill.com/blog/2022-04-we-dont-talk-about-quarto/) which got me started last April.
- [R for Data Science (2nd edition)](https://r4ds.hadley.nz/) has three chapters on [Communication](https://r4ds.hadley.nz/communicate.html) which include sections dedicated to Quarto, Quarto formats and a Quarto workflow.
- YouTube videos discussing Quarto that may be of interest to you include (in no special order):
    - From Tom Mock at Posit (new name of RStudio the company)
        - [Quarto for the Curious](https://www.youtube.com/watch?v=mrvhk2XUfWo) (runs 21 minutes)
        - [Welcome to Quarto workshop](https://www.youtube.com/watch?v=yvi5uXQMvu4) (2 hours 23 minutes)
        - [Beautiful Reports and Presentations with Quarto](https://www.youtube.com/watch?v=hbf7Ai3jnxY) (1 hour 45 minutes)
        - [Create & Publish a Quarto Blog on Quarto Pub in 100 Seconds](https://www.youtube.com/watch?v=t8qtcDyCRFA) (2 minutes).
        - [Reproducible Medical Research with Quarto](https://www.youtube.com/watch?v=KnwQFph3s94) (3 hours 15 minutes)
    - Isabella Velásquez: [Building a Blog with Quarto](https://www.youtube.com/watch?v=CVcvXfRyfE0) (1 hour 13 minutes)
    - Devin Pastoor: [Websites & Books & Blogs, oh my! Creating Rich Content with Quarto](https://www.youtube.com/watch?v=A9QRN4cpsDY) (21 minutes)
    - Frank Harrell: [R Workflow for Reproducible Biomedical Research using Quarto](https://www.youtube.com/watch?v=NCrrN3Al-kw) (1 hour, 2 minutes)
    - Lyndon Walker: [Create beautiful documents with Quarto and R](https://www.youtube.com/watch?v=y5VcxMOnj3M) (29 minutes)
    - Mine Çetinkaya-Rundel: [Hello, Quarto!](https://www.youtube.com/watch?v=YVa5cdkypbw)
    - Ted Laderas on [Quarto/R Markdown: What's Different?](https://www.youtube.com/watch?v=xC6I5OVOnKI) (28 minutes)

## Notes from the 431-432 Sequence

If you need them, the [431 Notes from Fall 2023 are here](https://thomaselove.github.io/431-notes/), and the [432 Notes for Spring 2024 are here](https://thomaselove.github.io/432-notes/).

---

## What Should I Do Before Our Next Class?

1. Be sure you are registered with SIS for the course. My list of registrants [is posted here](registered.md).
2. Please complete our [Welcome to 500 survey](https://bit.ly/500-welcome-2024). You’ll need to log into Google via CWRU to access the survey, which should take about 10 minutes to complete. Please complete the survey as soon as possible, and thanks to those of you who've already done this.
3. Download the software. Install R and RStudio and some necessary R packages on a computer you can control throughout the semester. Details [are available here](https://thomaselove.github.io/500-2024/software.html).
4. Work through [Lab 0](https://thomaselove.github.io/500-2024/lab0.html). Note that there's nothing to turn in here. If you like, you could also get started on [Lab 1](https://thomaselove.github.io/500-2024/lab1.html) which is due on 2024-02-01.
5. Buy the book. During the course, we will read Paul Rosenbaum’s book **Causal Inference**, which is available as an e-book or in paperback for under $15. Please read through Chapter 3 before our next class on 2024-01-25, if you can.
6. Read the other things I've asked you to read in [the Course Calendar](https://thomaselove.github.io/500-2024/calendar.html).
7. Make sure you familiarize yourself with everything [on our website](https://thomaselove.github.io/500-2024/).

If you have questions, visit Office Hours on Monday or Wednesday at 5 PM, or email us at **500-help at case dot edu**.

---

## One Last Thing

I am in a musical called "Curtains" that runs on the weekends in February starting February 2 and running through February 24 at [Hudson Players](https://www.hudsonplayers.com/now-playing), in Hudson, Ohio. I'm always delighted to see anyone I know at any show I do. Please do come if you are interested, and if you are comfortable being around people who are unmasked. 

"Curtains" is a harmonious fusion of Agatha Christie-esque mystery and the razzle-dazzle of golden-age musicals, and was nominated for eight Tony Awards when it opened in 2007, winning for Best Performance by a Leading Actor. The musical is a send-up of backstage murder mystery plots, set in 1959 Boston, Massachusetts, and follows the fallout when Jessica Cranshaw, the supremely untalented star of Robbin' Hood of the Old West is murdered during her opening night curtain call. I play the role of Christopher Belling, the English director of the musical-within-a-musical. Curtains' captivating score and cunning plot will keep you guessing until the final curtain falls. There are some adult themes in this production.

If you'd like to come, that would be great, and all of the information you need to buy tickets (they will **sell quickly**) is available by clicking the "Get Tickets" link at <https://www.hudsonplayers.com/>. Tickets are $15, and $12 for students and seniors. The theater is located at 41 South Oviatt Street, in Hudson, Ohio, about a 40-45 minute drive from the CWRU campus, east and south of Cleveland.

Performances are February 2, 3, 9, 10, 11, 16, 17, 18, 23 and 24, 2024. Friday and Saturday night shows begin at 8 PM, and the two Sunday matinees (Feb 11 and 18) start at 2 PM.

If you wouldn't like to come, that's **100% OK**. I have various professional roles (as a teacher, for example) where I have some nominal control over other people's happiness or work. If you're someone who interacts with me professionally, please feel no obligation to attend a show I'm in. Attending (or not attending) a show I'm in carries no weight with me at all in any professional capacity.
