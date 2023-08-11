# Movie Rating Prediction

### Problem Objective :
Using Exploratory Data Analysis techniques, find features affecting the ratings of any particular movie and build a model to predict the movie ratings.

### Steps:
- Import the three datasets
- Create a new dataset [Master_Data] with the following columns MovieID Title UserID Age Gender Occupation Rating. <br>(Hint: (i) Merge two tables at a time. (ii) Merge the tables using two primary keys MovieID & UserId)
- Explore the datasets using visual representations (graphs or tables), also include your comments on the following:<br>
1.User Age Distribution <br>
2.User rating of the movie “Toy Story” <br>
3.Top 25 movies by viewership rating <br>
4.Find the ratings for all the movies reviewed by for a particular user of user id = 2696
- Feature Engineering:<br>
Use column genres:<br>
1.Find out all the unique genres
(Hint: split the data in column genre making a list and then process the data to find out only the unique categories of genres)<br>
2.Create a separate column for each genre category with a one-hot encoding ( 1 and 0) whether or not the movie belongs to that genre.<br>
3.Determine the features affecting the ratings of any particular movie.<br>
4.Develop an appropriate model to predict the movie ratings <br>

### Setup and Installation:
```bash
pip install --upgrade pip
pip install -r requirements.txt
pip list
```

