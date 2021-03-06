# Deep Learning  - Tweet-sentiment-Analysis project


This is the final solution of the project 'Deployment' which consists in deploying a Sentiment Analysis model using RNN for Tweet Sentiment Analysis. The notebook and Python files provided here result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on COVID related Tweets.

In the final architecture AWS API Gateway and AWS Lambda functions is used as well. The application architecture diagram is:

![Web app Diagram](./Web&#32;App&#32;Diagram.svg) 


# General Outline

Step 1: Downloading the data

Step 2: Preparing and Processing the data

Step 3: Upload the data

Step 4: Build and Train the PyTorch Model

Step 5: Testing the Model

Step 6: Deploying the model for testing

Step 7: Use the model for testing

Step 6 Deploy the model for the web app

Step 7 Use the model for the web app


## Web app final result

The final project is executed in a html page which is deployed on IBM Cloud.

https://tweet-app.mybluemix.net

## Project demo Video Link https://youtu.be/lITu6mjgqsY

Sources used in video to check the sentiment of the tweet.

https://twitter.com/i/events/1240662046280048646?lang=en

https://twitter.com/hashtag/Covid19?src=hashtag_click

https://www.hindustantimes.com/india-news/maharashtra-minister-tweets-negative-covid-19-test-report-slams-rumours/story-HWE96RBxYZVSMYWKcyuxrL.html

Drive link for video(if youtube link doesn't work) 
https://rb.gy/92rrjq


NOTE - I've also used different cloud services because IBM cloud account provided by smartinternz is the limited free student Tier and has lots of limitation regarding instances and I needed powerful GPUs for my project which were not availabe in my free Student Tier with IBM.

