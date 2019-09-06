# WebScraping - project-3 website : https://influence.co/category/riyadh
## The Dataset link in kaggle:
https://www.kaggle.com/amjadalsulami/top-riyadh-influencers 
## Problem statment
- This dataset is for local (Saudi Arabia) social media influencers, and the dataset is built using web scraping to get influencers information from https://influence.co . The dataset focused on Instagram influencers in Saudi Arabia and contains 5 attributes and 243 rows. In particular, the dataset has the Instagram id for the influencers,number of followers, the category name that they belong to and level of impact of influencers on Instagramwhich is the avg engagement rate.

## Data Set Information: 
- IG_id, The influencer Instagram id, object.
- No_followers,  The number of followers the influencer have, int64.
- Category_name, the category which the influencer belongs to (# Here I assumed that when there were other social media platforms, I would replace them with the name of persons in these programs, for example,  'snapchat - lifestyle', youtube - vlogger','Facebook, Blogger'), object.
- Locations, the influencer location (based city), object.
- engagment_rate_avg , the engagement rate the influencer have in % ,float64.
## The data can be used to clustering the influencers according to their Category_name, their avg engagement rate and also the number of followers they have.
