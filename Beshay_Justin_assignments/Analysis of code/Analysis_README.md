# Memory Recall and Background Noise — R Analysis

This project presents a simulated experimental analysis investigating how different background noise conditions (Silence, White Noise, and Music) affect memory recall performance. The study explores both direct effects on recall and potential moderating factors such as music familiarity and personal study habits.

## Objectives

- **Primary Hypothesis**: Participants in the silence condition will have higher recall accuracy than those in the music and white noise conditions.
- **Secondary Hypotheses**:
  - Familiar music may impair recall more than unfamiliar music.
  - Individuals who typically study with music may be less affected by background music.
- **Exploratory Analyses**:
  - Examine the relationship between recall response time and accuracy.
  - Investigate the interaction between condition and music study habits.
  - Assess the distribution and effects of music familiarity ratings.

## Files

- `PNB3EE3_simulated_data_177.csv`: Simulated dataset with 177 participants.
- `Memory_Noise_Analysis.Rmd`: Complete RMarkdown notebook with:
  - Data simulation and cleaning
  - Descriptive statistics
  - Exploratory and inferential visualizations
  - ANOVA, t-tests, correlation, and interaction models
  - Final visual summary and interpretation

## How to Use

1. Install all required R packages:

```r
install.packages(c("tidyverse", "ggplot2", "rstatix", "ggpubr", "effectsize"))
```

2. Ensure that `PNB3EE3_simulated_data_177.csv` and `Memory_Noise_Analysis.Rmd` are in the same working directory.

3. Open `Memory_Noise_Analysis.Rmd` in RStudio and click “Knit” to generate a report (HTML or PDF).

## Key Findings

- The silence condition produced the highest mean recall accuracy (~74.5%), followed by white noise (~65.9%) and music (~56.3%).
- A one-way ANOVA showed a significant effect of condition: F(2, 174) = 52.26, p < .001, η² = .38.
- Planned one-tailed t-tests confirmed:
  - Silence > Music (p < .001)
  - Silence > White Noise (p < .001)
  - White Noise > Music (p < .001)
- No significant correlation between music familiarity and recall (r = .11, p = .42).
- No significant interaction between background noise condition and music study habits.

## Future Directions

- Include delayed recall tests to measure long-term retention.
- Experimentally manipulate the complexity and lyrical content of music.
- Incorporate subjective measures such as emotional response or preference for background audio.
