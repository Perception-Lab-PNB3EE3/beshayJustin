# Pre-registration Template

Adapted from <https://osf.io/preprints/metaarxiv/epgjd> into markdown
format.

<details>

-   [Study Information](#study-information)
    -   [1. Title](#1-title)
    -   [2. Authors](#2-authors)
    -   [3. Description](#3-description)
    -   [4. Hypotheses](#4-hypotheses)
-   [Design Plan](#design-plan)
    -   [5. Study type](#5-study-type)
    -   [6. Blinding](#6-blinding)
    -   [7. Is there any additional blinding in this
        study?](#7-is-there-any-additional-blinding-in-this-study-)
    -   [8. Study design](#8-study-design)
    -   [9. Randomization](#9-randomization)
-   [Sampling Plan](#sampling-plan)
    -   [10. Existing data](#10-existing-data)
    -   [11. Explanation of existing
        data](#11-explanation-of-existing-data)
    -   [12. Data collection procedures](#12-data-collection-procedures)
    -   [13. Sample size](#13-sample-size)
    -   [14. Sample size rationale](#14-sample-size-rationale)
    -   [15. Stopping rule](#15-stopping-rule)
-   [Variables](#variables)
    -   [16. Manipulated variables](#16-manipulated-variables)
    -   [17. Measured variables](#17-measured-variables)
    -   [18. Indices](#18-indices)
-   [Analysis Plan](#analysis-plan)
    -   [19. Statistical models](#19-statistical-models)
    -   [20. Transformations](#20-transformations)
    -   [21. Inference criteria](#21-inference-criteria)
    -   [22. Data exclusion](#22-data-exclusion)
    -   [23. Missing data](#23-missing-data)
    -   [24. Exploratory analysis](#24-exploratory-analysis)
-   [Other](#other)
    -   [25. Other](#25-other)

</details>

# Study Information

## 1. Title

Silence vs. Sound: Investigating How Background Music and Noise
Influence Study Retention

## 2. Authors

Justin Beshay

## 3. Description

Memory retention is a fundamental aspect of learning, and environmental
factors such as background noise may influence recall accuracy. However,
prior research has produced mixed findings on whether background
noise—particularly music—enhances or impairs memory performance. Some
studies suggest that background music can improve cognitive performance
by enhancing mood, increasing arousal, and reducing stress, which may
facilitate attention and encoding processes (Carr & Rickard, 2016;
Mammarella et al., 2007; Taheri et al., 2022). Others argue that
background music can be distracting, as it competes for attentional
resources needed for memory encoding and retrieval, leading to impaired
recall accuracy (Echaide et al., 2019; Lehmann & Seufert, 2017). Given
these conflicting findings, further research is needed to clarify how
different types of background noise influence memory retention.

One major limitation in the existing literature is the variability in
study designs, including differences in music type, volume, complexity,
and familiarity. For example, studies using instrumental music have
sometimes found no effect or even benefits for memory, whereas music
with lyrics has been shown to disrupt verbal processing tasks (Souza &
Leal Barbosa, 2023). The familiarity of the music may also be a key
factor—highly familiar songs may induce involuntary engagement, such as
singing along or anticipating lyrics, which could increase cognitive
load and reduce memory performance (Chew et al., 2016). Additionally,
the complexity of the music (e.g., fast tempo, unpredictable melodies)
may influence its impact on recall, with high-complexity music likely
being more disruptive than simple, ambient sounds (Gonzalez & Aiello,
2019). These inconsistencies highlight the need for a systematic
investigation that directly compares the effects of different background
noise conditions under controlled experimental conditions.

Another important gap in the literature is the role of individual
differences in study habits. Some students habitually study with music,
while others prefer silence, raising the question of whether Frequent
music listeners are less distracted by background music while studying
compared to those who usually study in silence (Furnham & Strbac, 2002).
If frequent music listeners develop adaptations to studying with noise,
their recall performance may be less negatively impacted than those who
are accustomed to studying in quiet environments. However, this remains
an open question, as relatively few studies have considered study habits
as a moderating variable in memory research when interacting with
music/noise (Christopher & Shelton, 2017).

The present study aims to clarify these mixed findings by systematically
examining how three background noise conditions—silence, white noise,
and music—impact recall accuracy. Specifically, we will test whether
music impairs recall more than silence and white noise, and whether the
effect of music depends on factors such as song familiarity and
complexity. We will also explore whether individual study habits
moderate the effects of background noise on memory, with habitual music
listeners potentially showing greater resistance to distraction.

To address these research gaps, participants will be randomly assigned
to one of three conditions (Silence, White Noise, or Music) and will
study a list of words. After a 10-minute delay, they will complete a
free recall test. Participants in the Music Condition will also rate
their familiarity with the song to assess its potential moderating
effect on recall accuracy.

Findings from this study may have important implications for optimizing
study environments, particularly for students who listen to music while
studying. If background noise impairs memory performance, educators may
need to reconsider best practices for study settings. Alternatively, if
specific types of music enhance memory retention, targeted use of
background noise could serve as a cognitive aid in educational contexts.

## 4. Hypotheses

1.  Primary Hypothesis (Directional): Participants who study in the
    silence condition will have higher recall accuracy compared to those
    in the music and white noise conditions.

2.  Secondary Hypothesis (Directional): Participants in the music
    condition will have lower recall accuracy than those in the silence
    and white noise condition, but the effect will depend on the
    complexity and familiarity of the music.

-   **High-complexity music** (e.g., fast-paced instrumental music,
    songs with unpredictable melodies, or multiple layers of sound) will
    impair recall accuracy more than low-complexity music (e.g., slow
    instrumental or ambient tracks).
-   **Familiar music** will be more distracting than unfamiliar music,
    as participants may involuntarily sing along or anticipate lyrics,
    leading to greater cognitive interference with memory encoding and
    retrieval.
-   **Music with lyrics** will be more disruptive to verbal memory tasks
    than instrumental music, as processing lyrics competes with the
    cognitive resources required for studying and recall.

3.  Long-Term Retention Hypothesis (Directional): Participants who study
    in the silence condition will exhibit better long-term retention of
    studied material compared to those in the music and white noise
    conditions.

4.  Interaction Hypothesis: The impact of background noise on recall
    accuracy will vary depending on individual differences in study
    habits (e.g., whether participants frequently listen to music while
    studying).

-   Participants who frequently listen to the same songs while studying
    may experience less distraction from familiar music compared to
    those who typically study in silence.

# Design Plan

## 5. Study type

This study qualifies as an experiment because it involves direct
manipulation of an independent variable—background noise condition—and
measures its effect on a dependent variable, recall accuracy.
Participants will be randomly assigned to one of three conditions
(silence, white noise, or music), ensuring that differences in memory
performance are due to the experimental manipulation rather than
pre-existing individual differences. By controlling for extraneous
variables, such as study time and recall delay, and using a standardized
procedure across conditions, this study allows for causal inferences
about how different types of background noise influence memory
retention. The structured design, with controlled exposure times and a
fixed delay period before recall, makes it a laboratory-style experiment
conducted in a digital setting using jsPsych.

## 6. Blinding

-   [ ] No blinding is involved in this study.

-   [ ] For studies that involve human subjects, they will not know the
    treatment group to which they have been assigned.

-   [ ] Personnel who interact directly with the study subjects (either
    human or non-human subjects) will not be aware of the assigned
    treatments. (Commonly known as “double blind”)

-   [x] Personnel who analyze the data collected from the study are not
    aware of the treatment applied to any given group.

## 7. Is there any additional blinding in this study?

This study is a single-blind experiment, meaning that participants will
be aware of their assigned condition, but the researchers analyzing the
data will not know which condition each participant was in.

Participants must be aware of their assigned condition because the
independent variable—background noise—directly affects their sensory
experience during the study phase. Unlike in pharmaceutical or placebo
studies where conditions can be masked, participants actively hear
either silence, white noise, or music while studying. Since it is
impossible to expose participants to different noise conditions without
them noticing, they are inherently aware of their assigned condition.
However, to prevent potential bias in data analysis, group assignments
(white noise, music, or silence) will concealed from researchers until
all statistical analyses are completed.

## 8. Study design

We have a between-subjects design with one factor (background noise
condition) with three levels: Silence, White Noise, and Music.
Participants will be randomly assigned to one of these conditions, and
recall accuracy will be measured as the percentage of correctly recalled
words. Since each participant experiences only one condition, no
counterbalancing is required.

## 9. Randomization

This study will use block randomization to assign participants to one of
three background noise conditions (silence, white noise, or music).
Block randomization ensures that the number of participants in each
condition remains balanced throughout the study. Each block will contain
an equal number of participants assigned to one of the three conditions.
Random assignment will be implemented automatically using a
randomization function within jsPsych.

# Sampling Plan

## 10. Existing data

-   [x] Registration prior to creation of data: As of the date of
    submission of this research plan for preregistration, the data have
    not yet been collected, created, or realized.

## 11. Explanation of existing data

This study does not use any pre-existing data. All data will be
collected after preregistration, ensuring that confirmatory analyses are
specified before any observations are made. All analyses will be
conducted on newly collected data.

## 12. Data collection procedures

### Population & Recruitment

Participants will be undergraduate students recruited through SONA
McMaster University’s research participation system. Recruitment will be
conducted via SONA study postings, and participants will receive course
credit for their participation.

### Eligibility Criteria

-   Age: 18+  
-   Language: Fluent in English  
-   Hearing: Normal or corrected-to-normal hearing  
-   Device: Must use a computer
-   Completion: Must finish the study in one session; incomplete
    responses will be excluded

### Study Timeline

1.  Informed Consent & Demographics:
    -   Participants provide consent and complete a demographic survey.
2.  Study Phase:
    -   Participants are randomly assigned to one of three background
        noise conditions:
        -   Silence  
        -   White Noise  
        -   Music  
    -   They study a word list.
3.  Delay & Distractor Task:
    -   A 10-minute delay with a neutral distractor task follows.
4.  Recall Test:
    -   Participants recall as many words as possible.
5.  Music Familiarity Rating: (Music condition only)
    -   Participants rate song familiarity on a 1-10 scale.
6.  Debriefing & Credit Allocation:
    -   Participants receive a debriefing statement and SONA credit.

### Data Collection Duration

Data collection will continue until the target sample size (determined
via power analysis) is met.

## 13. Sample size

the target sample size for this study is around 185 participants, with
59 participants per condition (silence, white noise, and music). Since
this is a between-subjects design, each participant will be exposed to
only one condition.

This sample size was determined using a power analysis for a one-way
ANOVA, assuming an effect size of 0.3, a significance level of 0.05, and
a desired power of 0.95. This ensures that the study has sufficient
statistical power to detect meaningful differences between the
conditions.

To account for potential dropouts or incomplete responses we rounded up
from 177 participants (directed from the power analysis) to 185,
slightly more participants than the minimum required. Only participants
who fully complete the study will be included in the final analysis.

## 14. Sample size rationale

``` r
# Load necessary package
options(repos = "https://cran.rstudio.com")  # Set default CRAN mirror
install.packages("pwr")  
```

    ## 
    ## The downloaded binary packages are in
    ##  /var/folders/6r/hs8r3gpd735bllzj7859ndfw0000gn/T//RtmpfFAsej/downloaded_packages

``` r
install.packages("pwr")  
```

    ## 
    ## The downloaded binary packages are in
    ##  /var/folders/6r/hs8r3gpd735bllzj7859ndfw0000gn/T//RtmpfFAsej/downloaded_packages

``` r
library(pwr)
```

    ## Warning: package 'pwr' was built under R version 4.3.3

``` r
# Set parameters
effect_size <- 0.3  # Cohen's f
alpha <- 0.05       # Significance level
power <- 0.95       # Desired power
num_groups <- 3     # Number of groups

# Perform power analysis
sample_size_per_group <- pwr.anova.test(k = num_groups, 
                                        f = effect_size, 
                                        sig.level = alpha, 
                                        power = power)$n
(sample_size_per_group) # = 58.2 so round to 59 participants per group
```

    ## [1] 58.20939

``` r
# Calculate total sample size
total_sample_size <- sample_size_per_group * num_groups

# Print results
print("Sample size per group: 59")
```

    ## [1] "Sample size per group: 59"

``` r
print("Total sample size: 59 x 3 = 177")
```

    ## [1] "Total sample size: 59 x 3 = 177"

## 15. Stopping rule

Sign-ups will remain open on SONA until we reach 185 completed
participants, as determined in #13 and #14 Sample Size.

# Variables

## 16. Manipulated variables

The manipulated variable (IV) in this study is background noise
condition, which has three levels:

1.  Silence Condition – No background noise will be played during the
    study phase. Participants will study in a quiet environment, with
    only system-generated instructions presented.
2.  White Noise Condition – A continuous, non-rhythmic white noise will
    be played at a standardized volume (e.g., 50 dB) throughout the
    study phase. This will be a pre-recorded white noise track that
    remains consistent for all participants.
3.  Music Condition – A song with lyrics will be played at a
    standardized volume (e.g., 50 dB) during the study phase. The song
    will be the same for all participants in this condition to maintain
    consistency.”)

The background noise will be played through their device speakers or
headphones. Participants will not have control over playback

## 17. Measured variables

The primary dependent variable in this study is recall accuracy,
measured as the percentage of correctly recalled words from the studied
word list. Participants will be asked to type all the words they
remember after a 10-minute delay following a distraction task.

Additional measured variables include:

1.  Response Time (Exploratory Measure): The time taken by participants
    to recall and enter words will be recorded to explore potential
    differences in retrieval speed across conditions.
2.  Study Habits (Covariate): Participants will self-report whether they
    typically listen to music while studying, which may moderate the
    effects of background noise on recall accuracy.
3.  Music Familiarity (Exploratory Measure): If assigned to the music
    condition, participants will indicate whether they were familiar
    with the song played.

## 18. Indices

In this study, the primary measure of interest is recall accuracy, which
will be computed as the percentage of correctly recalled words from the
studied list.

``` r
#correct_recalled <- sum(#participant_response %in% study_list)

#total_words <- 20
#recall_accuracy <- (correct_recalled / total_words) * 100
```

Once we collect data from jsPsych, we can determine correctly recalled
words by comparing the participant’s response with the original word
list.

1.  Mean Recall Time Measures how long participants take to recall words
    before submitting their response. This is used to find out if recall
    time is related to recall accuracy

``` r
#total_recall_time <- (final_submission_time - recall_start_time)
```

1.  Music Familiarity (Self-reported familiarity rating (1-10)) Used to
    explore whether familiar music is more distracting than unfamiliar
    music. Participants in the Music Condition will rate their
    familiarity with the song on a Likert scale (1 to 10): 1 = Not
    familiar at all, 10 = Extremely familiar

``` r
#music_familiarity_index <- ifelse(condition == "Music", as.numeric(familiarity_rating), NA)

## (Ensures only participants in the Music Condition have a familiarity score; others get NA.)
```

# Analysis Plan

## 19. Statistical models

We will use a **one-way between-subjects ANOVA** to test the effect of
**background noise** on **recall accuracy**.

-   **Independent Variable (IV):** Background noise condition
    (**Silence, White Noise, Music**)  
-   **Dependent Variable (DV):** Recall accuracy (**percentage of
    correctly recalled words**)

### **Primary Analysis**

-   A **one-way ANOVA** will determine whether background noise
    condition significantly affects **recall accuracy**, testing the
    **Primary Hypothesis** that **participants in the silence condition
    will recall more words** than those in the **music and white noise
    conditions**.
-   **Planned one-tailed t-tests** will compare recall accuracy between
    conditions based on our **directional hypotheses**:
    -   **Silence \> Music** (higher recall accuracy in silence than in
        music).  
    -   **Silence \> White Noise** (higher recall accuracy in silence
        than in white noise).  
    -   **White Noise \> Music** (music impairs recall more than white
        noise).

### **Secondary Analysis**

To examine the **Secondary Hypothesis**, we will explore whether:  
- **Music complexity** affects recall accuracy (e.g., high-complexity
music, such as unpredictable melodies, will be more disruptive).  
- **Music familiarity** moderates recall performance (e.g., familiar
music may be more distracting due to involuntary engagement).  
- **Music with lyrics** impairs recall more than instrumental music, due
to interference with verbal encoding.

These analyses will use **interaction effects** and **correlation
tests** to assess the impact of **familiarity, complexity, and lyrics
presence** in the **music condition** only.

### **Long-Term Retention Hypothesis**

If a **delayed recall phase** is included, we will use
**repeated-measures ANOVA** to test whether participants who studied in
**silence** exhibit **better long-term retention** than those in the
**music and white noise conditions**.

### **Interaction Hypothesis & Exploratory Analyses**

To assess whether **study habits** influence recall performance
(**Interaction Hypothesis**), we will examine:  
- Whether **habitual music listeners** perform differently in the
**music condition** compared to participants who typically study in
silence.  
- Whether **participants who frequently listen to the same songs while
studying** experience less distraction from familiar music.

These relationships will be tested using **moderation analyses** (e.g.,
ANCOVA with study habits as a covariate) and **correlation tests** to
explore how background noise effects vary based on **individual
differences**.

### **Effect Size & Reporting**

-   **Cohen’s *η*<sup>2</sup>** will be reported for ANOVA to quantify
    effect size.  
-   **Cohen’s *d*** will be used for planned pairwise t-tests.  
-   **Correlation coefficients** (*r*) will be reported for
    relationships between music familiarity, complexity, and recall
    accuracy.

All **exploratory findings** will be reported separately and labeled as
such, ensuring transparency in distinguishing between **confirmatory and
hypothesis-generating** analyses.

## 20. Transformations

The data from the effect of noise on recall accuracy dont require
transformations. All variables are in their natural form and suitable
for analysis. Categorical variables will be used as-is, and continuous
variables such as recall accuracy and response time will be analyzed
without normalization, centering, or scaling.

## 21. Inference criteria

Primary Analysis: A one-way ANOVA will be conducted to test for
differences in recall accuracy across the three conditions (silence,
white noise, and music).

Statistical Significance: A p-value threshold of 0.05 (𝛼=0.05) will be
used to determine statistical significance.

Post-hoc Comparisons: Since the hypotheses are directional, planned
one-tailed t-tests will be conducted for pairwise comparisons instead of
Tukey’s HSD.

Effect Size Reporting: Cohen’s 𝜂^2 (eta squared) will be reported for
ANOVA, and Cohen’s 𝑑 will be reported for pairwise comparisons.

One-Tailed Tests: Given the directional nature of the hypotheses, all
t-tests will be conducted as one-tailed tests, predicting that recall
accuracy will be higher in silence than in music/white noise and that
music will have a greater negative effect than white noise.

## 22. Data exclusion

Non-Completion of Key Experimental Phases: - Participants who fail to
complete the study phase (e.g., do not view the full word list) will be
removed. - Participants who do not attempt to recall any words will be
excluded, as their data does not contribute to memory performance
analysis.

Invalid or Non-Compliant Responses: - If participants enter nonsense
words, repetitions, or random keyboard inputs during recall, their data
will be flagged and reviewed for potential exclusion.

Outlier Handling: - Participants with total recall times exceeding three
standard deviations from the mean may be examined to determine if their
data is valid.

## 23. Missing data

Participants who do not complete the recall task (fail to submit any
recalled words) will be excluded from the analysis, as their data would
not contribute to assessing recall accuracy. Additionally, if a
participant does not complete the study phase (e.g., exits before
studying the full word list), their data will also be excluded.

For partial missing data: If a participant recalls some words but does
not submit within the allotted time, their recall accuracy will be
calculated based on the words they provided before timeout.

## 24. Exploratory analysis

Potential exploratory analyses include:

1.  Effect of Study Habits on Recall Accuracy: Participants will
    self-report whether they typically listen to music while studying.
    We will explore whether habitual music listeners perform differently
    in the music condition compared to those who usually study in
    silence.

2.  Impact of Music Familiarity on Recall Performance (Music Condition
    Only): Participants in the music condition will rate their
    familiarity with the song. We will explore whether familiarity
    affects recall accuracy (e.g., whether familiar music is more
    distracting than unfamiliar music).

3.  Individual Differences in Response Time: We will examine whether
    recall speed (total recall time) is associated with recall accuracy
    across conditions, potentially identifying patterns of fast vs. slow
    recallers.

# References

Carr, S. M., & Rickard, N. S. (2016). The use of emotionally arousing
music to enhance memory for subsequently presented images. Psychology of
Music, 44(5), 1145-1157. <https://doi.org/10.1177/0305735615613846>

Chew, A. S.-Q., Yu, Y.-T., Chua, S.-W., & Gan, S. K.-E. (2016). The
effects of familiarity and language of background music on working
memory and language tasks in Singapore. Psychology of Music, 44(6),
1431-1438. <https://doi.org/10.1177/0305735616636209>

Christopher, E. A., & Shelton, J. T. (2017). Individual differences in
working memory predict the effect of music on student performance.
Journal of Applied Research in Memory and Cognition, 6(2), 167–173.
<https://doi.org/10.1016/j.jarmac.2017.01.012>

Echaide, C., del Río, D., & Pacios, J. (2019). The differential effect
of background music on memory for verbal and visuospatial information.
The Journal of General Psychology, 146(4), 443–458.
<https://doi.org/10.1080/00221309.2019.1602023>

Furnham, A., & Strbac, L. (2002). Music is as distracting as noise: The
differential distraction of background music and noise on the cognitive
test performance of introverts and extraverts. Ergonomics, 45(3),
203–217. <https://doi.org/10.1080/00140130210121932>

Gonzalez, M. F., & Aiello, J. R. (2019). More than meets the ear:
Investigating how music affects cognitive task performance. Journal of
Experimental Psychology: Applied, 25(3), 431-444.
<https://doi.org/10.1037/xap0000202>

Lehmann, J. A. M., & Seufert, T. (2017). The influence of background
music on learning in the light of different theoretical perspectives and
the role of working memory capacity. Frontiers in Psychology, 8, 1902.
<https://doi.org/10.3389/fpsyg.2017.01902>

Mammarella, N., Fairfield, B., & Cornoldi, C. (2007). Does music enhance
cognitive performance in healthy older adults? The Vivaldi effect. Aging
Clinical and Experimental Research, 19(5), 394–399.
<https://doi.org/10.1007/BF03324720>

Souza, A. S., & Leal Barbosa, L. C. (2023). Should we turn off the
music? Music with lyrics interferes with cognitive tasks. Journal of
Cognition, 6(1), 24. <https://doi.org/10.5334/joc.273>

Taheri, S., Razeghi, M., Choobineh, A., Kazemi, R., Rasipisheh, P., &
Vali, M. (2022). Investigating the effect of background music on
cognitive and skill performance: A cross-sectional study. Work, 71(4),
871–879. <https://doi.org/10.3233/WOR-213631>

Carr, S. M., & Rickard, N. S. (2016). The use of emotionally arousing
music to enhance memory for subsequently presented images. *Psychology
of Music*, *44*(5), 1145–1157.
<https://doi.org/10.1177/0305735615613846>

Chew, A. S.-Q., Yu, Y.-T., Chua, S.-W., & Gan, S. K.-E. (2016). The
effects of familiarity and language of background music on working
memory and language tasks in singapore. *Psychology of Music*, *44*(6),
1431–1438. <https://doi.org/10.1177/0305735616636209>

Christopher, E. A., & Shelton, J. T. (2017). Individual differences in
working memory predict the effect of music on student performance.
*Journal of Applied Research in Memory and Cognition*, *6*(2), 167–173.
<https://doi.org/10.1016/j.jarmac.2017.01.012>

Echaide, C., Río, D. del, & Pacios, J. (2019). The differential effect
of background music on memory for verbal and visuospatial information.
*The Journal of General Psychology*, *146*(4), 443–458.
<https://doi.org/10.1080/00221309.2019.1602023>

Furnham, A., & Strbac, L. (2002). Music is as distracting as noise: The
differential distraction of background music and noise on the cognitive
test performance of introverts and extraverts. *Ergonomics*, *45*(3),
203–217. <https://doi.org/10.1080/00140130210121932>

Gonzalez, M. F., & Aiello, J. R. (2019). More than meets the ear:
Investigating how music affects cognitive task performance. *Journal of
Experimental Psychology: Applied*, *25*(3), 431–444.
<https://doi.org/10.1037/xap0000202>

Lehmann, J. A. M., & Seufert, T. (2017). The influence of background
music on learning in the light of different theoretical perspectives and
the role of working memory capacity. *Frontiers in Psychology*, *8*,
1902. <https://doi.org/10.3389/fpsyg.2017.01902>

Mammarella, N., Fairfield, B., & Cornoldi, C. (2007). Does music enhance
cognitive performance in healthy older adults? The vivaldi effect.
*Aging Clinical and Experimental Research*, *19*(5), 394–399.
<https://doi.org/10.1007/BF03324720>

Souza, A. S., & Leal Barbosa, L. C. (2023). Should we turn off the
music? Music with lyrics interferes with cognitive tasks. *Journal of
Cognition*, *6*(1), 24. <https://doi.org/10.5334/joc.273>

Taheri, S., Razeghi, M., Choobineh, A., Kazemi, R., Rasipisheh, P., &
Vali, M. (2022). Investigating the effect of background music on
cognitive and skill performance: A cross-sectional study. *Work*,
*71*(4), 871–879. <https://doi.org/10.3233/WOR-213631>
