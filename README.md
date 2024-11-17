# DatathonF2024

## Sebastian Chacon and Julian Cabrerra achieved 1st Place representing Traders@SMU

The Datathon was a 20 hour simulation challenge in which each team is tasked as "Consultants" for XYZ Company to present a thorough Trend Analysis, Abnormality Detetcion, and pitch actionable insights (via Proof of Concept) for a new product using Health and Fitness datasets. Myself along with Julian Cabrerra presented "NightHorse Tracker", a new health watch tracker utilizing two Machine Learning models to gather and interpret health metrics such as calorie intake, steps per day, hours of sleep, etc. 

Our models consisted of an Isolation Forest which found abnormalities in our data allowing us to plot a boundary curve for non-linear outliers in our data paired with a Gradient Booster, taking 6 inputs to build "profiles" around the trends in people who develop sleep disorders such as AFIB, Sleep Apnea, and Insomnia. Utilizing these models we can ping users with mild-harsh warnings alerting Users of their negative health habits that could develop sleeping disorders.


### Insights and going forward:

Through this project I (Sebastian Chacon) was able to apply techniques learned from ML classes and Traders@SMU to real world applications in which our pitch was given to Data Scientists from AT&T. Given more time for the project, I would love to have larger sample sizes in our data as I believe we could have impelemented better Data Leakage and Overfitting prevention as our model had an incredible prediction accuracy (93%). Our dataset had only 374 samples which is significantly smaller than typical inputs for ML. Addtionally, I would've liked to implement Multi-Linear regression to plot exactly the relationship found between Sleep Disorder development from metrics such as: Stress Level, Caloric Intake, Fitness levels, etc.
