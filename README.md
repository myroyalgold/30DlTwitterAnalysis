# 30DlTwitterAnalysis
## ProblemStatement
#30DaysOfLearning and #NG30DaysOfLearning is the hashtags used by the students undergoing training on DataAnalysis, DataScience and Powerplatform Organized by a SeniorCloudAdvocate named @TheOyinbooke along side with his other colleagues from MICROSOFT on twitter.



## ProblemObjective
What is the total tweet made by people on twitter? what is the total number of  users? what is the percentage of devices used? what is the total tweets made by day of the month? what is the total tweets made by weekday and which of the weekday has the most tweets? Who uses the hashtag most?




## DataSourcing: 
The hashtags scripts was posted to the learning platform (discord channel) by the Organiser ( Mr Oyinbooke Olanrewaju). link to the dataset https://aka.ms/30DLDATGitHubRepo Locate the "Twitter Data Web Scrape" folder and you will find both the Jupyter notebook python file and the csv file.


## DataTransformation:
Two data set was given to us,
- 30DLTweets.csv : This is a data that has already been scraped in to csv file.
- 30DLTweetsScrape.ipynb : This is a raw dataset that needs to be generated using python, jupiter anaconda or visual studio.
So, I downloaded the one in ipynb format to see how the data was scraped from twitter.
Firstly, I opened the jupiter anaconda on my system
![2022-07-17](https://user-images.githubusercontent.com/107118603/179413512-506271dc-1689-40c0-9860-8a504ba2ff02.png)

### After running it, it display this
![2022-07-17 (1)](https://user-images.githubusercontent.com/107118603/179416084-d8b8f6ee-6726-4e42-ba63-34d5d7dd5bb5.png)


I select download to open the jupiter notebook python file, click on 30DLTweetsscraped.ipynb and open it
![2022-07-17 (2)](https://user-images.githubusercontent.com/107118603/179416380-e24f823e-9258-4f66-b951-abd16ed7829d.png)

From this, it can be deduced data this code will generate data 
- for the two hashtags namely; #30DaysOfLearning and #NG30DaysOfLearning starting from (01/05/2022 to 0307/2022)
- tweets date, tweet url, tweet username, tweet source, tweets content,  device used, data, tweets, tweets replied and location.

![2022-07-17 (3)](https://user-images.githubusercontent.com/107118603/179416447-30a8c445-d09f-434e-979f-6d22bd3df109.png)

df means dataframe i.e all that has been listed to generate from twitter will be save to df, should incase you want to keep the headings simple and short you can rename it but by following order in tweets.append.
 #### relax !! we re not done scraping yet.
 The question is how will you save it as csv file on your computer? This is very simple, from the image above check the last line of code which is df.to_csv('30DLTweets.csv') which means the name you are saving this file with is 30DLTweets.
 
 #### It's time to use MicrosoftPowerBi
 Open Powerbi Desktop
 In Home tab, click on get data then select from text/csv
 
![2022-07-17 (9)](https://user-images.githubusercontent.com/107118603/179419630-8d54c220-4d7c-4505-94cd-b9306b5785e7.png)


####
Locate the csv file on your system
Click to open it
![2022-07-17 (11)](https://user-images.githubusercontent.com/107118603/179419676-dc1ef01b-9948-4a89-bb3d-f95b73332714.png)

####
Click on transform to check if there are error, null or incorrect spellings.

![2022-07-17 (12)](https://user-images.githubusercontent.com/107118603/179419743-1e268c64-6460-4404-8247-2938b07bc475.png)


####
It will open up the query page, go to home

![2022-07-17 (14)](https://user-images.githubusercontent.com/107118603/179419919-f3fcf77e-7457-402a-9648-be050b948e91.png)

####
Then go to view, check the box beside Column distribution, column profile and column quality.

![2022-07-17 (15)](https://user-images.githubusercontent.com/107118603/179420078-fd7db884-bfc9-40af-950a-33168847aabc.png)
 As seen in this image, the percentage of error value is 0%, null is 0% and the validity of each column is 100% which means the data is cleaned. 
 
#### 
Uncheck the boxes for distribution, quality and profile.
after that;
go to home
select close and apply drop down and click on close and apply.
![2022-07-17 (16)](https://user-images.githubusercontent.com/107118603/179420246-98949eab-d285-4173-8356-18ae96e56b2c.png)


####
The data is loading...

 ![2022-07-17 (17)](https://user-images.githubusercontent.com/107118603/179420273-50905712-4a07-4cfc-a0d8-0e709320b2b6.png)
 
 #### My data is ready for visualisation
 
![2022-07-17 (18)](https://user-images.githubusercontent.com/107118603/179420307-27f1cb81-478d-431c-9c61-281e64c2aebc.png)


## Data Strory Telling Time...
### This page is the first page designed that will direct you to any other pages by the click of a button.
 ![2022-07-17 (4)](https://user-images.githubusercontent.com/107118603/179420347-90f96667-4b24-4635-b05f-a73241a00865.png)
 
 ### 
  This page shows 
 - Totaltweets
 - Total number of users
 -  Top 5 active users
 -  Tweets by day of month
 -  Tweets by day of the week and
 -  Tweets percentage by devices (Devices refer to Source Column from the data uploaded.
 
 ![2022-07-17 (5)](https://user-images.githubusercontent.com/107118603/179420562-46184faa-fbec-4bbc-aa07-2afdd43dd527.png)


 
 ###
This page display other tools mentioned by users, and a table that display the entire actions performed by users. 
![2022-07-17 (6)](https://user-images.githubusercontent.com/107118603/179420577-1b5d8d77-01e3-4b26-907f-9c56d99d846f.png)


### Here is the dashboard
This page gives insights to problem objectives.

![2022-07-17 (7)](https://user-images.githubusercontent.com/107118603/179420672-2416c080-2dac-41a7-8a0a-1c2e99031ee5.png)


## Findings&Recommendation:
It turns out that
- The organiser (Oyinbooke) tweeted most, followed by @Richie4love.
- People tweeted most in june, and wednesday is the most tweeted day about the two hashtags.
- most people who undergo this training used android most
- Tools mentioned while using the hashtags are github, excel, powerbi  and Azure.

