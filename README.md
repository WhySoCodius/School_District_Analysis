# School_District_Analysis

## Overview of the school district analysis

The project's purpose is to analyze student performance at the school and district levels and provide useful insights into performance trends and patterns. Using the information, provide informed discussions and strategic decisions. Student funding and standardised test scores were considered in the analyses.

## Results

### District Summary
This investigation was repeated due to the possibility of academic dishonesty among Thomas High School ninth grade students. The full set of student data was used in the first trial of this study. In the second iteration, the ninth grade students of Thomas High School were excluded from the computations of this investigation. The scores of Thomas High School's whole ninth grade class have been substituted with NaN. The DataFrame below is an overview of the District Before & after the ninth graders' scores were replaced with NaN.

There was no effect on the School Type, Total students, Total School Budget and Per student Budget.

![District Summary Before](/Resources/District_summary.png)

- Average Math Score is 79.0 
- Percentage of Passing Math is 75
- Percentage of Passing Reading is 86
- Percentage of Overall Passing is 65

![District Summary After](/Resources/District_summary_Updated.png)

After Replacing the compromised score wit NaN below is the summary the District
- Average _Math_ Score dipped to 78.9
- Percentage of Passing _Math_ dipped to 74.8
- Percentage of Passing _Reading_ dipped to 85.7
- Percentage of _Overall_ Passing dipped to 64.9

![TopFiveSchools](/Resources/top_schools.png)

### School Size Vs School Budget

There is no relation between the School Budget and the Average test score & Passing Percentages.
In fact, As seen in the below Table as the budget increases test scores are decreasing and the Overall percentage is just little over 50%.

![School Budget](/Resources/School_Budget.png)

Also low Budget School - **Cabera High School** is the highest performing school in the entire district, whereas High Budget school - **Johnson High School** is the Lowest performing School
![All_top_schools](/Resources/All_top_schools.png)

Similarly, as shown in the table below, as the size of the school grows, test scores decline and the overall percentage decreases. This could be attributed to increased student engagement and increased teacher attention to student achievement.

![School Size](/Resources/School_Size.png)

### Charter vs. District Schools

All of the high-performing schools are "Charter Schools," whereas all of the low-performing schools are "District Schools," implying that Charter Schools outperform District Schools.

![CharterVsDistrict](/Resources/CharterVsDistrict.png)

### Average Scores by Grade Level

Based on the [Reading Score](/Resources/reading_scores_by_grade.png) and the [Maths Score](/Resources/Math_scores_by_grade.png) at Grade Level, there was no noticeable difference in performance depending on the students' grade level, but there were considerable differences in performance depending on the School.


## Summary

- Thomas High School's total passing percentages and average scores plummeted after the ninth graders' scores were replaced with NaN. 
- The district's average math and reading scores, as well as the total passing rate for kids, have all decreased.
- Thomas High School's overall passing percentage dropped from 91 percent to 65 percent.
- The school ranking of Thomas High School has dropped from eighth to second.
