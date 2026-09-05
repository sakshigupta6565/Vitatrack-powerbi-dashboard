# VitaTrack Wellness – Health & Lifestyle Analytics Dashboard

## Business Question
VitaTrack Wellness, a digital health company, wanted to understand user 
lifestyle patterns and identify factors linked to heart disease risk, 
in order to improve lifestyle suggestions for users.

## Approach
- Analyzed user data covering Age, Gender, BMI, Steps, Calories, Sleep, 
  Heart Rate, Blood Pressure, Smoking, Alcohol, Exercise, Diabetic and 
  Heart Disease status
- Built a one-page Power BI dashboard with DAX measures to explore 
  activity levels, BMI trends, and smoking/alcohol impact
- Segmented users by activity level for targeted recommendations

## Key Findings
- Analyzed 1,000 users, tracking average steps (10.7K), sleep (6.9 hrs), 
  BMI (26.7), and 93 total heart disease cases
- Highly active users recorded higher average daily steps than other 
  activity groups, with similar sleep duration across all three activity 
  segments
- Smoking showed no strong association with heart disease or heart rate 
  in this dataset — smokers had a slightly *lower* heart disease rate 
  (7.9%) than non-smokers (9.6%), and near-identical average heart rate 
  (85.2 vs 84.6 bpm)
- Daily steps and sleep hours showed no clear relationship in the 
  scatter plot, suggesting physical activity alone doesn't explain 
  sleep duration
- BMI stayed relatively consistent across age groups and genders 
  (25.8–27.4), without a strong age-driven pattern
- Users segmented into 54.8% Highly Active, 25.6% Moderately Active, 
  and 19.6% Low Active

## Recommendations
1. Encourage low-active users toward walking/fitness programs to close 
   the activity gap seen in the data
2. Since smoking didn't show a strong link to heart disease or heart 
   rate in this sample, avoid overstating that connection — instead 
   focus awareness efforts on the metrics that did show patterns
3. Promote consistent weight-management guidance across all age groups, 
   since BMI didn't vary strongly by age in this data

## Tools
Power BI, DAX

![Dashboard Screenshot](dashboard.png)
