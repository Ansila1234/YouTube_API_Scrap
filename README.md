# YouTube_API_Data_Scraper

In this project, we demonstrate the creation of a Python project focused on scraping YouTube data using the YouTube Data API. We utilize the API to gather data and subsequently load it into a Pandas DataFrame in Python for Analysis. At the end, we use the seaborn library to create visualizations based on the extracted data.

## Step 1 
### To collect data from YouTube, you need to set up an API
+ Go to Google Cloud Console.
+ Click on the project dropdown at the top, then "New Project"
+ Enter a project name and click "Create".
+ In the Google Cloud Console navigate to "APIs & Services"> "Library".
+ Search for "YouTube Data API v3" and click on it.
+ Click "Enable".
+ Go to "APIs & Services"> "Credentials".
+ Click "+ CREATE CREDENTIALS" and select "API key".
+ Copy the generated API key. 
## Step 2
+ We create a YouTube API key which will be our credential to acecss YouTube data.
+ Once the API key is generated, we will see how to use this API key to access different YouTube data.
+ We will look at the different sections in the documentation to access different data we need to build this project.
+ We will also look at the sample Python code given by Google to call different resources and methods to fetch YouTube data.

  ![IMG_20240731_120956 (1)](https://github.com/user-attachments/assets/6b815e29-59f2-4b0b-94b0-552a27122d69)

## Step 3
+ Then we will get into writing the Python code to build this project.
+ Here I have used Jupyter Notebook to write my Python code. 1st we will install all the required Python packages.
+ To access YouTube API data in python, we'll need to install the "google-api-python-client" package. You can do this by running the command:'pip install google-api-python-client'.

![14-10-01-332820987-f7a9b437-8516-4739-931a-491d528150e5](https://github.com/user-attachments/assets/29760c4b-a9e7-4868-a954-b0bde711c8a3)


## Step 4
+ 1st we extract channel details from YouTube ie we extract details such as YouTube channel name, total no of subscribers,total views,and total number of videos posted by each channel.
+ We gather these details for a few Data Analyst/ Data Scientist kind of channels and then compare these channel data with each other.
+ We shall see who has the highest number of subscribers and who gets the most views and the amount of videos posted by these channels.
+ We will be loading all of this data into a Pandas data frame and then analyzing it. We will also generate some basic visualization using this data so we can easily compare these multiple channels.

  ![14-11-08-311625946-a46c4987-6972-4403-92e8-6260775fc695](https://github.com/user-attachments/assets/c2971418-afe8-4cfc-9518-e8950d5b8c76)


## Step 5
+ Following step 4, we'll develop a process to retrieve ideo details from specific channels. Intially,we'll focus on extracting data from the Codebasics channel,followed by the Krish Naik channel.
+ We will then analyze this data by loading it into a pandas data frame. At the end, we will create some visualizations using the Seaborn Python library.

   ![14-11-13-311626473-758c0957-ae18-4542-8a30-674607e407b3](https://github.com/user-attachments/assets/4840a7ac-45bd-4cc4-99d1-399e7806fa3f)







      
