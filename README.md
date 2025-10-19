# 🏡 Airbnb Listings Analysis (Tableau Dashboard)

### 📊 Project Overview
This project analyzes **Airbnb listings data from 2016** to uncover key trends in pricing, property types, and geographic patterns across different neighborhoods.  
Using **Tableau**, I built an interactive dashboard that visualizes how listing characteristics such as the number of bedrooms, location (zipcode), and availability influence average prices and revenue potential.

---

### 📁 Dataset
**Source:** [Airbnb Listings 2016 Dataset – Kaggle](https://www.kaggle.com/datasets/alexanderfreberg/airbnb-listings-2016-dataset)

**Description:**  
The dataset contains detailed information about Airbnb listings in Seattle, including:
- Listing ID, host details, and property type  
- Bedrooms, bathrooms, and accommodation capacity  
- Location (latitude, longitude, zipcode, neighborhood)  
- Pricing, availability, and review metrics  

---

### 🎯 Objectives
- Analyze **price variation by bedroom count** and **zipcode**
- Understand **revenue trends across time**
- Identify **top-performing neighborhoods** by price and occupancy
- Support hosts and analysts in **data-driven pricing decisions**

---

### 🧩 Key Insights

#### 💰 Average Price per Bedroom
- Prices increase significantly with the number of bedrooms.  
- 1-bedroom listings average **$96**, while 6-bedroom listings exceed **$580** on average.  
- Indicates strong scalability in pricing with larger accommodations.

#### 📆 Revenue for the Year
- Revenue shows consistent growth throughout 2016, peaking around mid-year.  
- The pattern aligns with **seasonal tourism**—higher occupancy during summer months.

#### 📍 Price per Zipcode
- Zipcode **98134** shows the **highest average price**, followed by **98101** and **98109**.  
- Central areas and waterfront neighborhoods command premium pricing.  
- Outlying areas have lower average prices, indicating potential affordability for longer stays.

#### 🏘️ Distinct Count of Bedroom Listings
- Majority of listings are **1-3 bedrooms**, reflecting the dominance of small apartments and short-stay homes.  
- Limited availability of high-bedroom listings suggests an opportunity for multi-family or luxury rentals.

---

### 🧠 Analytical Approach
1. **Data Cleaning & Preparation**
   - Handled missing values, standardized price fields, and derived features like “Revenue per Listing.”
   - Used Excel and Tableau Prep for preprocessing.
2. **Dashboard Design**
   - Combined multiple sheets into an **interactive Tableau dashboard**.
   - Added filters for bedrooms, zipcodes, and time period.
3. **Visualizations Used**
   - Bar chart: Average Price per Bedroom  
   - Line chart: Revenue for Year (Week-over-Week)  
   - Map: Price per Zipcode  
   - Histogram: Distinct Listings Count by Bedrooms  

---

### 🧰 Tools & Technologies
- **Tableau Public** – Data visualization and dashboard building  
- **Excel / Tableau Prep** – Data cleaning and preparation  
- **Kaggle** – Dataset source  

---

### 🚀 Business Impact
- Helps **Airbnb hosts** optimize pricing based on bedroom size and location.
- Assists **property managers** in identifying high-performing neighborhoods for new listings.
- Provides **tourism and hospitality analysts** with data-backed insights into seasonal and geographic price trends.

---

### 📊 Dashboard Preview
<img width="1112" height="550" alt="airbnb_dashboard" src="https://github.com/user-attachments/assets/6397cc18-998b-4337-a83c-3ec15e46b02a" />

🔗 **View Interactive Dashboard:** https://public.tableau.com/views/AirBnB2016_17603471303810/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
