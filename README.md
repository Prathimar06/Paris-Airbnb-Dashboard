# 📊 Paris Airbnb Market Analysis Dashboard

### [➡️ View the Live Interactive Dashboard on Power BI Service](https://app.powerbi.com/...) 
*`[**CRITICAL:** Publish your dashboard to Power BI Service ("Publish to web") and paste the public link here. This is the most important link in your project.]`*

![Dashboard Demo](Images/Paris%20Dashboard_.gif)
*`[Note: I've automatically formatted the link to your GIF. The '%20' handles the space in the filename.]`*

---

> This project presents an in-depth analysis of the Paris Airbnb market. The interactive Power BI dashboard visualizes key metrics on pricing, availability, and property types across different Parisian neighborhoods (arrondissements) to uncover actionable insights for hosts and market analysts.

---

### ## 🛠️ Tech Stack & Tools

* **Data Visualization & Dashboarding:** Microsoft Power BI
* **Data Cleaning & Transformation:** Power Query, Python (with Pandas) *`[Mention the tools you used for cleaning]`*
* **Data Source:** Public Airbnb Scrape Data (`listings.csv`, `Paris Cleaned Dataset.csv`)

---

### ## ✨ Dashboard Showcase

This dashboard is composed of four distinct pages, each designed to answer specific business questions.

#### Page 1: 🗺️ Market Overview
*`[This should be your main summary page. Describe its purpose.]`*
This page provides a high-level, geographical overview of the market, showcasing average prices and listing density across all 20 arrondissements of Paris.

![Market Overview](Images/Page1.png)

#### Page 2: 💲 Pricing & Availability Analysis
*`[Describe what this page shows. Is it about trends over time?]`*
This view allows for a deep dive into pricing strategies and booking trends, analyzing how nightly rates, cleaning fees, and availability fluctuate by season and neighborhood.

![Pricing Analysis](Images/Page2.png)

#### Page 3: 🏠 Property Type Deep-Dive
*`[Describe this page. Does it compare apartments vs. private rooms?]`*
This section breaks down the market by property type (Entire home/apt, Private room, etc.), comparing their distribution, pricing power, and guest ratings.

![Property Type Analysis](Images/Page3.png)

#### Page 4: 📝 Host & Review Insights
*`[Describe the final page. Is it about superhosts or review scores?]`*
This page focuses on host-level metrics and guest satisfaction, analyzing the characteristics of top-rated "Superhosts" and correlating review scores with property features.

![Host Insights](Images/Page4.png)

---

### ## 📈 Key Insights Discovered

My analysis of the data revealed several key findings:

* **Insight 1: Pricing Power of Central Arrondissements:** *`[Example: Properties in the 6th (Saint-Germain-des-Prés) and 7th (Eiffel Tower) arrondissements command a 45% higher average nightly rate than the city average.]`*
* **Insight 2: High Demand for "Entire Home/Apt":** *`[Example: "Entire home/apt" listings, while only making up 60% of properties, generate over 85% of the total estimated revenue, indicating massive demand.]`*
* **Insight 3: August is the Peak Booking Month:** *`[Example: There is a clear seasonal trend, with booking prices and occupancy peaking in August, likely driven by summer tourism.]`*

---

### ## 📂 Data & Source Files

* **`Paris_Airbnb.pbix`:** The Power BI source file containing all the data models, queries, and report pages.
* **`data/` folder:** Contains the raw (`listings.csv`) and cleaned (`Paris Cleaned Dataset.csv`) data used for the analysis.

---

### ## 🤔 Challenges & Future Improvements

* **Challenge:** *`[Example: The initial dataset contained significant missing values in the 'price' and 'last_review' columns, which required careful imputation and cleaning in Power Query to ensure data quality.]`*
* **Future Work:** *`[Example: In the future, I would like to integrate data from the Paris Metro system to analyze how proximity to a station impacts a listing's price and occupancy.]`*
