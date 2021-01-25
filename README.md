# School District Analysis

*Prepared for Maria - 2021 JAN 24*

## Overview of the School District Analysis

### Purpose

This report is an addendum to the orginal analysis of high school grades within the board. The main purpose of the orginal report was to determine budget and school priorities for the upcoming year, however academic dishonesty is suspected in the grade 9 level at Thomas High School, and therefore the data analysis needs to be updated in order to understand the extent of impact that the academic dishonesty from Thomas High School and ensure that they uphold state-testing standards. This updated analysis will be performed by replacing all grade 9 math and reading marks from Thomas High School with NaN, and they will therefore not be included in the data, allowing all other associated data with this student group to remain intact. The total number of marks with NaN was **461**. This analysis and the updated data findings to the school board, which will inlcude the following:

* District Summary
* School Summary
* Top 5 and botton 5 performing schools
* The average math score for each grade level from each school
* The average reading score for each grade level from each school
* The scores by school spending per student
* The scores by school size
* The scores by school type

### Resources

* Data sources: students_complete.csv, school_complete.csv
* Software: Python 3.8.5, jupyter notebook

## School District Analysis Results

### District Summary
As displayed in the **District Summary** below, after removing the Thomas High School Grade 9 math and reading scores, the **Average Math Score** dropped by **0.1%**, the **% Passing Math** dropped by **0.2%**, the **% Passing Reading** dropped by **0.3%**, and the **% Overall Passing** dropped by **0.1%**. 
![District Summary](Resources/District_Summary.png)
### School Summary
As displayed in the **School Summary** below, for Thomas High School (*after removing the grade 9 math and reading scores*) the **Average Math Score** dropped by **0.07%**, the **Average Reading Score** increased by **0.05%**, the **% Passing Math** dropped by **0.08%**, the **% Passing Reading** dropped by **0.29%**, and the **% Overall Passing** dropped by **0.32%**. 
![School Summary](Resources/School_Summary.png)
### Top 5 and bottom 5 performing schools
As displayed in the **Top 5** chart, although the marks for Thomas High School are slightly different (refer to *School Summary* above), they still remain in the top 5 schools. The **Bottom 5** chart also remains unchanged.
![Top 5](Resources/Top_5.png)
![Bottom 5](Resources/Bottom_5.png)
### The average math score for each grade level from each school
As displayed in the chart below, the average math scores for each grade at each school remains unchanged, although for grade 9 at Thomas High School *NaN* replaces a numeric value.
![Average Math](Resources/Average_Math.png)
### The average reading score for each grade level from each school
As displayed in the chart below, the average reading scores for each grade at each school remains unchanged, although for grade 9 at Thomas High School *NaN* replaces a numeric value.
![Average Reading](Resources/Average_Reading.png)
### The scores by school spending per student
The student scores by **Spending** is not impacted by removing the Thomas High School grade 9 marks.
![Scores by Spending](Resources/Scores_Spending.png)
### The scores by school size
The student scores by **School Size** is not impacted by removing the Thomas High School grade 9 marks.
![Scores by School Size](Resources/Scores_Size.png)
### The scores by school type
The student scores by **School Type** is not impacted by removing the Thomas High School grade 9 marks.
![Scores by School Type](Resources/School_Type.png)

## Summary
Fortunately, there were no major changes in the data despite the academic dishonesty from the 9th grade at Thomas High School. Although the impact was minimal, it is important to note the main changes:
* Average Math Scores, % Passing Maths, % Passing Reading, and the % Overall Passing **dropped** for both *District Summary* and *School Summary (for Thomas High School)
* Average Reading Scores **increased** for *School Summary (for Thomas High School)
