# Fraud-Detection
Detecting anomaly patterns in surveys using autoencoders

This was an internship assessment project that I was required to do, I have developed my skill using unsupervised learning with this project and had to expand my knowledge on autoencoders and how they work.

A breif report of the assessment is found in the file Report.pdf

Below you can see all the entries that were completed, the green dashed line is the threshold line and any point above that is colored red and is labeled as Fraud

![Fraud detection scatter plot](https://user-images.githubusercontent.com/86129692/122640371-ddbc1800-d107-11eb-9638-0d1d251bae02.png)

Out of the 155,000 data entries, we have gathered 12,341 data points that were labeled as "Complete" to where the user opened and completed the survey this rewarding the user with a revenue per completion.

We then split the completed datapoints into a 80/20 for training and testing with the testing consisting of 2,468 datapoints.

Out of the 2,468 datapoints we have detected 27 fraudulent activities and the user_id and the survey_id of these fraudulent activities can be found in the table below.

![image](https://user-images.githubusercontent.com/86129692/122640350-cd0ba200-d107-11eb-91ff-e5c1b93eb41d.png)

