# apps-analysis
This repository contains the work done towards analyzing the Google Play Store apps, exploratory analysis, cluster distributions, types of apps, ratings analysis, machine learning for predicting ratings, and developing insights for future.

### Data Set Context
While many public datasets (on Kaggle and the like) provide Apple App Store data, there are not many counterpart datasets available for Google Play Store apps anywhere on the web. On digging deeper, I found out that iTunes App Store page deploys a nicely indexed appendix-like structure to allow for simple and easy web scraping. On the other hand, Google Play Store uses sophisticated modern-day techniques (like dynamic page load) using JQuery making scraping more challenging.

### Data Set Content
Each app (row) has values for catergory, rating, size, version, genre and more.

### Data Set Acknowledgements
This information is scraped from the Google Play Store. This app information would not be available without it.

### Inspiration and Goal
The Google Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market. These include analysis such as exploratory, sentiment and others. We will be performing these analysis with the help of various librariries in Jupyter Notebook such as pandas, numpy, scipy, and other visualization plots.

###v Data Description
App : Application name
Category : Category the app belongs to
Rating : Overall user rating of the app (as when scraped)
Reviews : Number of user reviews for the app (as when scraped)
Size : Size of the app (as when scraped)
Installs : Number of user downloads/installs for the app (as when scraped)
Type : Paid or Free
Price : Price of the app (as when scraped)
Content Rating : Age group the app is targeted at - Children / Mature 21+ / Adult
Genres : An app can belong to multiple genres (apart from its main category). For eg, a musical family game will belong to Music, Game, Family genres.
Last Updated : Date when the app was last updated on Play Store (as when scraped)
Current Ver : Current version of the app available on Play Store (as when scraped)
Android Ver : Min required Android version (as when scraped)
