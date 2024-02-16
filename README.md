# School_District_Analysis

## Overview of School District Analysis

### Background
In this module, we were tasked with assisting Maria, the chief data scientist for a city school district, in analyzing student test score data. Specifically, we used Pandas and Jupyter Notebook to aggregate the student test score data into various formats, enabling us to uncover current patterns and trends which could then be used to drive future school board decisions.

### Purpose
After successfully helping Maria analyze the data, she is notified by the school board that the students_complete.csv file shows evidence of academic dishonesty. It seems that the math and reading scores for 9th-graders attending THS have been altered. Consequently, Maria needs us take this new information into account by replacing the altered test scores, then repeat the school district analysis. We'll see if this new information affects our original analysis. 

## Results

How is the district summary affected?

- The district summary is only slightly affected. Specifically, the **Average Math Score** decreased by 0.1 points, the **% Passing Math** decreased by 0.2%, the **% Passing Reading** decreased by 0.3%, and the **% Overall Passing** decreased by 0.1%.

**Original District Summary**
![Original District Summary](https://github.com/dharlerjr/School_District_Analysis/blob/main/Resources/Images/01_Original_District_Summary.png)

**Updated District Summary**
![Original District Summary](https://github.com/dharlerjr/School_District_Analysis/blob/main/Resources/Images/10_Updated_District_Summary.png)

How is the school summary affected?

- As expected, the only row of the school summary that was affected is the **Thomas High School** row. 

How does replacing ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?

**Original School Summary**
![Original District Summary](https://github.com/dharlerjr/School_District_Analysis/blob/main/Resources/Images/02_Original_School_Summary.png)

**Updated School Summary**
![Original District Summary](https://github.com/dharlerjr/School_District_Analysis/blob/main/Resources/Images/11_Updated_School_Summary.png)

- Despite the updated data, Thomas High still ranks second in **% Overall Passing** relative to the other schools in the district!

How does replacing the ninth-grade scores affect the following:

- Math and Reading Scores by Grade:     only the scores received by Thomas High 9th graders were changed
- Scores by School Spending:            Unaffected
- Scores by School Size:                Unaffected
- Scores by School Type:                Unaffected


## Summary
Four changes in the updated school district analysis inlcude...
1. a 0.1 point decrease in District **Average Math Score**
2. a 0.2% decrease in District **% Passing Math**
3. a 0.3% decrease in District **% Passing Reading**, and
4. a 0.1% decrease in District **% Overall Passing**.