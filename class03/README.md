# 500 Class 03: 2024-02-01

Today's class was pre-recorded. See your email for the link.

[Main Website](https://thomaselove.github.io/500-2024/) | [Calendar](https://thomaselove.github.io/500-2024/calendar.html) | [Syllabus](https://thomaselove.github.io/500-syllabus-2024) | [Canvas](https://canvas.case.edu) | [Data/Code](https://github.com/THOMASELOVE/500-data) |  [Sources](https://github.com/THOMASELOVE/500-sources) | For help, email
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :------: | :-----------: 
links for everything | deadlines | expectations | zoom, submissions | downloads | to read | `500-help` at `case` dot `edu`

## Today's Slides

Class | Date | PDF | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :-------------:
03 | 2024-02-01 | **[Slides 03](https://github.com/THOMASELOVE/500-slides-2024/blob/main/500_slides03.pdf)** | **[Code 03](https://github.com/THOMASELOVE/500-slides-2024/blob/main/500_slides03.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

![](https://imgs.xkcd.com/comics/confounding_variables.png) from https://xkcd.com/2560

## Announcements

1. Today's class will be recorded and posted so that you can watch it, as soon as Dr. Love can get that done.
2. The Answer Sketch for [Lab 1](https://thomaselove.github.io/500-2024/lab1.html) will be posted to our Shared Drive as soon as possible.
3. **Next Week** My plan for 500 [Class 04](https://github.com/THOMASELOVE/500-classes-2024/tree/main/class04) is to teach it from 9 to 11 AM on Thursday 2024-02-08 but over Zoom. The Zoom link will be sent as a reminder via email and is also available on Canvas. As things stand, I intend to return to regular (in-class) teaching for 500 with Class 05 on Thursday 2024-02-15.

## What should I be working on?

1. Your [OSIA selection](https://thomaselove.github.io/500-2024/osia.html) (due Tuesday 2024-02-06 at 9 AM) - accepted claims [are posted here](https://github.com/THOMASELOVE/500-osia-2024/tree/main).
2. Readings for Class 4: Skim Austin and Mamdani (2006), Normand (2001) and D'Agostino, Jr. (1998) all on our [Sources](https://github.com/THOMASELOVE/500-sources) page.
3. [Lab 2](https://thomaselove.github.io/500-2024/lab2.html), due 2024-02-15 at 9 AM to Canvas.
    - Here are the R packages I used to build my answer sketch for Lab 2, not counting the xfun package which I used only to present the session information. You don't need to use all of these:
        - broom, janitor, mosaic, naniar, tableone, Hmisc, arm, Matching, cobalt, survival, and tidyverse.
4. Get started (if you haven't already) on your first draft of the [Project Proposal](https://thomaselove.github.io/500-2024/proj500.html) (due Tuesday 2024-02-20)

## Using R to do propensity score analysis

The [toy example](https://github.com/THOMASELOVE/500-data/tree/master/toy) and the [lindner example](https://github.com/THOMASELOVE/500-data/tree/master/lindner) will be the focus of Class 04, next week, but you are encouraged to peruse them in advance.

## Today's Agenda

1. Estimating the Propensity Score (Building the Propensity Model)
2. A schematic for propensity matching in a “simple” study
3. Mechanics of Propensity Matching
4. Schematics for other Propensity Methods in “simple” studies
5. An Introduction to The SUPPORT / Right Heart Catheterization Study
6. Lab 1 (How did it go?)
    - The Answer Sketch for Lab 1 will be posted to our Shared Google Drive **by class time**.
  
## References from Today's Class

References posted on our [Sources page](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources)

- D'Agostino Ralph B Jr. 1998 [Tutorial in Biostatistics: Propensity Score Methods for Bias Reduction in the Comparison of a Treatment to a Non-Randomized Control Group](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/D'Agostino%201998%20SIM%20Tutorial%20on%20Propensity%20Scores.pdf) *Statistics in Medicine*
- Connors Alfred F et al. 1996 [The Effectiveness of Right Heart Catheterization in the Initial Care of Critically Ill Patients](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/articles/Connors%20et%20al%201996%20JAMA%20The%20Right%20Heart%20Catheterization%20Study.pdf) *Journal of the American 
- Gum Patricia A Thamailarasan Maran Watanabe Junko et al. 2001 [Aspirin Use and All-Cause Mortality among Patients being Evaluated for Known or Suspected Coronary Artery Disease](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Gum%202001%20JAMA%20Aspirin%20Use%20Propensity%20Analysis.pdf) *JAMA* 2001 286(10): 1187-1194.
- Hirano Keisuke and Imbens Guido W 2001 [Estimation of Causal Effects using Propensity Score Weighting: An Application to Data on Right Heart Catheterization](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Hirano%20and%20Imbens%202001%20Weighting%20in%20RHC.pdf) *Health Services & Outcomes Research Methodology*
- Hirano Keisuke, Imbens Guido W. and Ridder Geert 2003 [Efficient Estimation of Average Treatment Effects Using the Estimated Propensity Score](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Hirano%20Imbens%20Ridder%20Efficient%20Estimation%20of%20ATE.pdf) *Econometrica* 2003, 71(4): 1161-1189. https://doi.org/10.1111/1468-0262.00442.
- Rosenbaum Paul E 2010 [Design of Observational Studies](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Rosenbaum%20PR%202010%20Design%20of%20Observational%20Studies.pdf)
- Rosenbaum Paul E Rubin Donald B 1983 [The Central Role of the Propensity Score in Observational Studies for Causal Effects](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Rosenbaum%20and%20Rubin%201983.pdf) *Biometrika* 1983: 70(1); 41-55.
- Rosenbaum Paul E Rubin Donald B 1984 [Reducing Bias in Observational Studies Using Subclassification on the Propensity Score](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Rosenbaum%20and%20Rubin%201984%20JASA.pdf) *JASA* 1984: 79(387): 516-524.
- Rosenbaum Paul E Rubin Donald B 1985 [Constructing a Control Group Using Multivariate Matched Sampling Methods That Incorporate the Propensity Score](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Rosenbaum%20and%20Rubin%201985.pdf) *The American Statistician* 1985: 39(1): 33-38.
- Rubin Donald B 2001 [Using Propensity Scores to help Design Observational Studies: Application to the Tobacco Litigation](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Rubin%202001%20Tobacco%20Litigation%20article.pdf) *Health Services & Outcomes Research Methodology*
- Rubin Donald B 2004 [On principles for modeling propensity scores in medical research](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Rubin%202004%20editorial%20Pharmacoepidemiology%20and%20Drug%20Safety%20on%20Propensity%20Score%20Principles.pdf) *Pharmacoepidemiology and Drug Safety*
- Weitzen Sherry et al. 2004 [Principles for modeling propensity scores in medical research: A systematic literature review](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Weitzen%20et%20al%202004%20Systematic%20Literature%20Review%20of%20Propensity%20Score%20Usage.pdf) *Pharmacoepidemiology and Drug Safety*
- Weitzen Sherry et al. 2005 [Weaknesses of goodness-of-fit tests for evaluating propensity score models: the case of the omitted confounder](https://github.com/THOMASELOVE/500-classes-2023/tree/main/sources/articles/Weitzen%20et%20al%202005%20Why%20goodness%20of%20fit%20tests%20aren't%20appropriate%20for%20evaluating%20propensity%20score%20models.pdf) *Pharmacoepidemiology and Drug Safety*

Other references in the slides, if you're interested in tracking down further details...

- Brookhart MA Schneeweiss S Rothman KJ Glynn RJ Avorn J Stürmer T Variable selection for propensity score models. *Am J Epidemiol* 2006 Jun 15;163(12):1149-56. doi: 10.1093/aje/kwj149. Epub 2006 Apr 19 [PubMed](https://pubmed.ncbi.nlm.nih.gov/16624967/)
- D'Agostino Jr. RB and Rubin DB Estimating and Using Propensity Scores with Partially Missing Data *JASA* 2000, 95(451): 749-759.
- McCaffrey DF Ridgeway G Morral AR Propensity score estimation with boosted regression for evaluating causal effects in observational studies. *Psychol Methods* 2004 Dec;9(4):403-25. doi: 10.1037/1082-989X.9.4.403. [PubMed](https://pubmed.ncbi.nlm.nih.gov/15598095/)
- Harrell FE *[Biostatistics for Biomedical Research](http://hbiostat.org/bbr/)*, specifically the [BBR Notes (pdf)](http://hbiostat.org/doc/bbr.pdf). 
- Lunceford JK and Davidian M 2004 Stratification and weighting via the propensity score in estimation of causal treatment effects: a comparative study. *Stat Med* 2004 Oct 15;23(19):2937-60. doi: 10.1002/sim.1903. [PubMed](https://pubmed.ncbi.nlm.nih.gov/15351954/).


## And, finally...

Tickets to [Curtains, the musical](https://www.hudsonplayers.com/now-playing), in which I play Christopher Belling, are going very quickly. If you'd like to go, please visit <https://www.hudsonplayers.com/>. I will not be in the show February 2-3 but will be in the show February 9-11, 16-18, 23-24 on Friday and Saturday evenings, but the two Sunday matinees are already sold out.
