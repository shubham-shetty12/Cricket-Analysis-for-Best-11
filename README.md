# Cricket Analysis for Best 11

## Project Overview:
In this project, the challenge was to create a dashboard of the best T20 team of 11 players. The main objective is to gain insights about batting and bowling performance of different players and based on some criteria select the Top 11.

## Tool used is Power BI Desktop

## Important Questions asked?:
- what are the key performance metircs that can be considered for filtering the best batsman, best bowlers and allrounders?
- how is batsman striking the ball along with scoring runs?
- what is the boundary % rate of player?
- who is the lead run scorer?
- who has taken the highest wickets?
- who has the best economy?
- how is our allrounder performing in both fields?

## Steps Applied:
### Understanding and Transforming Data:
- Gathered the data and analyzed it to understand what all fields are required for certain KPI's.
- Loading the data into Power query and performing transformation or adding new columns as per the requirements.
- Made a rough visual on how the final dashboard should look, it's an iterative process some trial and errors but final visual is always better.

### Cleaning the data:
- Checking data types of each column of all files and making sure each column is assigned with right data type.
- Filtering categorical column to see if there are any same category but with slight variations like an extra space or an Uppercase.
- Replacing such category names with right ones to make our final visual clean and clear.
- Removed duplicate entries and handled null values and cross checked each columns using 'Column qualty'.
- After cleaning the data we will load the data into Power BI front end for building dashboard.
- After data is loaded, we will define relationships between table under "Model View".

### Data Processing and Analysis:
- In this step we will create conditional columns and some new columns like boundary runs for batsman, total free runs given by bowlers in form of wides and no-balls.
- We will also create important measures like :
  #### For Batsman:
  Total runs scored, Batting average, Strike rate , Innings played, Total boundaries ,no of 4s and 6s.
  #### For Bowler:
  Total wickets, Bowling average, Bowling economy, Dot ball % and Wicket rate.
  
-  Created a matrix to display players performance based on the measures and filtered top 5 players from each categories that are Top & Middle order batsman, All rounders and Fast Bowlers.
- Plotted some bar charts for players with most boundaries, most wickets and lowest economy and plotted a scatter plot for batsmans batting average vs Strike rate.

### Dashboard Creation:
- This final dashboard view contains a matrix that has the top 11 players of different categories.
- We have a slicer to replace players in the matrix by players from the list based on categories.
- We have a navigation button on top to navigate throught each unique category.

### Key Insights:
1. Virat Kohli (IND) is the leading run scorer with 296 runs in 6 innings and also has scored the highest number of boundaries.
2. Suryakumar Yadav (IND) is having the highest strike rate of 189 with a batting average of 39.83 in the middle order.
3. Shadab Khan (PAK) is the best allrounder with strike rate of 200 and has taken 11 wickets with an economy of 6.35.
4. Wanindu Hasaranga (SL) is leading wicket taker with 15 wickets and an economy of 6.42.
5. Anrich Nortje (SA) has the lowest economy of 5.37 in fast bowlers and has taken 11 wickets in 2 innings.
