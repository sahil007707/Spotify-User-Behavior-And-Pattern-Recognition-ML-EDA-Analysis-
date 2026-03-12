🎧 Spotify User Behavior Analysis (Synthetic Dataset)
📌 Overview

This project explores user behavior patterns on a music streaming platform using a synthetic dataset of 50,000 users designed to reflect realistic streaming behavior. The goal of this analysis is to understand how users interact with the platform and identify factors influencing engagement, subscriptions, and inactivity.

The dataset simulates real-world scenarios such as listening habits, subscription types, device usage, ad interactions, and playlist activity, enabling meaningful data analysis and insights.

📊 Dataset Information

Dataset Name: Spotify User Behavior Dataset

Rows: 50,000

Columns: 18

Data Type: Synthetic but designed to reflect realistic user behavior

Format: CSV

⚠️ Disclaimer:
This dataset is synthetically generated for educational and analytical purposes. No real user data is included.

📁 Dataset Features
Column	Description
user_id	Unique identifier for each user
country	User's country
age	Age of the user
signup_date	Date when the user joined the platform
subscription_type	Type of subscription (Free, Premium, etc.)
subscription_status	Current subscription status
months_inactive	Number of months the user has been inactive
inactive_3_months_flag	Indicates if the user has been inactive for 3+ months
ad_interaction	Whether the user interacts with ads
ad_conversion_to_subscription	If ad interaction led to subscription
music_suggestion_rating_1_to_5	Rating for recommendation system
avg_listening_hours_per_week	Average listening time per week
favorite_genre	User’s most listened genre
most_liked_feature	Feature liked the most
desired_future_feature	Feature users want in future
primary_device	Device mostly used
playlists_created	Number of playlists created
avg_skips_per_day	Average songs skipped per day
🔍 Key Questions Explored

The analysis focuses on identifying patterns and answering questions such as:

What factors influence subscription upgrades?

Which countries show higher listening engagement?

How does device usage affect listening time?

Are users with more playlists more active listeners?

Does ad interaction lead to subscription conversions?

Can user churn be predicted using inactivity patterns?

🛠 Tools & Technologies

The dataset can be analyzed using:

Python (Pandas, NumPy, Matplotlib, Seaborn)

SQL

Power BI

Tableau

Excel

📈 Potential Use Cases

User behavior analysis

Customer segmentation

Churn prediction models

Marketing analytics

Music recommendation system experiments

Data visualization projects

🚀 Future Improvements

Possible extensions of this project include:

Building a machine learning churn prediction model

Creating Power BI / Tableau dashboards

Developing recommendation system experiments

Advanced user segmentation analysis

📂 Repository Structure
Spotify-User-Behavior-Analysis
│
├── dataset
│   └── spotify_user_behavior_realistic_50000_rows.csv
│
├── notebooks
│   └── analysis.ipynb
│
├── visuals
│   └── charts
│
└── README.md
🤝 Contributions

Contributions are welcome!
If you have ideas for improving the analysis or expanding the dataset, feel free to open an issue or submit a pull request.
