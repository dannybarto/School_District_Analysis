# School_District_Analysis

The additional school district analysis was commissioned due to suspicions that the reading and math grades for Thomas High School ninth graders have been modified. Our task was to replace the math and reading scores for Thomas High School ninth graders with NaNs and retain the completeness of the remainder of the data. After that we were asked to go back through the original school district analysis and report our findings.

## How is the district summary affected

The scores in the district summary were affected only slightly by the removal of ninth grade reading and math scores. The changes are basically withing tenths of percentage points across the board.

## How is the school summary affected?
Again, we see a negligible difference when the ninth grade reading and math scores are removed from the analysis.

## How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?

Replacing the ninth graders' math and reading scores does bring the average scores up a bit relative to other schools.

## How does replacing the ninth-grade scores affect the following:

    - Math and reading scores by grade
      Math and reading scores do not show any significant improvement coming out of any school
    - Scores by school spending
      Overall spending per student is higher in bottom performing schools
    - Scores by school size
      Smaller schools '(<2000) have significantly higher pass rates than larger schools '(>2000)
    - Scores by school type
      Charter schools outperform 

## Summary

There weren't any significant changes to note even after introducing the NaNs to the data frame. The math and reading passing percentages were statistically insignificant. A couple of other things to note. Spending per student is not a predictor of better scores. In fact, it appears to the be opposite. Also, it is interesting to note that the bottom performing schools are all District and the top five are all Charter.  Overall the results were inconclusive.


