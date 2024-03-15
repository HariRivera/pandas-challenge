# pandas-challenge
## Challenge #3 Pandas Hari Rivera
The goal of this work conducted with Pandas in Python was to analyze and understand student performance across various schools within a school district, based on key dimensions such as spending per student, school size, and school type (Charter vs. District). Pandas, a Python library for data manipulation and analysis, was extensively used due to its ability to handle large data sets, ease of use for statistical computations, and effectiveness in grouping and sorting data to gain meaningful insights.

## Specific Objectives:
Analyze the Impact of Spending per Student on Performance: We segmented schools into spending ranges per student to examine how differences in financial investment affect average math and reading scores, as well as passing percentages in these subjects.

Assess the Influence of School Size on Student Performance: Schools were classified by size to determine if there's a correlation between the size of the school and student performance, measured through average scores and passing percentages.

Compare Performance Between Charter and District Schools: We compared Charter schools with District schools to identify significant differences in student performance, thus providing a basis for educational policy discussions.

## Methods Used:
Categorization and Binning: We used pd.cut() to categorize schools into different ranges based on spending per student and school size, allowing us to analyze school performance within these specific segments.

Grouping and Aggregation: Data was grouped by categorical variables such as spending range, school size, and school type, and we calculated aggregate statistics like the mean to assess average performance across different categories.

Creation of Summary DataFrames: Several summary DataFrames were created to present findings in an organized and accessible manner, facilitating the interpretation and analysis of the results.

## Analysis Summary:
The school data analysis project has uncovered significant differences in student performance across various dimensions, including spending per student, school size, and school type. By utilizing a series of meticulously structured DataFrames, we have been able to break down school performance based on spending ranges per student, the sizes of the institutions, and their classification as either Charter or District schools. Key findings include variations in average math and reading scores, as well as differences in the passing percentages for these fundamental subjects.

# Conclusions:
## Impact of Student Spending on Performance:
Financial investment per student shows an inverse correlation with student performance, particularly noticeable in schools spending less than $585 per student, where the highest overall passing percentages are observed. Contrary to intuition, schools with higher student spending ($645-680) exhibit the lowest average math and reading scores, as well as the lowest passing percentages. This suggests that increased financial investment per student does not automatically guarantee an improvement in academic performance.

## Influence of School Size on Performance:
Students from small and medium-sized schools (less than 2000 students) significantly outperform those in large schools (2000-5000 students) in terms of average scores and passing percentages. Notably, small and medium-sized schools achieve a significantly higher overall passing percentage than large schools, indicating that a smaller size may facilitate a more effective and personalized learning environment that contributes to better academic outcomes.

These findings highlight the complexity of the factors influencing student performance and challenge some common assumptions about the relationship between student spending and educational quality. Additionally, they underscore the importance of considering school size when assessing and planning educational interventions. These insights can inform decision-makers in the school district on how to allocate resources more effectively and how to structure the school environment to maximize student performance.

This analysis provides a basis for deeper discussions and further evaluations aimed at improving education for all students in the district.

## Challenge Conclusion:
This work in Pandas provided a detailed insight into student performance across multiple dimensions, enabling the identification of strengths and areas for improvement. By leveraging Pandas' capabilities for data analysis, we were able to conduct a thorough and multifaceted analysis that contributes to a deeper understanding of the factors affecting educational success in the school district.
