# Boardgames

## Project Overview 
Welcome to the Board Game repository! In this "Board Game Analysis and Visualization" project, we aim to analyze and visualize data related to board games, including their titles, descriptions, ratings attributes. This project provides valuable insights into popular keywords, common themes, and the highest-rated board games.

<details>
<summary>Project Objectives </summary>
<text> 
  
  1. Data Collection: Gather data about board games from reliable sources such as BoardGameGeek or other board game databases. This data should include game titles, descriptions, ratings, and relevant attributes.

  2. Data Preprocessing: Clean and preprocess the collected data to remove duplicates, handle missing values, and prepare it for analysis.

  3. Keyword Analysis: Analyze the descriptions of board games to identify common keywords and themes. Special attention is given to specific keywords, such as 'war,' to understand their prevalence and significance.

  4. Visualization: Create visualizations to represent the data in an understandable and insightful manner. This includes bar charts, word clouds, and tables to display the most common words and the highest-rated games.

  5. Keyword Exclusion: Allow users to exclude specific words from the analysis, such as 'the,' 'game,' and 'of,' to provide more relevant insights.

  6. Top-Rated Games: Identify and list the top-rated board games containing specific keywords in their titles. Limit the results to a user-defined number, e.g., the top 10.

  7. Tabular Display: Present the results, including the list of top-rated games, in a table format using libraries like pandas and tabulate for better readability.

  </text>
</details>

## Repository Contents 
- Project.ipynb: The code on how to analyse the dataset with user friendly visuals
- README.md: You are currently reading this README file, which provides an overview of the project.



## Tools and Technologies:

- Python for data collection, analysis, and visualization

- Libraries like pandas, nltk, and matplotlib for data manipulation and visualization
- Web scraping tools if data is collected from online sources
- tabulate library for tabular display
- Jupyter Notebook or Colab for presenting results and user interaction.

##  Data Description
The board game dataset is organized into one table, with 6 attributes.

<details>
<summary> Attributes Description </summary>
<text> 

- _Game Title_ : The title of the board game.
  
- _Descriptions_ : A textual description of the board game, including information about its theme, gameplay, and features. 

- _Greek Rating_ : A numerical rating representing the game's overall quality or user satisfaction.
- _Average Rating_:  The average user rating or score assigned to a board game.
- _Votes_:  The number of votes or user reviews submitted for a board game.
- _Release Years_: The years in which board games were initially released or made available to the public


</text>
</details>


## Insights
Here, you'll discover 6 fun facts with the board game
1. Most Common Words in Board Game Descriptions 1
2. Most Common Words in Board Game Descriptions 2
3. Most Common Word in the game title
4. Trends in the Release of New Board Games Over the Last Five Decades
5. Game with the greatest variance between 'Greek Rating' and 'Average Rating'
6. Game with the number of votes  


## Reference 
Resources: https://boardgamegeek.com/

