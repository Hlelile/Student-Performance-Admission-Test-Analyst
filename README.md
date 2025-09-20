# Student-Performance-Admission-Test-Analyst
Goal: A school wants to analyze how parental education level and test preparation courses would affect a student's academic performance?

Introduction
Many students take admissions tests, and they encounter various difficulties. Understanding and analyzing student performance on those examinations is vital for schools to determine how they may contribute to improving it. The performance of students might fluctuate amongst groups and be impacted by a variety of circumstances. A deeper comprehension of these elements can aid the school in developing methods to raise student achievement.

<img width="2330" height="914" alt="image" src="https://github.com/user-attachments/assets/784241a0-e6bb-452b-a2b4-9e4873b3d84b" />

There are 1000 rows and 9 columns in this dataset. Since there were no null values in this dataset, no data imputation was utilized during data preprocessing.

Both categorical and numerical column types are used to display data about the students, including gender, test preparation courses taken, parental education level, lunch, race/ethnicity groups, and scores on the writing, reading, and math sections of the admission test.

We also have a feature-engineered column called Obtained Score, which is a score total. Students' scores in the various portions of the test as well as the overall score are provided in numerical columns. However, categorized columns are giving us some further information about their background and exam preparation that can aid in our research.
Methodology for Data Analysis:
We have used many data analysis approaches, such as

Data aggregation and Data summary procedures, to filter our dataset into subsets and aggregate it using either the mean, mode, or median.
To do our data aggregation based on quartiles, we have conducted analysis using the Minimum, Maximum, and Range values of the numerical columns. We were able to do an inter-quartile range analysis using these quartiles to identify outliers in a dataset.
In addition to putting Measures of Location and Measures of Spread into practice, we also performed data visualization analysis by creating scatter plots, bar plots, and correlation graphs from our dataset.
Power BI is used a a Data Visualisation tools to compile the data and reports.

Insights Generation:
Here are some conclusions we were able to draw from the aforementioned analysis:

Depending on gender
Female students were able to perform better than male students when comparing their overall performance on the admissions test based on Obtained Score. However, if we look at the individual results, we find that female students did not perform any better than male students in math. However, they performed better in writing and reading than the study's male participants.

image
Based on exam preparation:
According to overall scores and section-by-section scores, all students who were able to finish the test preparation courses were performing relatively better than other students.

image
Based on Parental Education Level:
We summed up our analysis at Parental Education Level in order to help you comprehend the significance of your parents' educational background. In comparison to students whose parents had some college or some high school as their parental level of education, those whose parents had significantly higher levels of education, such as Masters or bachelors, were able to earn decent grades.

image
Performance by section:
We have determined that students have struggled the most in the Math part compared to other sections based on the minimum, mean, and median scores in the Math portion.

image
Identification of Outliers:
Using the Interquartile Range, we were able to pinpoint two students who scored below either the IQR minimum or the bottom bound of the data distribution.

<img width="738" height="407" alt="image" src="https://github.com/user-attachments/assets/1a0dd5a8-e303-4ef9-a757-fa9c1d72844b" />

<img width="695" height="440" alt="image" src="https://github.com/user-attachments/assets/6321f6fa-73ed-4744-9b06-34c862ad697d" />

Data Visualisation



Conclusion
We now know that parents play a substantial part in a student's performance improvement. Parents who are educated, for instance, who hold a bachelor's or master's degree can better inspire and prepare their children for the admissions test. For parents who don't have a lot of education, schools can also set up extra help and training courses. so that these parents can inspire their kids and contribute more effectively to their achievement.
According to the dataset analysis, students who have completed test preparation classes can do better on all of the admissions exam's sections and earn higher grades. So that students can perform better on tests, schools should push them to finish preparation courses that allow them to practice all portions conceptually and practically.



Data Visualisation
Link: https://app.powerbi.com/view?r=eyJrIjoiNTBkZjRkNmQtMDg2Mi00NDcxLTliMDgtMzgzNjRjMmUyNTg2IiwidCI6IjJlNjQwMjUwLTUyZTQtNDkyMS1hYjAyLTA3MzMzNzQ1YjIwOSIsImMiOjEwfQ%3D%3D

image
