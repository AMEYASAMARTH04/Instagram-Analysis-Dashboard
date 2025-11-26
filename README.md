# Instagram-Analysis-Dashboard
This dashboard visualizes my Instagram performance using a machine-learning model that predicts post reach. It highlights key KPIs like engagement rate, reach efficiency, conversion rate, hashtag ROI, and content category insights—helping identify what drives the highest impact.

Instagram Analysis Dashboard & Reach Prediction Model

A complete end-to-end Instagram analytics project combining data analysis, machine-learning reach prediction, and a fully interactive Power BI dashboard. This project helps identify what drives reach, engagement, follower growth, and content efficiency across different media types and content categories.

Project Overview

This project analyzes Instagram post-level data, creates key performance metrics, and uses a machine-learning model to predict post reach. The final dashboard visualizes both the actual and predicted reach, highlights top-performing content, and explains which factors contribute most to follower growth and engagement.

The goal is to help creators and marketers understand:

Which media types perform best

How efficiently content turns impressions into followers

What categories drive saves, comments, shares, and likes

How hashtags, captions, and traffic sources impact reach

Which posts outperform or underperform predictions

Machine Learning Component

A reach prediction model was trained using features such as:

Media type

Hashtags count

Caption length

Engagement metrics (likes, comments, shares, saves)

Traffic source

Content category

Time & upload behaviour

The model outputs Predicted Reach, which is compared with Actual Reach to identify:

Viral-potential posts (Predicted < Actual)

Underperforming posts (Predicted > Actual)

This helps creators refine future content strategy.

Dashboard Features (Power BI)
Key KPIs

Average Likes

Reach Efficiency

Overall Engagement Rate

Hashtag ROI

Caption Efficiency

Conversion Rate (Reach → Followers Gained)

Visual Insights

Average Reach & Followers by Media Type
Shows how Reels, Photos, Videos, and Carousels perform.

Engagement Breakdown by Content Category
Visualizes saves, comments, shares, and likes across themes (Fitness, Tech, Beauty, Travel, etc.).

Actual vs Predicted Reach Table
Compares how posts performed relative to model expectations.

Traffic Source Filters
Identifies which discovery paths (Explore, Reels Feed, Hashtags, Profile) deliver the best visibility.

Insights from the Analysis

Reels achieve high reach but inconsistent follower conversion.

Carousel posts show stable engagement and predictable growth.

Beauty, Fitness, and Technology categories generate deeper engagement signals (saves & comments).

Hashtag ROI and Caption Efficiency show strong correlation with engagement quality.

Several posts significantly outperformed ML predictions—strong indicators of organic virality.

Tech Stack

Python (Pandas, Scikit-learn, XGBoost)

Power BI for dashboard visualization

Jupyter Notebook for EDA + ML workflow

CSV Dataset for input data

Project Structure

/Instagram-Analysis-Model
│
├── data/                 # Source dataset
├── notebooks/            # EDA + ML model training
├── dashboard/            # Power BI (.pbix) file
├── model/                # Saved ML model + features
└── README.md             # Project documentation


Conclusion

This project provides deep insights into Instagram content performance using both analytics and predictive modeling. It helps creators, brands, and analysts understand what truly drives reach and engagement, leading to smarter content strategy and higher follower growth.
