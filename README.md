# IPL Data Analysis

This project delves into the Indian Premier League (IPL) 2017 cricket dataset to extract meaningful insights through data manipulation, transformation, analysis, and visualization techniques. It focuses on exploring various aspects of the IPL using a dataset comprising CSV files stored in an S3 bucket. These files cover match-related information, including ball-by-ball details, match summaries, player profiles, and team details.

## Data Sources

The analysis utilizes a dataset comprising CSV files stored in a public AWS S3 bucket, covering a range of match-related information, including:

- Ball_By_Ball.csv
- Match.csv
- Player.csv
- Player_match.csv
- Team.csv

You can find the dataset here: https://www.kaggle.com/datasets/raghu07/ipl-data-till-2017.

## Tools and Technologies

- **PySpark:** For data processing and analysis.
- **Matplotlib & Seaborn:** For data visualization.
- **Databricks:** For efficient environment setup and utlizing spark.
- 
![image](https://github.com/user-attachments/assets/033ed193-99d5-4833-b81d-7237bf1f6e07)

## Analysis and Insights

The project involves various analysis tasks such as:

- Calculating total and average runs scored in each match and innings.
- Identifying high-impact balls (scoring more than 6 runs or resulting in a wicket).
- Analyzing the impact of winning the toss on match outcomes.
- Identifying top-scoring batsmen and most economical bowlers in each season.
- Visualizing key metrics and insights using charts and graphs.

## How to Run

1. **Set up Environment:** Install PySpark, Matplotlib, and Seaborn in your environment. Tip: Use databricks compute cluster for large datasets and efficient setup.
2. **Data Loading:** Load the IPL dataset CSV files from the S3 bucket into PySpark DataFrames.
3. **Data Transformation:** Apply transformations to clean, enrich, and prepare data for analysis.
4. **Analysis and Visualization:** Execute analysis tasks and visualize the results.

## Results

The analysis provides insights into various aspects of the IPL, such as:

- Top-scoring batsmen and most economical bowlers.
- Impact of winning the toss on match outcomes.
- Player performance trends over seasons.
- Key venue statistics.
- Frequent dismissal types.

## Conclusion

This project demonstrates the potential of data analysis to extract valuable insights from a large dataset such as the IPL. The findings can be further used to understand and predict team performance, player performance, and match outcomes.


## Tools Used
![image](https://github.com/user-attachments/assets/e9350f92-0013-4648-94a7-bf91c7524716)
![image](https://github.com/user-attachments/assets/da1970f0-1ba9-453d-9056-f776e58885a0)
![image](https://github.com/user-attachments/assets/17faa924-53ff-4cd9-aa4b-3ce08aaa7dee)
![image](https://github.com/user-attachments/assets/35d5c549-01ba-4ddd-b0bc-b3a09ede4c88)



## Future Enhancements
- Analyze the impact of player nationality on team performance.
- Understanding consistency of teams' performance through each season.
