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

![Uploading image.png…]()
