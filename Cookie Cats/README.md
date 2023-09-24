# A/B Testing for Cookie Cats Game

## Project Description
This project conducts an A/B test on the mobile puzzle game, Cookie Cats, to analyze the impact of moving the gate from level 30 to level 40 on player engagement and retention. The dataset includes user information, version assignment (gate_30 or gate_40), number of game rounds played, and retention data.

## Objectives
- Analyze the difference in engagement (sum of game rounds played) between users in the control group (gate_30) and the treatment group (gate_40).
- Compare the 1-day and 7-day retention rates between the two groups.

## Dataset
The dataset contains the following columns:
- `userid`: Unique identifier for each player.
- `version`: Group assignment (gate_30 or gate_40).
- `sum_gamerounds`: Number of game rounds played by the player during the first 14 days after install.
- `retention_1`: Player returned to play 1 day after installing (True/False).
- `retention_7`: Player returned to play 7 days after installing (True/False).

## Analysis Steps
1. **Data Exploration**
   - Load the dataset and explore its structure and contents.
2. **Engagement Analysis**
   - Visualize the distribution of `sum_gamerounds` for both groups.
   - Calculate descriptive statistics.
   - Perform the Mann-Whitney U test to compare engagement.
3. **Retention Rate Analysis**
   - Calculate 1-day and 7-day retention rates for both groups.
   - Perform Chi-squared tests to compare retention rates.

## Results
- **Engagement**: Some evidence of a difference in engagement between the two groups, but not strongly significant.
- **1-Day Retention**: No statistically significant difference between the two groups.
- **7-Day Retention**: Statistically significant higher retention in the `gate_30` group.

## Implications
The results provide insights into player behavior and the impact of game design changes on engagement and retention, guiding future decisions on game level design.
