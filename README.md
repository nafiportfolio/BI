# BI
Business Intelligence (BI) Portfolio showcasing expertise in data analytics.
Tableau Public URL: https://public.tableau.com/views/AnalyzingFitnessandDigitalBehaviorTrends_17424018487610/Insights?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

This document provides a detailed case solution for Fitness and Design Behavior Trends. It outlines the data sources, solution design, business logic, and formulas used in the project. The objective is to ensure clarity and transparency in the approach and methodology applied to this solution.
Dataset: 
Gym Members Exercise Tracking Dataset:
Contains information about gym members’ demographics, health metrics, workout habits, and hydration levels.	 

User Behavior Dataset:
Contains details about members’ mobile device usage and digital habits.	 

Repository Location: nafiportfolio/BI: Business Intelligence (BI) Portfolio showcasing expertise in data analytics.
Solution Design:

The workflow is the approach of solution designing for this project. 
The dashboard was developed using Tableau Public, incorporating two data sources:
Case Study – Including Heads.xlsx (974 records, including headers) located at C:\Users\user\Downloads\Case Study – Including Heads.xlsx.
User Behavior Dataset.xlsx (701 records, including headers).
Both datasets contain Age and Gender as common columns. An inner join was performed on these fields, resulting in a final dataset of 701 unique records.
Business Logics and Formula used on this visualization process: 
I began by analyzing the datasets to understand their structure, including data types from both sheets. After reviewing the business questions embedded in the data, I conducted exploratory data analysis (EDA) to identify key relationships and patterns. This allowed me to determine the most relevant variables for visualization and insight generation. To maintain clarity, I documented all exploratory analyses in a separate dashboard. I have published the dashboard and named it as Exploratory Analysis tab. 
 
Insights:
In the Insights tab, I focused on addressing the four key case questions.
 
Q1: Are there patterns in workout types (e.g., strength, cardio, yoga) based on digital usage habits?  
This visualization compares screen-on time and app usage time per day across different workout types (Cardio, HIIT, Strength, and Yoga). The green bars represent total screen-on time (hours/day), while the red bars indicate app usage time (hours/day).
Key Insights:
Higher Screen Time Than App Usage – Across all workout types, users spend more total screen-on time than actively using the app, indicating passive engagement (e.g., video streaming, background use).
HIIT Shows the Highest Engagement – Users engaged in HIIT workouts have the highest screen-on time (5.1 hours/day) and app usage (3.9 hours/day), suggesting a strong reliance on digital platforms for guided training.
Consistent App Usage Across Workouts – App usage remains stable (~3.8-3.9 hours/day) across different workout types, which may suggest habitual usage patterns regardless of workout intensity.
Opportunity for Engagement Optimization – Understanding the gap between screen time and active app use can help refine user experience strategies, such as targeted content delivery, engagement incentives, or personalized workout recommendations.
Findings: Users spend more time on their screens than actively using the app across all workout types, with HIIT showing the highest engagement (5.1 hours/day screen time, 3.9 hours/day app usage). The consistent app usage (~3.8-3.9 hours/day) suggests habitual engagement, highlighting opportunities to enhance interaction through personalized content and engagement strategies.
This analysis helps identify digital engagement patterns, guiding strategic improvements for user retention and experience optimization.
Q2: Do users with higher app usage spend less time on workouts or burn fewer calories?  
This scatter plot examines the relationship between median calories burned and median app usage time (hours/day) across different gender groups.
Key Insights:
Inverse Relationship Between App Usage and Calories Burned – Users with higher app usage tend to burn fewer calories, suggesting that increased screen time may not necessarily translate to more active workout engagement.
High-Calorie Burners Show Lower App Usage – The data points indicate that users burning the most calories (closer to 900 median calories burned) generally have lower median app usage, implying that they may rely less on the app during workouts or engage in more offline activities.
Higher App Usage Correlates with Lower Activity Levels – Users who spend the most time on the app (closer to 8 hours/day) are not necessarily the most active, which may indicate passive app usage for content browsing, tracking, or non-exercise-related activities.
Business Implications:
There is an opportunity to enhance engagement strategies by promoting more interactive and guided workouts to ensure high app usage aligns with increased physical activity.
Personalization features, such as adaptive workout plans, reminders, and gamification, could encourage users to actively engage in workouts rather than passively consuming content.
This analysis suggests that while the app is being used frequently, optimizing its features to drive more active participation could enhance user fitness outcomes.
In conclusion, the data indicates an inverse relationship between app usage and calories burned, suggesting that higher screen time does not always translate to increased physical activity. To bridge this gap, optimizing the app with interactive features, guided workouts, and personalized engagement strategies can encourage more active participation and improve overall fitness outcomes.
Q.3: How does hydration level correlate with app or screen-on time? 
In linear regression, R-squared measures the strength of the relationship between variables, where a higher value indicates a better fit. The p-value assesses statistical significance, where a lower value suggests a meaningful relationship.
The scatter plot visualizes the relationship between average water intake (liters/day) and app usage time (hours/day) across different user types.
Key Observations:
Weak Correlation Between Hydration and App Usage – The R-squared value (0.08) indicates a very weak relationship, meaning hydration levels do not strongly predict app usage time. The P-value (0.4579) further suggests the relationship is not statistically significant.
Mixed Trends Across User Groups – 
The blue trend line (right Y-axis) shows a slight positive correlation, indicating that some users with higher hydration levels may spend more time using the app.
The pink trend line (left Y-axis) suggests a slightly negative correlation, implying that increased hydration might be associated with slightly lower screen-on time for certain users.
High Variability in App Usage – The data points are widely scattered, indicating that individual behavior varies significantly, and water intake alone is not a strong predictor of digital engagement.
Conclusion:
There is no strong or consistent correlation between hydration levels and app/screen-on time, as indicated by the weak R-squared value and high variability. While some users with higher hydration may engage more with the app, the trend is not statistically significant, suggesting other behavioral or lifestyle factors have a greater influence on app usage patterns.
Q.4: Can we segment users into groups (e.g., high-engagement, low-fitness) to provide tailored recommendations?
This scatter plot segments users based on average app usage time (x-axis) and session duration (y-axis) to identify distinct engagement and workout patterns.
Key Observations:
Distinct User Groups: 
High App Usage, Short Sessions (Brown & Purple) → Users highly engaged with the app but with shorter workout sessions, possibly indicating passive app usage or low physical activity.
High App Usage, Long Sessions (Green & Orange) → Users who frequently use the app and have longer workout durations, likely representing highly engaged fitness enthusiasts.
Low App Usage, Short Sessions (Gray & Yellow) → Users who neither engage much with the app nor work out for long, possibly needing motivation or personalized nudges.
Low App Usage, Long Sessions (Light Green & Dark Orange) → Users with lower app reliance but extended workout durations, indicating self-guided fitness habits.
Answer to the Question:
Yes, we can segment users into distinct groups, such as high-engagement, low-fitness, or self-motivated users, to offer personalized recommendations. For example:
High app, low fitness users → Encourage more active participation through guided workouts or gamification.
Low app, high fitness users → Leverage data-driven recommendations to enhance workout efficiency.
Inactive users → Use targeted notifications, fitness challenges, or incentives to increase engagement.
This segmentation enables data-driven personalization, improving both app engagement and fitness outcomes for different user types.
Tableau Public URL: https://public.tableau.com/views/AnalyzingFitnessandDigitalBehaviorTrends_17424018487610/Insights?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link
I have hidden all the shits associated with both dashboard's One of the worksheets I did not used for any dashboards, so did not hide it. As tableau public do not have much flexibility.
Formula I have used: 
 
* Note: Due to the small dataset size, I have primarily used the Median in visuals, as it provides a more accurate and meaningful representation of central tendency.



