# Student Performance in an Admission test
Goal: A school wants to analyze how parental education level and test preparation courses would affect a student's academic performance?

<hr style="border: 0; height: 2px; background: linear-gradient(to right, #00f2fe, #4facfe, #43e97b, #38f9d7); border-radius: 2px;">

#  Introduction
Many students take admissions tests, and they encounter various difficulties. Understanding and analyzing student performance on those examinations is vital for schools to determine how they may contribute to improving it. The performance of students might fluctuate amongst groups and be impacted by a variety of circumstances. A deeper comprehension of these elements can aid the school in developing methods to raise student achievement.

<hr style="border: 0; height: 2px; background: linear-gradient(to right, #00f2fe, #4facfe, #43e97b, #38f9d7); border-radius: 2px;">

#  Data Description

<img width="2330" height="914" alt="image" src="https://github.com/user-attachments/assets/784241a0-e6bb-452b-a2b4-9e4873b3d84b" />

There are 1000 rows and 9 columns in this dataset. Since there were no null values in this dataset, no data imputation was utilized during data preprocessing.

Both categorical and numerical column types are used to display data about the students, including gender, test preparation courses taken, parental education level, lunch, race/ethnicity groups, and scores on the writing, reading, and math sections of the admission test.

We also have a feature-engineered column called Obtained Score, which is a score total. Students' scores in the various portions of the test as well as the overall score are provided in numerical columns. However, categorized columns are giving us some further information about their background and exam preparation that can aid in our research.

<hr style="border: 0; height: 2px; background: linear-gradient(to right, #00f2fe, #4facfe, #43e97b, #38f9d7); border-radius: 2px;">

#   Methodology for Data Analysis:
We have used many data analysis approaches, such as

1. Data aggregation and Data summary procedures, to filter our dataset into subsets and aggregate it using either the mean, mode, or median.
2. To do our data aggregation based on quartiles, we have conducted analysis using the Minimum, Maximum, and Range values of the numerical columns. We were able to do an inter-quartile range analysis using these     quartiles to identify outliers in a dataset.
3. In addition to putting Measures of Location and Measures of Spread into practice, we also performed data visualization analysis by creating scatter plots, bar plots, and correlation graphs from our dataset.
4. Power BI is used a a Data Visualisation tools to compile the data and reports.

 <hr style="border: 0; height: 2px; background: linear-gradient(to right, #00f2fe, #4facfe, #43e97b, #38f9d7); border-radius: 2px;">  

#  Insights Generation:
Here are some conclusions we were able to draw from the aforementioned analysis:

Depending on gender
Female students were able to perform better than male students when comparing their overall performance on the admissions test based on Obtained Score. However, if we look at the individual results, we find that female students did not perform any better than male students in math. However, they performed better in writing and reading than the study's male participants.

<img width="622" height="72" alt="image" src="https://github.com/user-attachments/assets/f0777c4a-c573-4de9-b9aa-d3cef8cb23b3" />

Based on exam preparation:
According to overall scores and section-by-section scores, all students who were able to finish the test preparation courses were performing relatively better than other students.

<img width="627" height="78" alt="image" src="https://github.com/user-attachments/assets/4b05f70d-f702-483f-842d-390a9be85439" />

Based on Parental Education Level:
We summed up our analysis at Parental Education Level in order to help you comprehend the significance of your parents' educational background. In comparison to students whose parents had some college or some high school as their parental level of education, those whose parents had significantly higher levels of education, such as Masters or bachelors, were able to earn decent grades.

<img width="632" height="548" alt="image" src="https://github.com/user-attachments/assets/5a7c5199-e47c-4321-8944-823d7a3be97b" />

Performance by section:
We have determined that students have struggled the most in the Math part compared to other sections based on the minimum, mean, and median scores in the Math portion.

<img width="247" height="91" alt="image" src="https://github.com/user-attachments/assets/d3b0b0dd-756a-4adb-b331-0a90a16de1ba" />


Identification of Outliers:

Using the Interquartile Range, we were able to pinpoint two students who scored below either the IQR minimum or the bottom bound of the data distribution.


<img width="695" height="440" alt="image" src="https://github.com/user-attachments/assets/6321f6fa-73ed-4744-9b06-34c862ad697d" />

<hr style="border: 0; height: 2px; background: linear-gradient(to right, #00f2fe, #4facfe, #43e97b, #38f9d7); border-radius: 2px;">

#  Data Visualisation

[https://nacosa123-my.sharepoint.com/:u:/g/personal/hlelile_nacosa_org_za/EdaNHEJLeGVKlOF4SoG-r9wBnsLaY8N8D8yQt4LQArwkXA?e=Vk6OBQ](https://nacosa123-my.sharepoint.com/:u:/g/personal/hlelile_nacosa_org_za/EdaNHEJLeGVKlOF4SoG-r9wBnsLaY8N8D8yQt4LQArwkXA?e=YZj8Zp)


<img width="1167" height="652" alt="image" src="https://github.com/user-attachments/assets/955c1a3d-2329-46df-8e69-6e5336264983" />

<hr style="border: 0; height: 2px; background: linear-gradient(to right, #00f2fe, #4facfe, #43e97b, #38f9d7); border-radius: 2px;">

#  Conclusion
1. We now know that parents play a substantial part in a student's performance improvement. Parents who are educated, for instance, who hold a bachelor's or master's degree can better inspire and prepare their children for the admissions test. For parents who don't have a lot of education, schools can also set up extra help and training courses. so that these parents can inspire their kids and contribute more effectively to their achievement.
2. According to the dataset analysis, students who have completed test preparation classes can do better on all of the admissions exam's sections and earn higher grades. So that students can perform better on tests, schools should push them to finish preparation courses that allow them to practice all portions conceptually and practically.

<img width="1200" height="43" alt="image" src="https://github.com/user-attachments/assets/9eb4eef0-1c0c-434a-8fb5-2ecb0b0a82a1" />


