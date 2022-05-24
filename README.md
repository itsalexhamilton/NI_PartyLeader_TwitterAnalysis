# NI_PartyLeader_TwitterAnalysis

PROJECT AIM: A high level analysis of the twitter data of each of the elected political party leaders of Northern Ireland, as of May 2022.

**📚 Introduction**

In this project, I aimed to create a high level analysis of each of the seven political party leaders in Northern Ireland, mirroring a similar study referenced down below. The following questions were posed for this study:

1. Which Northern Irish political leader is the most active on the platform?
2. How does each Northern Irish political leader use their Twitter account? As a platform for press releases and statements or to connect with their consitutuency and Twitter following?
3. What are the most frequently mentioned keywords for each Political leader? How do these differ by designation and party affiliation?
4. Are certain party leader's more positive or negative in their sentiment?

In this repository, you can find the Excel files with the Twitter data for each of the seven leaders, the code used to manipulate each of these datasets which were finally uplaoded to a locally hosted PostgreSQL server for further manipulation and analysis.

I have also attached a text file with the basic information to get started for each leader incl


**📚 About BeyondNI Politics**

Here you can find a link to the article, objectives, methodology and findings on the BeyondNI website: tobepopulatedoncepublished.

BeyondNI is a political website aiming to improve poltiical transparency on Northern Irish political matters and to help people become active citizens with the use of technology, research and data. Find out more at: https://www.beyondni.com

**🔨 Tools Used**

Python >= 3.6
Pandas
WordCloud
NLTK.Sentiment.Vader - Sentiment Analzyer
Matplotlib

PostgreSQL

Microsoft Excel

**🔨 Data Sources**

As mentioned, the Excel files containing the 3,200 tweet datasets for each NI political leader have been added to this repository. Please see attached further resources that may assist you in conducting a similar study your area.

**🔨Similar Inspiration Project:**
Inspiration study article: https://towardsdatascience.com/understanding-political-twitter-ce3476a38377
Inspiration study GitHub respository: https://github.com/duncangrubbs/political-sentiment

**🔨Twitter Data Downloads**

The Vicinitas website was used to download the most recent 3,200 tweets for each political leader's twitter: https://www.vicinitas.io

Vicinitas helps track and analyze real-time and historical tweets of social media campaigns and brands on Twitter.

It provides a free tool to download up to 3,200 of the most recent tweets of any Twitter user.

Other methods possible for getting datasets such as Tweepy Python library or interacting with the Twitter API though this project utilized above method.
