# Analyze-YouTube-Data-using-YouTube-API
## Table of Contents:
* Introduction
* Prerequisites
* How to get an API key
* Create an environement
* Description and documentation
* Conclusion

## Introduction
YouTube is one of the most important and powerful toolsocial media platforms for both consumers and businesses. About 122 million users consume a billion hours of video every day and 500 hours of content are uploaded every minute. Moreover, YouTubers spends millions of hours of video every day, and three million of those hours are spent watching ads. These factors made YouTube a tremendous valuable source of data, a treasure for us the data analysts.Overall, YouTube data is a rich collection of continually changing user, channel, and content interactions.
There are three different APIs of Youtube to easily extract information about virtually everything stored in their servers, so these petabytes of information can be leveraged to get useful insights of a wide variety of interesting problems.There are a lot of APIs available by google with each of them having their application in various fields which makes the work easier while the development of mobile applications, website development and many more. One such API is the YouTube Data API v3 by google. It provides features including: 
* Search for videos,
* Retrieve information of videos from youtube either of channel or of particular video i.e. likes/dislikes, comments, etc.
* Can start the youtube video directly from the application.
In this project, the data of several music channels has been extracted with the help of the API and analysised considering different prespective.

## Prerequisites
* Google account
* Python 
* Libaries: Pandas(analysis), Seaborn(visualization)
* The Google APIs Client Library
pip install --upgrade google-api-python-client 
* The google-auth-oauthlib and google-auth-httplib2 libraries for user authorization. 
pip install --upgrade google-auth-oauthlib google-auth-httplib2

## How to get an API key
The project is started with the "google developer console" and "create a project". Once the project is created we need to enable the APIs and services by accessing the library. The library has different options sonce it is the google cloud. The YouTube option is then chosen(Youtube data API v3) and enable it.Finally the API key must be created. Click on "credentials", then "create credentials" and the API Key is generated. Once the project is created we need to enable the APIs and services by accessing the library. The library has different options sonce it is the google cloud. The YouTube option is then chosen(Youtube data API v3) and enable it.Finally the API key must be created. Click on "credentials", then "create credentials" and the API Key is generated:
"AIzaSyD-hADklXrfLe0RSBCkqq16Nl2Wfc7bkW8"

## Create an environement
A new virtual environment named youtube has been created for this project through using anaconda

## Description and documentation
this project has been divided into two parts. In the first part, channel details such as youtube channel name, total no of subscribers, total views and total number of videos posted by each channel has been extracted.Few famous Music channel have been used to gathe these details and then compared these channel data with each other. The highest subscriber and most views and the amount of videos posted by these channels has been analyzed.All of these data have been laded into a pandas dataframe and then has been analyzed. Some basic visualizations have been generated using the data for comparing these multiple channels.

In the second part a function has been built to extract video details from a particular channel. The details such as video title, total views each video has got, total number of likes, dislikes and comments each video has got have been extracted. Then the data from the videos posted by a particular channel has been analyzed in same process .


