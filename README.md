# Data Collection and Analysis of Movie Data

| <span>      |                           |
|:----------- |:-------------------------:|
| Task        | Semestral project         |
| Course      | Data Processing in Python |
| Course code | JEM207                    |
| Authors     | Jan Hanzal & Eric Zila    |

## Project description

In our project, we are scraping the international movie database: [iMDb](https://www.imdb.com). We are interested in creating a dataset of movies along with their directors, actors, ratings, revenues, and other data that can be further used for data analysis. We will be primarily interested in finding the determinants of movie performance.

After scraping the data using the beautifulSoup package, we download them into a .csv file and perform further analysis on them. Namely, we first perform a descriptive analysis to find out potential problems with the data, such as outliers and missing values. Then, we turn to an exploratory and confirmatory analysis. Here, we first investigate the relationship between movie genre and the worlwide gross revenues by performing a basic linear regression and applying a decision tree algorithm. Finally, we test the hypotheses that rating count and rating score have positive effects on movie performance.
