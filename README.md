# YoutubeChannelAnalysis. 
YouTube Channel Analysis

Overview
This repository contains code and data for analyzing a dataset of the top 5000 YouTube channels. The analysis includes data cleaning, exploration, and visualization to gain insights into the YouTube channels' characteristics.

Table of Contents
Dataset
Analysis Steps
Requirements
Usage
Results
Contributors
License
Dataset
The dataset used for this analysis is named "top-5000-youtube-channels.csv." It contains information about the top 5000 YouTube channels, including their ranking, grade, channel name, video uploads, subscribers, and video views.

Analysis Steps
Displaying Data: Displayed the first 5 and last 5 rows of the dataset using df.head() and df.tail().

Data Shape: Found the shape of the dataset, indicating the number of rows and columns.

Data Information: Obtained information about the dataset, including data types and null values, using df.info().

Data Statistics: Calculated overall statistics about the dataframe using df.describe().

Data Cleaning: Replaced '--' values with NaN in the 'Video Uploads' and 'Subscribers' columns.

Checking Null Values: Checked for null values in the dataset using df.isnull().sum() and confirmed that no null values remained.

Data Cleaning (Video Uploads & Subscribers): Cleaned the 'Video Uploads' and 'Subscribers' columns by converting non-numeric values to NaN and then to int64.

Average Views: Calculated the average number of video views for all channels.

Top Channels by Video Uploads: Identified the top five channels with the maximum number of video uploads.

Correlation Matrix: Created a correlation matrix and a heatmap to visualize the relationships between columns.

Grade with Maximum Video Uploads: Determined which grade has the maximum number of video uploads.

Grade with Highest Average Views: Found the grade with the highest average video views.

Grade with Highest Subscribers: Identified the grade with the highest number of subscribers.

Grade with Highest Video Views: Discovered the grade with the highest average video views.

Requirements
To run the code in this repository, you need the following Python libraries:

pandas
numpy
matplotlib
seaborn

Results
The analysis provides insights into the characteristics of the top 5000 YouTube channels, including their video uploads, subscribers, and video views. It also identifies the top channels in terms of video uploads and explores correlations between variables.

Contributors
[Udit Soni]


