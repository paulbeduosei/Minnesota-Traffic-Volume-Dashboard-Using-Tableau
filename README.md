# Minnesota-Traffic-Volume-Dashboard-Using-Tableau
🚦 Minnesota Traffic Volume Dashboard

Client: Minnesota Department of Transportation (MnDOT)

📌 Project Overview
This project analyzes traffic sensor data to help MnDOT understand when, why, and under what conditions traffic volume changes. The dashboard focuses on time trends, weather impact, and holiday effects.

🎯 Business Questions

How does traffic volume vary throughout the year and day?

How do different weather conditions impact traffic volume?

How does traffic behavior change on holidays?

📂 Key Data Fields

date_time – timestamp of traffic reading

traffic_volume – number of vehicles

weather_main – primary weather condition

holiday – holiday indicator

Custom time fields were created from date_time to support hourly, daily, monthly, and yearly analysis.

📊 Dashboard Components

1️⃣ Traffic Volume Over Time

Dimensions: Year, Month, Day, Hour

Measure: Traffic Volume

Purpose: Identify seasonal trends and peak travel hours.

2️⃣ Traffic Volume by Weather

Dimensions: Weather Condition, Date Time

Measure: Traffic Volume

Purpose: Understand how weather influences driving behavior.

3️⃣ Traffic Volume by Holiday

Dimensions: Holiday, Date Time

Measure: Traffic Volume (Custom Holiday Metric)

Purpose: Highlight holiday-specific travel patterns.

🧠 Key Insights

Traffic peaks during weekday rush hours

Clear and cloudy weather sees the highest volume

Major holidays significantly alter traffic behavior

🛠 Tools Used

Tableau

Calculated fields & filters

Time-series aggregation

Exploratory data analysis

🚀 Skills Demonstrated

Client-focused dashboard design

Translating business questions into visuals



Time-based feature engineering

Insight storytelling
