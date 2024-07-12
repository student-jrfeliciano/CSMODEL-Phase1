# Understanding Video Game Sales: Key Attributes and Regional Trends
 
This group project was completed in partial fulfillment of the course requirements for CSMODEL.

###Dataset Description

**Video Game Sales and Ratings Dataset**
link to dataset: [VG Sales and Ratings | Kaggle](https://www.kaggle.com/datasets/kendallgillies/video-game-sales-and-ratings)

This dataset contains a list of video games with sales greater than 100,000 copies along with critic and user ratings, Sales per region, and ESRB rating. The data is accurate as of January 2017. The dataset contains a total of 17416 entries/observations

**Collection Method**
Data was collected through a combined web scrape from VGChartz and Metacritic along with manually entered year of release values for most games with a missing year of release. The original code was created by Rush Kirubi, but it limited the data to only include a subset of video game platforms. Not all of the listed video games have information on Metacritic, so there are some rows that have missing values.

**Structure**
The Dataset consists of one (1) csv file that contains 15 columns for each variable. Each row represents 1 video game and its details.

Variables included in the dataset:

Name - The game's name
Platform - Platform of the games release
Year_of_Release - Year of the game's release
Genre - Genre of the game
Publisher - Publisher of the game
NA_Sales - Sales in North America (in millions)
EU_Sales - Sales in Europe (in millions)
JP_Sales - Sales in Japan (in millions)
Other_Sales - Sales in the rest of the world (in millions)
Global_Sales - Total worldwide sales (in millions)
Critic_score - Aggregate score compiled by Metacritic staff
Critic_count - The number of critics used in coming up with the critic score
User_score - Score by Metacritic's subscribers
User_count - Number of users who gave the user score
Rating - The ESRB ratings (age rating)