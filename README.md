# Gaming Behavior Analysis

Project Overview

This project analyzes player behavior within a gaming environment to uncover key trends, insights, and actionable recommendations. The analysis identifies factors influencing player retention, engagement, and purchasing behavior. The goal is to provide recommendations to improve player experience, retention, and game revenue.

Problem Statement

Player retention is critical for gaming companies as it directly impacts revenue and game longevity. Understanding player engagement patterns can help identify drop-off points, optimize game difficulty, and target promotions effectively. This project aims to analyze player behavior to discover actionable insights for enhancing player experience and engagement.

Data Description

Source: Predict Online Gaming Behavior Dataset

Size: 40,035 rows, 13 columns

Features:

Player ID: Unique identifier for each player.

Age: Player age.

Gender: Player gender.

Location: Player's geographic location.

Game Genre: Genre of the game being played.

Play Time Hours: Average playtime per session.

In-Game Purchases: Indicator of whether the player makes in-game purchases (0 = No, 1 = Yes).

Game Difficulty: Difficulty level of the game being played.

Sessions Per Week: Total sessions played per week.

Avg Session Duration (Minutes): Average session duration in minutes.

Player Level: Player's current game level.

Achievements Unlocked: Number of achievements unlocked by the player.

Engagement Level: Engagement category (High, Medium, Low).

Tools Used

Excel: Used for data cleaning and initial exploration.

SQL: Used for data extraction, cleaning, and analysis.

Tableau: Used for data visualization and dashboard creation.

Data Cleaning Steps (Excel)

Null and Duplicate Check:

Identified and handled missing values through imputation or removal.

Removed duplicate player records to ensure unique entries.

Column Formatting:

Standardized data formats (e.g., text to integers, rounding numerical columns).

Ensured consistency in categorical data for analysis and visualization.

New Metric Creation:

Age Group: Categorized players into age groups: <20, 20-30, 30-40, 40+.

Purchase Category: Grouped in-game purchases into No Purchases, Low Purchases, Moderate Purchases, and High Purchases.

Purchases Per Session: Calculated average purchases per session.

Achievements Per Session: Measured player engagement by dividing total achievements by the number of sessions.

Error Handling:

Addressed division-by-zero errors in session-based calculations by using conditional logic to avoid invalid results.

SQL Analysis Steps

Player Demographics:

Segmented players into age groups and analyzed player participation by gender.

Weekly Sessions by Age Group and Gender:

Calculated the average weekly sessions for different age groups and genders.

Popular Game Genres:

Identified the top 5 game genres based on total playtime.

Game Difficulty Analysis:

Measured player engagement at different difficulty levels.

Regional Analysis:

Measured purchases and playtime by player location.

Player Levels and Achievements:

Analyzed player progression and achievements at different levels.

Purchase Category Insights:

Identified trends and behavior of players across different purchase categories.

Tableau Process

Data Import:

Imported the cleaned dataset from SQL into Tableau for visualization.

Data Preparation:

Verified column data types and configured filters and parameters for analysis.

Visualization Design:

Player Demographics Dashboard: Displayed player count and engagement by age, gender, and location.

Retention Funnel: Visualized player progression from onboarding to sustained engagement.

Purchases Dashboard: Showcased in-game purchase trends, including purchase categories and player behavior.

Heatmap of Player Activity: Illustrated player activity by time of day and day of the week.

Game Genre Dashboard: Displayed the most popular game genres with engagement trends.

Interactive Features:

Added filters for player age, gender, location, and game genre.

Added hover-to-inspect tooltips and slicers for real-time insights.

Dashboard Deployment:

Published the dashboard to Tableau Public, providing stakeholders with access to interactive insights.

How to Run This Project

Download the Dataset:

Download the dataset from the Kaggle dataset link.

Data Cleaning:

Open the dataset in Excel to check for nulls and duplicates.

Format and create new metrics as outlined in the Data Cleaning Steps section.

SQL Analysis:

Load the cleaned dataset into a SQL environment.

Run the SQL scripts for analysis as outlined in the SQL Analysis Steps section.

Tableau Visualization:

Import the SQL output into Tableau.

Create dashboards according to the Tableau Process section.

Publish the dashboard on Tableau Public for stakeholder access.

Business Recommendations

Enhance the Onboarding Experience: Players who complete tutorials are more likely to stay engaged, so refining the onboarding process could improve retention.

Targeted Promotions During Weekends: Player activity peaks during weekends, so offering weekend-exclusive events or rewards could increase engagement.

Difficulty Balancing: Players often drop off after failing levels multiple times. Providing level-specific tips or support could reduce player churn.

Player Segmentation for Marketing: Segment players by age, gender, and location to create personalized marketing campaigns and promotions.

Author

Name: Gabe Puente

Role: Aspiring Data Analyst

LinkedIn: Gabe Puente LinkedIn

If you have any questions or suggestions for improvement, feel free to reach out!

