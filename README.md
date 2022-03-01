# School_District_Analysis
## Overview of the School District Analysis
The school board has notified of evidence showing academic dishonesty. This evidence specifically relates to the reading and math grades for Thomas High School ninth graders. We conducted a school district analysis using Pandas and Jupyter Notebook to determine key trends with the school data based on grades, school spending, size, and type. Now, we need to replace the ninth grade math and reading scores for Thomas High School with NaNs while keeping the rest of the data the same. 

# Results
### Overview of Original Anaysis
The school district analyses conducted before the evidence of scholastic dishonesty 

![PyCitySchools](/PyCitySchools.ipynb)

provides key insights relating to all the school districts:

![Original_Data](/Resources/Old_Total.png)

### Overview of Edited Analysis
There are some changes evident in the

![PyCitySChools_Challenge](/PyCitySchools_Challenge.ipynb)

 after adjustng for the scholastic dishonesty:

![Adjusted_Academic_Dishonesty](/Resources/New_Total.png)

To clean up the data, all the ninth grade reading and math scores at Thomas Lee High School needed to be replaced with NaN (Not a Number) to account for the academic dishonesty.

To summarize the changes in data, we can look at various categories to see how Thomas Lee Hiigh School was affected.
- District Summary
    - Analyzing the original and adjusted data for Thomas High School, it's evident there weren't any staggering changes. However, a few categories were minorily adjusted:
        -   The average math score decreased from 79 to 78.9. 
        -   The overall passing math % decreased from 75% to 74.8%.
        -   The overall passing reading % decreased from 86% to 85.7%.
- School Summary
    - The Overall Passing % for Thmomas High School was almost 91% 

    ![Original_Thomas_School_Summary](/Resources/Old_Overall_Passing.png)
    
    The 91% for Thomas High School placed second in high schools. After accounting fo rthe academic dishonesty, Thomas High School dropped down to 8th with a 65% overall passing rate.
- This discrepancy also shows how replacing ninth graders' math and reading scores affects Thomas High School's performance relative to the other high schools (2nd to 8th in Overall Passing %).

- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade:
        * The significance of replacing these scores was very minimal in terms of the average score. However, the student count adjustment went from 1635 to 1174 after changing the ninth grade scores. This means 461 scores were adjusted.

    - Scores by school spending:

    ![School_Spending](/Resources/School_spending.png)

        * School spending does not seem to have an impact on school performance. However, based on this data, higher spending resulted in a lower student performance overall. The average overall passing was 90% for individual student spending of less than $585. Spening $645-$675 per student resulted in an overall passing percentage of almost 54%.

    - Scores by school size:

    ![School_Size](/Resources/school_size.png)

        * 
    - Scores by school type