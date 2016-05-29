# Facebook Data (January 2016 - April 2016)

This repository contains data about **Facebook** repositories as downloaded from [Github Archive](https://www.githubarchive.org) for the months January 2016 to April 2016.

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

Each folder contains the same data in the following formats: Numpy (`.npy`), JSON (`.json`) and pickle (`.pickle`).
