
# 🏠 Airbnb Data Analysis

## 📌 Project Overview

This project focuses on analyzing Airbnb listing data to uncover pricing patterns, host behavior, customer engagement, and location-based insights. The objective is to perform structured data cleaning, exploratory data analysis (EDA), and visualization to derive actionable business insights.

---

## 🎯 Objectives

* Analyze price distribution across different neighborhoods
* Study host verification and listing concentration
* Evaluate review trends and customer engagement
* Identify factors influencing listing price
* Extract meaningful insights using data visualization

---

## 📂 Dataset Description

The dataset includes the following key attributes:

* id
* name
* host_id
* host_identity_verified
* neighbourhood_group
* neighbourhood
* latitude & longitude
* country & country_code
* instant_bookable
* cancellation_policy
* room_type
* construction_year
* price
* service_fee
* minimum_nights
* number_of_reviews
* last_review
* reviews_per_month
* review_rate_number
* calculated_host_listings_count

---

## 🧹 Data Cleaning Performed

* Removed duplicate entries
* Handled missing values
* Standardized column names
* Converted price and service fee to numeric format
* Formatted date columns properly
* Removed outliers in pricing (if applicable)

---

## 📊 Exploratory Data Analysis (EDA)

### 1️⃣ Price Analysis

* Distribution of listing prices
* Price comparison by room type
* Neighborhood-wise average pricing

### 2️⃣ Host Analysis

* Verified vs non-verified host distribution
* Host listing count analysis
* Impact of host activity on pricing

### 3️⃣ Review Analysis

* Reviews per month trend
* Relationship between rating and price
* High-engagement listing identification

### 4️⃣ Location Insights

* Neighbourhood group performance
* Geographic clustering of listings

---

## 📈 Key Insights

* Entire homes/apartments tend to have higher pricing.
* Verified hosts generally maintain higher review rates.
* Listings with higher reviews per month often show competitive pricing.
* Certain neighbourhood groups dominate in listing concentration.
* Price outliers significantly affect overall distribution and require normalization.

---

## 🛠 Tools & Libraries Used

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly

---

## 🧠 Skills Demonstrated

* Data Cleaning & Preprocessing
* Handling Large Datasets
* Feature Understanding
* Statistical Exploration
* Data Visualization
* Insight Extraction

---

## ▶️ How to Run

```bash
git clone https://github.com/0m-08/Data-Analytics-Projects.git
cd AirBNB
pip install -r requirements.txt
```

Open the Jupyter Notebook and run all cells.

---

## 📌 Future Improvements

* Apply regression models for price prediction
* Build an interactive dashboard (Streamlit / Dash)
* Perform clustering analysis for neighborhood segmentation
* Deploy as a mini data analytics portfolio project

* Make it more **resume-impact oriented with quantified statements**
* Make a shorter minimalist version
* Or create `requirements.txt` properly for this project

Tell me which direction you want to position this project in.
