# social-media-analytics
Social Media Analytics Dataset

A synthetic dataset of 3,000 social media posts with engagement metrics, sentiment labels, and a pre-built dashboard for exploring content performance across platforms.

File
social_media_analytics_3000_finally.xlsx — Excel workbook containing the raw data, pivot tables, charts, and a summary dashboard.
Contents

The workbook has 10 sheets:

Sheet	Description
Social Media Analytics	Main dataset — 3,000 posts, 16 columns (see below)
dashboard	Visual dashboard with charts and slicers summarizing the data
Sheet1, Sheet4, Sheet7, Sheet12, Sheet14, Sheet15, Sheet16	Supporting pivot tables feeding the dashboard charts
count of sentiment	Pivot table breaking down post counts by sentiment
Main dataset columns
Column	Description
Post ID	Unique identifier for the post
Timestamp	Date and time the post was published
Platform	Social platform (Instagram, TikTok, X (Twitter), LinkedIn, YouTube)
Account / Creator	Account or creator handle
Content Category	Topic category (e.g. Tech & AI, Business & Finance, Lifestyle & Wellness)
Post Type	Format of the post (e.g. Short Video, Text Only, Video Tweet)
Follower Count	Follower count of the posting account
Impressions	Number of times the post was displayed
Reach	Number of unique accounts that saw the post
Likes	Number of likes
Comments	Number of comments
Shares / Retweets	Number of shares or retweets
Saves / Bookmarks	Number of saves or bookmarks
Clicks	Number of clicks
Engagement Rate (%)	Calculated engagement rate
Sentiment	Sentiment label (Positive, Neutral, Negative)
Usage

Open the file in Excel, Google Sheets, or load it programmatically:

python
import pandas as pd

df = pd.read_excel("social_media_analytics_3000_finally.xlsx", sheet_name="Social Media Analytics")
print(df.head())
