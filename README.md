
# Hotel Booking Exploratory Data Analysis Project 🔥🍁

<p align="center">

  [![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
  
  ![GitHub stars](https://img.shields.io/github/stars/chandusayhi/Hotel_Booking_Analysis)
  ![GitHub forks](https://img.shields.io/github/forks/chandusayhi/Hotel_Booking_Analysis)
  [![GitHub contributors](https://img.shields.io/github/contributors/chandusayhi/Hotel_Booking_Analysis.svg)](https://GitHub.com/chandusayhi/Hotel_Booking_Analysis/graphs/contributors/)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
  [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
</p>  

![image](https://user-images.githubusercontent.com/84115928/140745716-6591df44-5f14-47e4-a557-6959f9591fd3.jpg)

# 📝Problem Statement
Analysis of the following is required by the Sales Team of Hotel Bookings:

    1. Where do the guests come from and perform spatial Analysis?
    2. Which type of hotel has the highest number of cancellations?
    3. How much do guests pay for a room per night?
    4. How does the Price per Night vary over the Year?
    5. Distributions of nights spent at hotels by market segment and hotel type?
    6. Analysing Preference of Guests in terms of 'Meal', What they basically Prefer?
    7. Which are the Most busy Months or In which Months Guests are High?
    8. How long do People Stay at the Hotels?
    9. How many bookings were Cancelled?
    10.Which Month has the Highest Number of Cancellations?

# ⏳ Dataset
Download the dataset for this project from following Link -
* [Hotel Booking Dataset](https://github.com/chandusayhi/Hotel_Booking_Analysis/blob/main/hotel_bookings.csv)

# 📚 Data Analysis
In the datasets, we are provided with 32 columns(Features) of data.

* **hotel** : Hotel (H1 = Resort Hotel or H2 = City Hotel)
* **is_canceled** : Value indicating if the booking was canceled (1) or not (0).
* **arrival_date_year** : Year of arrival date.
* **arrival_date_month** : Month of arrival date.
* **stays_in_weekend_nights** : Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel.
* **stays_in_week_nights** : Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel.
* **adults** : Number of adults.
* **children** : Number of children.
* **babies** : Number of babies.
* **meal** Type of Meal booked. Categories are presented in standard hospitality meal packages.
* **country** : Country of Origin. Countries are represented in the ISO 3155–3:2013 format.
* **market_segment** : Market segment designation. In categories, the term "TA" means "Travel Agents" and "TO" means "Tour Operators".
* **reserved_room_type** : Code of room type reserved.
* **adr** : Average Daily Rate / Price per night.
* **total_of_special_requests** : Number of special requests made by the customer.

Out of the 32 features given in the datasets, 20 are Continuous and 12 (including the target variable) are Categorical features.

# 🖥️ Technologies:
## 🛠️ Tools Used
* Jupyter Notebook is used as IDE.
* Pandas and NumPy are used for Data Manipulation & Pre-processing and Mathematical functions respectively.
* For visualization of the plots, Matplotlib, Seaborn, Plotly are used.
* GitHub is used as version control system.

<p align="center">
  <img src="https://user-images.githubusercontent.com/84115928/141269995-77714aa7-9b0c-4b11-a94c-e1639a0a743b.png">
</p>

# 🎉 Tasks performed under Choropleth Maps Analysis:
* Analysed ***Countries with most guests come from*** using **'Choropleth Maps'**.
* Moreover, Plotted a **"Choropleth Maps with Animation"** for in-depth analysis on Yearly basis.

# 🌱 Some Exciting Glimpse of the Visuals:
![Final Glimpse 1](https://user-images.githubusercontent.com/84115928/141301079-637277f2-a00f-4808-9c38-594b22756412.gif)
![Final Glimpse 2](https://user-images.githubusercontent.com/84115928/141341458-ef8881a7-70b4-4db5-b57e-b3d5795d184b.gif)
![Final Glimpse 4](https://user-images.githubusercontent.com/84115928/141303002-feaed86b-ba9c-4911-8b08-7b54317a59ef.gif)

# 💡 Conclusions
* May-August happens to be the busiest months but so the hotels should target more customers and try to do more business during these times.
* The hotel business tends to make more profit during the rainy season.
* The hotels can keep experimenting with their packages, interiors and amenities as there are more new guests than the repeated guests.
* Majority of the hotels booked are city hotel. Definitely need to spend the most targeting fund on those hotel.
* Majority of the guests are from Western Europe. We should spend a significant amount of our budget on those area.
* The corporates mostly prefer Bed and Breakfast package, due to which the hotel can add more features to the package, also can profit from the customisation feature.
* Set Non-refundable Rates, Collect deposits, and implement more rigid cancellation policies.
* Encourage Direct bookings by offering special discounts.
* "August" Month has the Highest Number of Cancellations followed by "July" & "May".


