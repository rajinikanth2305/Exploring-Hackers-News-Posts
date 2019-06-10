# Exploring-Hackers-News-Posts
In this project, I'll compare two different types of posts from Hacker News, a popular site where technology related stories (or 'posts') are voted and commented upon. The two types of posts we'll explore begin with either Ask HN or Show HN.

Users submit Ask HN posts to ask the Hacker News community a specific question, such as "What is the best online course you've ever taken?" Likewise, users submit Show HN posts to show the Hacker News community a project, product, or just generally something interesting.

I'll specifically compare these two types of posts to determine the following:

Do Ask HN or Show HN receive more comments on average?
Do posts created at a certain time receive more comments on average?

You can find the data set [here](https://www.kaggle.com/hacker-news/hacker-news-posts), but note that it has been reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that did not receive any comments, and then randomly sampling from the remaining submissions. Below are descriptions of the columns:

id: The unique identifier from Hacker News for the post<br>
title: The title of the post<br>
url: The URL that the posts links to, if it the post has a URL<br>
num_points: The number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes<br>
num_comments: The number of comments that were made on the post<br>
author: The username of the person who submitted the post<br>
created_at: The date and time at which the post was submitted<br>

