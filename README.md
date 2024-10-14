♟️ A/B Testing Analysis: Chess Games ⚔️
Project Overview 🧐
This project dives into the world of A/B Testing to analyze chess games and discover differences in game characteristics between rated and non-rated games. Using a dataset of over 20,000 games, we investigate whether rated games tend to have longer or shorter durations (in terms of turns) compared to non-rated games. The goal is to statistically test whether there's a significant difference in the number of turns taken in rated and non-rated chess games.

Task Summary 📝
Task Name: A/B Testing Analysis
Intern ID: CA/O3/45464
Assigned By: CodeAlpha Internship
Dataset Description 📊
The dataset consists of chess game records with the following relevant attributes:

Rated: Whether the game is rated (True/False)
Turns: Number of turns in the game
White Rating: Rating of the player using the white pieces
Black Rating: Rating of the player using the black pieces
Victory Status: The method by which the game was won (e.g., outoftime, resign, mate)
Winner: The winner of the game (white/black)
Analysis Process 🛠️
Data Cleaning and Preprocessing 🧹
Data Type Conversion: Converted the white_rating and black_rating columns to numeric types to facilitate analysis.
Handling Missing Values: Dropped any rows with null values to ensure accuracy in the analysis.
Grouping 🧮
Grouped the data into Group A (rated games) and Group B (non-rated games) based on the rated column.
Metrics Calculation 📈
Calculated the mean number of turns for both groups:
Mean Turns for Rated Games: 61.96
Mean Turns for Non-Rated Games: 54.27
Hypothesis Testing 🎯
Conducted a t-test to evaluate whether the difference in mean turns between rated and non-rated games is statistically significant.
Null Hypothesis (H₀): There is no significant difference in the mean number of turns between rated and non-rated games.
Alternative Hypothesis (H₁): There is a significant difference in the mean number of turns between rated and non-rated games.
Results 📊
T-Statistic: 12.89
P-Value: 6.56e-38
Since the p-value is much smaller than the significance level (α = 0.05), we reject the null hypothesis, indicating a significant difference in the number of turns between rated and non-rated games.
Visualization 🎨
We visualized the distribution of turns for both groups using histograms:

Group A (Rated Games): Represented in black.
Group B (Non-Rated Games): Represented in green.

This graph clearly shows the distribution of turns for both rated and non-rated games, providing visual evidence of the difference.

Conclusion 🚀
This A/B testing analysis reveals that rated chess games tend to have more turns on average compared to non-rated games. The significant difference suggests that players in rated games might engage in more strategic play, leading to longer game durations.
