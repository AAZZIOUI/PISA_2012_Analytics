# PISA 2012 Exploratory data analysis
## by (Anas Azzioui)


## Dataset

PISA is a Program for International Student Assessment that assesses 15 years old students' competencies in 3 main subjects: mathematics, science and reading. It is conducted every 3 years, and each time the focus is on one of the subjects. In 2012, the focus was on mathematics, which means, students got more questions math-related. Alongside the assessments, PISA gather a lot of information about many features related especially to students, parents, teachers and schools.


## Summary of Findings

While working on the dataset, my main actions and findings were as follows:

    - The original csv file contains 635 columns and 485490 rows of data. After a careful analysis with the help of official documentation related to PISA 2012 (file codebook https://www.oecd.org/pisa/pisaproducts/PISA12_stu_codebook.pdf), I kept 93 columns that I thought would be useful and gave them understandable names.

    - The information I kept is related to:
        + Student's personal information
        + Student's Truancy (absenteeism)
        + Student's math interest
        + Parent's math interest from children opinion
        + Student's attributions to failure
        + Student's work ethics and behaviour
        + Student's learning startegies
        + Scores
    
    - After doing iteratively some data wrangling, I visually compared the above aspects with the score, gender and the grade in order to explore any trends that might impact the scores for all students in all countries, and from time to time, for students who scored 600 or above.

    - Main findings are:
        + Students' grades are distributed from 7th up to 12th grade.
        + The best 5 countries/regions in terms of the mean score of their students are:
            - China-Shanghai
            - Singapore
            - Hong Kong-China
            - Chinese Taipei
            - Korea
        + Absenteeism, work ethics and learning strategies differ among students. 
        + Absenteeism clearly has a negative influence on the score.
        + Students with high or low scores practice all kinds of learning strategies, work ethics or behaviours. But some work a little bit better in some grades for certain gender and some others don't.
        + Mean scores of math,reading and science are strongly, positively correlated with one another. This means that a student who is good at math is usually also good at reading and science.
         



## Key Insights for Presentation

I intend to show that math, reading and science are strongly correlated,then I will focus mainly on the analysis of the absenteeism, work ethics/behaviour, learning strategies, parents interest in maths and their impact on students' scores in order to answer the question, what makes those students perform well?

For that purpose, I converted, when needed, some violinplots from the exploration phase, into boxplots in the explanatory phase.

