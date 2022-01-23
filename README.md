# School_District_Analysis

## Overview of School District Analysis

### Background
In this module, we learned how to use Juptyer Notebook and Pandas to help Maria analyze data on student funding and standardized test scores. 

### Purpose
After successfully helping Maria analyze the data, she is notified by the school board that the students_complete.csv file shows evidence of academic dishonesty. Specifically, the math and reading grades for 9th graders attending THS have been altered. Consequently, Maria needs us take this new information into account by replacing the altered test scores, then repeat the school district analysis that we already completed while working through the module. We'll see if this new information affects our original analysis. 

## Results

- How is the district summary affected? \
The district summary is only slightly affected. Specifically, the **Average Math Score** decreased by 0.1 points, the **% Passing Math** decreased by 0.2%, the **% Passing Reading** decreased by 0.3%, and the **% Overall Passing** decreased by 0.1%.

## \Resources\images\01_District_Summary\new_district_summary.png##

![alt text](https://github.com/[dharler]/[School_District_Analysis]/[main]/Resources/Images/01_District_Summary/new_district_summary.png?raw=true)

- How is the school summary affected? \
As expected, the only row of the school summary that was affected is the **Thomas High School** row. However, out of the 5 highlighted values that were affected (see image below), all 5 were only changed by a few hundreths. Thus, the school summary was not significantly affected. 

- How does replacing ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools? \
Despite the updated data, Thomas High still ranks second in **% Overall Passing** relative to the other schools in the district!

- How does replacing the ninth-grade scores affect the following:
    - Math and Reading Scores by Grade: only the scores received by Thomas High 9th graders were changed
    - Scores by School Spending: Unaffected
    - Scores by School Size: Unaffected
    - Scores by School Type: Unaffected


## Summary
Four changes in the updated school district analysis inlcude a...
1. 0.1 point decrease in District **Average Math Score**
2. 0.2% decrease in District **% Passing Math**
3. 0.3% decrease in District **% Passing Reading**, and
4. 0.1% decrease in District **% Overall Passing**.
