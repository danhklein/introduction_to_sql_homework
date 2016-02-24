introduction_to_sql_homework
============================

This repository is here so students can fork it and add their sql scripts. The repo is intentionally empty.

The total number of posts:

SELECT COUNT(*) FROM posts;

Chooses the bottom 50 scored posts (supposed to be top, I know)

SELECT TOP 50 * FROM posts ORDER BY score;

total number of distinct tags:

SELECT count(DISTINCT tags) FROM posts;

First 10 posts:

SELECT TOP 10 * FROM posts ORDER BY CreationDate;