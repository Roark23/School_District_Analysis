# School_District_Analysis
## Overview of the School District Analysis
The school board has notified of evidence showing academic dishonesty. This evidence specifically relates to the reading and math grades for Thomas High School ninth graders. We conducted a school district analysis using Pandas and Jupyter Notebook to determine key trends with the school data based on grades, school spending, size, and type. Now, we need to replace the ninth grade math and reading scores for Thomas High School with NaNs while keeping the rest of the data the same. 

# Results
### Overview of Original Anaysis
The school district analyses conducted before the evidence of scholastic dishonesty with

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
    
    The 91% for Thomas High School placed second in high schools. After accounting for the academic dishonesty, Thomas High School dropped down to 8th with a 65% overall passing rate.
- This discrepancy also shows how replacing ninth graders' math and reading scores affects Thomas High School's performance relative to the other high schools (2nd to 8th in Overall Passing %).

- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade:
        * The significance of replacing these scores was very minimal in terms of the average score. However, the student count adjustment went from 1635 to 1174 after changing the ninth grade scores. This means 461 scores were adjusted.

    - Scores by school spending:

    ![School_Spending](/Resources/School_spending.png)

    *  The significance of replacing these scores was very minimal in terms of the school spending. However,school spending may have an impact on school performance. Based on these schools, higher spending resulted in a lower student performance overall. The average overall passing was 90% for individual student spending of less than $585. Spening $645-$675 per student resulted in an overall passing percentage of almost 54%.

    - Scores by school size:

    ![School_Size](/Resources/school_size.png)

     *  Replacing the scores for school size did affect the data. It's important to note school size appears to have an impact on student performance. This data shows that large schools consisting of 2,000+ students had an overall passing percentage of 58%. This is a huge difference compared to small and medium schools both having around a 90% overall passing percentage.

    - Scores by school type:

    ![School_Type](/Resources/school_type.png)

     *  The significance of replacing these scores was very minimal in terms of thethe school type.Analyzing the data, it's evident school type also affects individual student performance. Charter schools appear to outperform District schools. While the average scores were similar for both math and reading, the overall percent passing was significant. Students in charter school pass 90% of the time overall. District school students had a 54% overall pass rate.

# Summary
#### Overall, we can draw many conclusions from the school district analysis. It is unfortunate that our analysis had to omit some of the data due to academic dishonesty. Replacing the scores with NaN for the entire grade does affect how accurate our data is relative to the other schools. However, there are still data driven conclusions we can make to not only inform schools, but potentially improve student performance for all the schools in the future. 
- Changing the school district analysis after replacing reading and math scores resulted in the average math score minimally decreasing. The overall passing math % decreased from 75% to 74.8%. The overall passing reading % decreased from 86% to 85.7%. Overall, the data was minimally affected after changing the math adn reading grades.
- The overall passing percetange for Thomas High school decreased significantly. The school went from 2nd to 8th and 91% down to 65%. INterestingly, increased school spending had an inverse relationship with student performance. Also, District schools and larger school student performance was worse than Charter and smaller schools.
