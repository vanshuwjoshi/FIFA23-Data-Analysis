# FIFA23 Player Analysis Project

## Overview

This project utilizes Python and various data analysis libraries, including Pandas, Seaborn, Matplotlib, and NumPy, to conduct an Exploratory Data Analysis (EDA) on FIFA23 player data. The primary objectives of the analysis are to determine the best starting 11 players overall, categorized into 1 goalkeeper, 4 defenders, 3 midfielders, and 3 attackers. Additionally, the project aims to identify the best under-21 starting 11 players. The analysis also delves into the relationship between player wages and various attributes such as overall rating, potential rating, best position, national team affiliation, and player value.

## Dataset

The dataset used for this analysis is sourced from the FIFA23 game, providing detailed information about players, including their attributes, positions, ratings, wages, and more. The dataset is loaded and processed using Python's Pandas library for effective data manipulation and exploration.

[Link to dataset](https://www.kaggle.com/datasets/sanjeetsinghnaik/fifa-23-players-dataset)

## Methodology

The project follows these main steps:

1. **Data Loading and Cleaning**: Load the FIFA23 player dataset and perform necessary cleaning procedures to handle missing values and ensure data integrity.

2. **Best Starting 11 Selection**: Identify the best starting 11 players overall, adhering to the traditional distribution of positions on the field. A similar analysis is conducted to determine the best under-21 starting 11 players.

3. **Wage Analysis**: Investigate the relationships between player wages and various player attributes.

    - **Wage vs Overall Rating**: Examine how player wages correlate with their overall performance rating.
    - **Wage vs Potential Rating**: Explore the impact of player potential on their wages.
    - **Wage vs Best Position**: Analyze how a player's best position influences their salary.
    - **Wage vs National Team Name**: Investigate the relationship between player wages and their national team affiliation.
    - **Wage vs Value of the Player**: Explore the correlation between player wages and their market values.

## Observations

The key observations from the analysis include:

1. Among the top 100 highest-earning players, Brazilian, French, English, and Spanish players collectively constitute nearly half, with 13, 12, 12, and 12 representatives, respectively.
2. A substantial salary disparity exceeding 60,000 euros exists between the average earnings of Strikers and Center Backs within the cohort of the 100 highest-earning players.
3. The discrepancy between the market value of Kylian Mbappe (the highest-valued player) and Karim Benzema (the highest earner) exceeds an impressive 126 million euros.
4. In the elite category of the top 10 highest earners, a significant majority of 8 players are of European origin, all of whom are affiliated with European clubs.
5. Both Spanish and English football clubs prominently feature in the upper echelons of player salaries, each boasting 5 representatives within the top 10 earners. Consequently, these nations are notable for their substantial financial investments in player wages.
6. Casemiro, the 10th highest earner, commands an income nearly half that of K. Benzema, the top earner in the list.

## Conclusion

This project provides valuable insights into the FIFA23 player data, revealing the best starting 11 players and under-21 players, as well as shedding light on the relationships between player wages and various attributes. The detailed analysis is documented using Python scripts and Jupyter notebooks, ensuring transparency and reproducibility. Future iterations of this project could include more advanced statistical analyses, machine learning models, and interactive visualizations for enhanced exploration of FIFA player data.

Feel free to explore the Jupyter notebooks provided in this repository for a comprehensive understanding of the analysis process. Your feedback and contributions are highly welcomed.

Thank you for exploring this FIFA23 Player Analysis Project!
