# Facebook Data (January 2016 - April 2016)

This repository contains the data about **Facebook** repositories.

The data is a list of lists (2D array). Each record contains (in the following order):
- Repository name
- Programming language
- CommitCommentEvent
- ForkEvent
- IssueCommentEvent
- IssuesEvent
- PullRequestEvent
- PullRequestReviewCommentEvent
- PushEvent
- WatchEvent

You can get more information about each event int [Github API](https://developer.github.com/v3/activity/events/types/) website

Each folder contains the same data in Numpy (`.npy`), JSON (`.json`) and pickle (`.pickle`) formats.
