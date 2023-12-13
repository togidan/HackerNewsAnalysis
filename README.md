## Goal

There are 2 goals for this project:
1. Compare the two types of posts, Ask HN and Show HN and figure which one gets more comments on average
2. Figure out if posts at a certain time receive more comments on average


### Dataset
The dataset can be found on [Kaggle](https://www.kaggle.com/hacker-news/hacker-news-posts). It is a subset of data that has the following columns:
* id: the unique identifier from Hacker News for the post
* title: the title of the post
* url: the URL that the post links to, if the post has a URL
* num_points: the number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes
* num_comments: the number of comments on the post
* author: the username of the person who submitted the post
* created_at: the date and time of the post's submission
