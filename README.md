# School_District_Analysis

## Overview of the school district analysis

### Background

    The School District Analysis was conducted to confirm the effect that a subset of the data has on the overall analysis that was originally conducted. In this example, there was suspicion of academic dishonesty among the Thomas High School ninth grade math and reading scores. Because the investigation is ongoing into the specific examples of academic dishonesty, and the School Board still has decisions to make based off of the analysis, the decision was made to omit the Thomas High School ninth grade math and reading scores from the School District Analysis, upholding the state-testing standards and integrity. The School District analysis will look into the effect that omitting the ninth grade math and reading scores have on the accuracy of the analysis.

## Results

### How is the district summary affected?
    - The district summary after removing Thomas High School ninth grade math and reading scores shows a drop in every score metric including average math score, average reading score, % passing math, % passing reading and % overall passing.

![District_Summary_OG.png](https://github.com/stovepipe/School_District_Analysis/blob/main/Resources/District_Summary_OG.png)
![District_Summary_RW.png](https://github.com/stovepipe/School_District_Analysis/blob/main/Resources/District_Summary_RW.png)

### How is the school summary affected?
    - The school summary, similar to the district summary, reflects a drop in every metric except Average Reading Score. However, the scores do not drop enough to affect Thomas High School's ranking in the school district.

![Top_Five_Schools_OG.png](https://github.com/stovepipe/School_District_Analysis/blob/main/Resources/Top_Five_Schools_OG.png)
![Top_Five_Schools_RW.png](https://github.com/stovepipe/School_District_Analysis/blob/main/Resources/Top_Five_Schools_RW.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    -Thomas High School’s performance relative to the other schools decreased as a result of removing ninth grade math and reading scores.

### How does replacing the ninth-grade scores affect the following:
        a. Math and reading scores by grade
        -No effect indicated

        b. Scores by school spending
        -No effect indicated

        c. Scores by school size
        -No effect indicated

        d. Scores by school type
        -No effect indicated

## Summary

### Analysis identified four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

        1. Thomas High School ninth grade math and reading scores caused all but one score metric in the reworked district summary to drop. The only metric that did not drop after removing ninth grade scores is Average Reading Score. This indicates that the math scores that were removed, were higher than the district average math score, as well as, more ninth graders overall passed than the average school in the district.

        2. The school summary closely reflected the district summary in Thomas High School's case with the exception of Average Reading Score. After ninth grade reading scores were removed, the % Passing Reading dropped similarly to other metrics, however, the Average Reading Score increased. This indicates that the ninth grade reading scores were lower than the average reading score of 83.84. Although the average reading scores were lower, more still were overall passing than the 10-12 grade overall passing percentage.

        3. In reference to the lack of effect that removing the Thomas High School ninth grade math and reading scores had on the score summaries by school spending, school size and school type, the school board can be assured that regardless of the outcome of the investigation into academic dishonesty among ninth graders, the summarys presented remain accurate for decision-making.

        4. The reported ninth grade math scores were higher than the district average and contributed to the overall passing percentage of Thomas High School.