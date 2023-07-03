# Analysis of Game Sales

[Notebook Preview](https://nbviewer.org/github/ootho/data_analysis/blob/main/game_analysis/game_analysis.ipynb)

Data Source: [Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales)

## Objective and Research Goals

We have access to historical data on game sales, user and expert ratings, genres, and platforms up until 2016. Our goal is to plan a campaign for the year 2017.

**Objective**
- Identify patterns that determine the success of a game, allowing us to focus on potentially popular products and plan advertising campaigns.

**Tasks and Workflow**
- Prepare the data for analysis.
- Analyze the data.
- Determine potentially profitable platforms.
- Determine potentially profitable genres.
- Explore the relationship, if any, between game ratings and sales.
- Create user profiles for each region.

## Conclusion

We have identified the **most promising platforms** for the year 2017:
- The most promising platforms are `XOne` and `PS4`.
- The platform that is likely to show moderate results but will remain in the market is `PC`.
- The platforms with declining sales and not worth relying heavily on for sales are `3DS`, `PSV`, and `WiiU`.
- In Japan, it makes sense to focus more on local platforms, including `3DS`.

We have also identified the **top-selling game genres**:

Shooter  
Sports  
Platform  
Racing  

Additionally, for North America, `Fighting` should be added to the list, and for Europe, `Simulation`.

The top 5 genres in Japan differ significantly: `Puzzle`, `Role-Playing`, `Fighting`, `Misc`, `Action`.

We conducted an **analysis of sales based on ESRB ratings** and found that the most popular ratings are `M`, `E`, and `T`. However, in Japan, games without ratings are the most popular, indicating a preference for locally produced games. Games without ratings also rank second and third in North America and Europe, respectively.

In the analysis of user data by regions, we found that preferences of North American, European, and Japanese gamers differ not only in platform and genre choices but also in age ratings. The differences between Europe and North America are smaller compared to Japan and the other regions. In Japan, it is advisable to focus on locally produced platforms and games.

During the exploratory data analysis, we discovered that there is a **correlation between critic ratings and game sales**, while the correlation between user ratings and sales is weak. When planning a campaign, it is advisable to consider critic ratings.

Based on hypothesis testing, we found that:
- The average user ratings for Xbox One and PC platforms are the same.
- The average user ratings for the Action and Sports genres are different.