**Introduction**

Google Play, also known as the Google Play Store, is an app store run by Google. It is the official platform for downloading apps on Android devices and ChromeOS. Besides apps, Google Play also offers digital content like music, books, movies, and TV shows, which can be accessed on web browsers and Android or iOS devices.

In this Exploratory Data Analysis (EDA), we will analyze data from the Google Play Store to understand various aspects like app types, number of installs, ratings, and more. By examining and manipulating the data, we aim to answer key questions and uncover insights about the app market.

**Data**

The datasets consist of two CSV files: play store data.csv and user reviews.csv.

play store data.csv: Contains 10,841 entries and 13 variables about app details like name, rating, number of reviews, size, price, installs, type (Free/Paid), content rating, and genres.

user reviews.csv: Contains 64,295 entries and 5 variables about app reviews, including app name, translated review, sentiment (Positive/Negative/Neutral), and sentiment polarity score.

**Pie Chart showing distribution of various application category**
Firstly taking out all the categories of various apps on PlayStore and finding the total sum of those respective categories.
Using groupby function to convert "Category" into a dataframe.
Using matplotlib to plot pie chart out of the given information by using specific radius of 4, showing percentage distribution.

![image](https://github.com/user-attachments/assets/c5b0bc59-e58a-44e1-9b22-b955565b29bd)

**Number of Applications for Each Category**

![image](https://github.com/user-attachments/assets/b8a42604-5329-448c-a887-58b52037f9d1)

**Paid and Free Application percentage distribution:**
Applications on the playstore are of two types:

Paid
Unpaid

![image](https://github.com/user-attachments/assets/ceea839b-4574-47d8-b13b-a7eded8dad0f)

**Number of Installs For Each Category**

**Top 10 most installed applications are :**
WhatsApp Messenger,Google Play Books,Subway Surfers,Maps - Navigate & Explore,Gmail,Instagram,Facebook,Google Chrome: Fast & Secure,Google+,YouTube

![image](https://github.com/user-attachments/assets/b9fcab27-c9b7-4a33-9e39-4a7056b79ef8)

**Top 10 highest rated applications are :**
Life Made WI-Fi Touchscreen Photo Frame,Barisal University App-BU Face,EF Academy,CG Jobs,Quran Khmer Offline AY,A-Y Collection,Flippy Axe : Flip The Knife & Axe Simulator,Axe Champs! Wars,Food-Aw - Order Food Online in Aruba,Tozer Devotional -Series 1

![image](https://github.com/user-attachments/assets/395d9c56-5de3-4f77-a097-f247a18fb906)


**Top 5 paid most installed applications are :**
 Hitman Sniper,Minecraft,Five Nights at Freddy's,Bloons TD 5,HD Widgets

 ![image](https://github.com/user-attachments/assets/fcd21253-42d6-4804-8ff3-1026e30992ac)

 **Conclusion**
 Analyzing the data reveals:

1.Google PlayStore features two main types of apps: Free and Paid.
2.Key categories include Family, Tools, and Games.
3.Apps receive ratings and reviews, influencing their popularity.
4.The most common categories are Business, Game, Family, and Tools, with free apps making up 98% of the total.
5.Communication, Games, and Tools are the most installed categories.
6.Apps with ratings between 4.0-4.7 tend to have more reviews and installs, though price doesn't directly impact ratings.
7.Install counts and reviews are strongly correlated and significantly influence app popularity.
Various factors, including app price, ratings, reviews, and install numbers, affect app usage and popularity.


