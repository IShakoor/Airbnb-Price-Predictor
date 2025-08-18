# 🏡 Airbnb Price Predictor

This project showcases a machine learning model that accurately predicts the listing price of Airbnb properties using publicly available data. The goal is to assist hosts in pricing their listings competitively and fairly through data exploration, preprocessing, and the development of an XGBoost-based model. The resulting model demonstrates strong performance, generalizing well to new data and capturing much of the variance in listing prices, making it a useful tool for property pricing.

## 📌 Overview

Airbnb hosts often face challenges in setting competitive prices that balance profitability with demand. Overpricing can lead to fewer bookings, while underpricing may result in lost income. This project takes a data-driven approach to address that challenge by developing a robust machine learning model that predicts Airbnb listing prices based on key features such as location, number of bedrooms, amenities, availability, and user reviews.

By providing data-informed pricing recommendations, the model empowers hosts to optimize their pricing strategies, stay competitive in the market, and ultimately maximize revenue.


## 📊 Data Sources & Structure

Source: https://www.kaggle.com/datasets/whenamancodes/london-uk-airbnb-open-data/data
City: London
Size: 66,679 rows & 18 columns


## 📈 Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) was conducted to uncover key trends, patterns, and relationships within the data. This step helped guide feature engineering and informed modelling decisions by identifying variables with strong potential to influence price.

The following are some examples of visualisations created to support this analysis:

![Missing Values Summary](assets/missing_values.png)

![Feature Correlation Heatmap](assets/heatmap.png)

![Property Type - Price Distribution](assets/property_type_dist.png)

![People Accomodated - Price Distribution](assets/accomodated_dist.png)

🧹 Data Cleaning and Preprocessing

Data Formatting: Correcting data format, including date, money, and correcting data types.
Dropping Columns: Columns with low predictive power were dropped to keep the data focused and prevent noise.
Missing Values: Took a nuanced approach, using different methods for different columns, including removal, median filling, and flagging.
Feature Transformation: Numerical feature which showed large variance were log-transformed to make them easier to handle.
Outlier Handling: Features with a high number of outliers were winsorized to prevent skewed data.
Feature Engineering: 








