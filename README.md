## An exploration of the relationship between BMI,eyesight and mid-term test scores
### Data
The data is based on data collected from _CHINA EDUCATION PANEL SURVEY_ at [CEPS](http://ceps.ruc.edu.cn/English/Home.htm).
### Method
#### Data Cleaning
Delete student samples missing or incorrect essential variables.
#### Variable Selection
- Independent Variables: <br>
[Body Mass Index](https://zh.wikipedia.org/zh-cn/%E8%BA%AB%E9%AB%98%E9%AB%94%E9%87%8D%E6%8C%87%E6%95%B8) calculated by 
height and weight;<br>
Whether the student is short-sighted.
- Control Variables: <br>
Gender,Cognitive test scores, the type of household registration account,
whether the student is the only child in the family, the financial condition of the family,
the educational expectation of parents and child, the educational degree of mother and father <br>
- Dependent Variables: <br>
Mid-term Chinese, English, Math score.
#### Linear Regression using sklearn
- Use Linear Regression model to predict the relationship between independent
variables, control variables and dependent variables.
- Group student samples based on BMI to explore test performance
#### Conclusion