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
So, I downloaded the DeNormalized dataset to see how the data was gotten from twitter.
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





---

## Findings&Recommendation:
It turns out that the organiser tweeted most, followed by @Richie4love, most people who undergo this training used android most, and tools mentioned while using the hashtags are github, excel, powerbi  and Azure.

