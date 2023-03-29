# pandas-challenge
Module 4 - Pandas Challenge

*Summary of Analysis*

This analysis was based on combining two data sets from PyCity schools. One data set that focused on the 'school data' that included data such as the school names, student populations, budgets, and types of schools. The other data set was 'student data' that included information on the school each student attends, grade level, and reading and math scores. The analysis generated insightful data into the relationships between the school budgets, size, and types of schools to shows how those factors correlate with students' reading and math scores.


*School Spending Per Student*

One of the more surprising parts of the analysis shows that the amount of dollars spent per student does NOT have a positive correlation to the overall performance based on math and reading test scores. The lowest spending range, <$585/student, actually had the highest overall passing rate. 

It is common to think that schools often need more funding to provide better outcomes for their students, but this dataset actually shows the opposite. Taken at face value this could imply that spending less money would improve the lower performing schools, but that is likely an oversimplification. There are likely other socioeconomic impacts at play that are not accounted for in this dataset. For example, the average household income per school would offer some insight into the socioeconomic backgrounds that make up the student populations at each school. 

*School Size & Passing Rates*

The correlation between the school size and passing percentages had a more expected result, with small (<1000 students), and medium sized (between 1000-2000 students) schools far outperforming the large schools (2000-5000 students). Small and medium size schools had roughly 90% overall passing rates, while the largest schools only had a 58% overall passing rate. 

It is an easy assumption to say that smaller schools are able to drive better testing results for students by focusing teacher and faculty efforts onto a smaller student population. However, there is still a key piece of data that could provide more insight on this topic to better understand the drastic decline in test scores between the different size schools. Data on the 'student teacher ratio' or 'average students per teacher' would help provide clarity if the key factor is really the student population or the number of faculty per student.

*Types of Schools*

Comparing the results between Charter schools and District schools is effectively another comparison between school sizes. I added the mean number of students to my data to better explain this point. The difference in the average student population is quite drastic. The average number of students for Charter schools are only about ~1500 students. Compared to the average number of students for District schools over ~3800 students. You can also see this relationship in the 'per_school_summary' table by just observing the smaller student population for most of the Charter schools, but calculating the average emphasizes the stark difference in these very different school populations. 

Without showing the student population next to the testing results for the type of schools it would be easy to dismiss any argument against increasing funding for District schools. Especially when District schools spend on average almost $50 more per student. This value was also added to my analysis to provide more insight into the data. 

Overall this analysis raises serious concerns for how the District schools for PyCity are setup. At face value the data is very supportive of Charter schools, but additional analysis should be done to have a deeper understanding of the underlying factors that could be contributing to the stark differences shown in this analysis. A couple examples previously mentioned are the socioeconomic standing of families for each school, as well as the student teacher ratio between these different types/sizes of schools. 
