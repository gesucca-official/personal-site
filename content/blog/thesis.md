---
title: "Bachelor Thesis"
date: 2018-10-12T12:49:27+06:00
featureImage: images/single-blog/thesis.png
postImage: images/single-blog/thesis-pres.png
---

My thesis presents a summary of a data mining study on student and course data from a Bachelor's degree program in computer science. The analysis used two datasets: one containing anonymous academic records of four student cohorts, and another with aggregated student evaluations of courses.

To extract insights for improving the program, visualization and data mining techniques were applied. MongoDB was chosen as the database management system due to its efficient handling of large datasets and compatibility with Python (via the pymongo driver). Additionally, the Weka software was used for data mining, alongside tools like R for visualization.

Initial analysis explored the datasets separately, revealing a direct correlation between student evaluations of a course and exam performance. The datasets were then joined to allow mining on combined records of student grades and course ratings. Using the K-Means algorithm, the data was clustered into two groups: courses rated highly and those rated poorly, based on exam grades, completion time, and student evaluations.

The Apriori algorithm identified associative rules with high confidence, supporting the correlation between course evaluations and student performance. Finally, frequent sequential patterns were mined with the GSP algorithm, highlighting exams often taken later than their ideal sequence, suggesting course order adjustments.

- [(EN) Presentation](/CiprianiSimone_Presentazione.pdf)
- [(IT) Summary](/CiprianiSimone_Riassunto.pdf)
- [(IT) Thesis](/CiprianiSimone.pdf)