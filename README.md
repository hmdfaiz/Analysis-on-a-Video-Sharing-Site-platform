# Analysis on a Video-Sharing Site Platform

I am doing this analysis on Google Colab using python libraries such Numpy, Pandas, Matplotlib and Seaborn

## Deployment

To deploy this project,

```bash
  1. Download the US_category_id.json and the US_youtube_trending_data.csv
  2. Make sure you have Google Colaboratory account
  3. If you do then open a new notebook
  4. Connect to the server
  5. Upload the files that u just downloaded
  6. Copy the file path
  6. Store it to a new dictionary and a new data frame
  7. Go to my Analysis_on_a_Video_Sharing_Site_platform.ipynb
  8. Copy one by one the line of code
  9. Compare the result and our purpose of analysis
```

## Objective

Our analysis objective:
 - Data Cleaning, Read the concerned files
 - Converting two date time columns to approriate formats
 - Fill the null value on 'description' column with 'No description provided'
 - Video with max views and min views details
 - Create a function that can store the video catagory name into related data frame
 - Channel with the most view count (list/top)
 - Plotting the 5 channels with largest view_count, likes, dislikes, comment_count
 - Most watched category
 - Least watch category
 - Response percentage column which signifies the public responses to a video and engagement between the viewers and the video
 - Public Response vs Type of Videos
 - Comment_Percentage, Likes, Dislikes vs Type of Videos
 - Channels analysis (vs Total Views, Total Comments)
 - Video Trending analysis (Channels vs No of Time in Trending)
 - Channels, Category vs Total No of Time in Trending
 
 ## Data Set Source

 - [US Video Trending](https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset?select=US_youtube_trending_data.csv)
