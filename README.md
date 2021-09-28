# Movie Recommendation Engine in Apache Spark

### Overview
In this project, I built a movie recommendation engine using **Alternative Least Squares** [(ALS)](https://spark.apache.org/docs/latest/ml-collaborative-filtering.html) algorithm in model-based collaborative filtering and Apache Spark APIs on [MovieLens movie rating dataset ](https://grouplens.org/datasets/movielens/latest/) of size ~762MB, to predict the ratings by users, give recommendations accordingly to users on request, and find similar movies for a specific movie of interest.

The whole project code and report can be found at the Databricks ipynb. The outline of the report is organized as follows: Part 1 data ETL and OLAP, Part 2 model training and evaluation on sample data, Part 3 model deployment on full data, Part 4 model applications, Part 5 complete walkthrough of the code.

Here's a high-level summarization chart showing the workflow and pipeline in the project:

![alt text](https://github.com/zcheng233/Movie-Recommendation-Engine-in-Spark/blob/main/flowchart.png)
