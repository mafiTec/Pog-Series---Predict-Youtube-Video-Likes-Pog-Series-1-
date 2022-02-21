# Pog-Series---Predict-Youtube-Video-Likes-Pog-Series-1-



skills used: python,sklearn,pandas,numpy,matplotlib, Seaborn, lightgbm

project Description Youtube Video View Count Prediction
Training/Test Data (train.parquet/test.parquet)
id - Unique Identifier for the row (combindation of video id and trending date)
video_id - Unique Identifier for the video
title - Title of the Video
publishedAt - Datetime the video was published
channelId - Id of the channel hosting the video
channelTitle - Title of the channel hosting the video
categoryId - Video category
trending_date - Date on which we are predicting the view count
tags - Video Tags
view_count - Number of views as of the trending date
likes - Number of likes as of the trending date Not provided in the test set
dislikes - Number of dislikes Not provided in the test set
comment_count Comment Count Not provided in the test set
thumbnail_link Link to the thumbnail of the video.
comments_disabled True/False if comments are disabled.
ratings_disabled True/False if ratings are disabled.
duration_seconds The duration of the video.
has_thumbnail True/False if the thumbnail is available for the video.
description Video description
target TARGET COLUMN - this is the ratio of like to view coun
