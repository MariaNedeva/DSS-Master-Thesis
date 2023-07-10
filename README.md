# DSS-Master-Thesis
The dataset used in this study is not publicly available and cannot be provided. 

The filder contains four files with codes, presenting the process of feature engineering from:
1) App-event time- series data that has been collected trough mobile application. The data is related to users' phone activity (applications used, timestamps, actudal time,
 and locations).
- features engineered: Ratio of specific applications usage, trend slopes of specific applications usage, trend slopes of overall phone usage

2) Location features - The locations from the abovementioned dataset were used in this file.
-features engineered: number of times specific area was visited, duration of stay

3) Sleep duration and study time
- features engineered: average time spent studying every day, average sleep duration

4) Well-being features - The original dataset contains daily questionary related to well-being and emotional state. The answers were measured in 7-point Likert scale.
- features enhgineered: trend slopes of change in well-being

The final file contains training and testing several machine learning models, as well, error analysis and SHAP features contribution to the best performing model.
