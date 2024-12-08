# Analysis on Student's Performance Factors
This is a group final project on applying different visualisation techniques, statistical inference techniques and OLS regression on the StudentPerformanceFactors dataset to collect insights on how students' perfromance vary with respect to multiple life and education factors.

The source code are provided in each corresponding notebooks. Before runing, it's expected to have these libraries installed:
- [NumPy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [statsmodels](https://www.statsmodels.org/stable/index.html)
- [seaborn](https://seaborn.pydata.org/)

## Techniques Summary
- We have successfully examined and prepared data in order to increase the quality of exploratory results through missing value processing and outlier detection.
- We also did univariate as well as multivariate exploratory analysis to better grasp the details of mentioned dataset. This includes providing characteristics of students through their distributions and centrality measures, exploring bivariate relationships between numerical as well as categorical features, exploring the relationships between one or two features to the target variable Exam_Score. In order to ensure statistical significance, we use various hypothesis tests to check for correlations: Chi-square test of Independence, Pearson's r statistics and Oneway-ANOVA.
- For visualisation of these relationships, we have succesfully applied different plots to show trends and differences of groups of students present in the dataset.
- Finally, we constructed a multiple linear regression model and estimated it using OLS method provided by statsmodels. We have found that our model is statistically signification at 5% signifance level. Furthermore, R^2 metric concludes that our model could explain approximately 85% of the variation in exam score. Our model also concludes that Access_to_Resources and Parental_Involvement have the most effect on Exam_Score.

## Analysis Summary
Through our exploratory anlysis, we have found evidence to conclude commonly known trends:
- Numerically, the more time students invested in studying as well as the more attendant they are the more likely they will perform well.
- The students' access to resources and parental involvement have high effects to their performance.
- Although small, parental's educaion level, other peer's influence and learning disabilities correlate to students' performance.
- Moreover, we have also found intercorrelation between features. Firstly, students who participate in extracurricular activities are more likely to be influenced (either positively or negatively) by their peers. Secondly, students with low motivation level are less likely to rate teacher quality as low. Finally, private school students are more likely to have high access to resources. 

---
## Acknowledgement
We would like to show gratitudes and thanks to Dr. Nguyen An Te for his guidance to Data Visualisation and Statistical Analysis. Not for your guidance, this project would have been a lot more challenging and would be a lot less than what it is.\
Once again, we thank you for your noble time and patience as you pass down more and more knowledge to future Data Science majors. We wish the best of the best!

---
### Our contributors:
---
Nguyễn Tấn Gia Bảo\
Trương Thế Bảo\
Trịnh Ngọc Các\
Nguyễn Thị Ngọc Diệp