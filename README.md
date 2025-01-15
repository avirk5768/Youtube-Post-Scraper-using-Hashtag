# Youtube-Post-Scraper-using-Hashtag
This Python script automates the process of collecting YouTube video data using the YouTube Data API. It searches for videos based on specific hashtags and gathers details like the title, views, likes, and comments for each video.

1. **Logging**: Tracks the process and saves logs in both a file and the console.
2. **API Setup**: Uses the YouTube Data API to search for videos with given hashtags.
3. **`get_video_details`**: Fetches detailed information (title, views, likes, etc.) for a video by its ID.
4. **`search_youtube_videos`**: Searches for videos using specified hashtags, collects details for each video, and handles pagination for multiple search result pages.
5. **Hashtags & Keywords**: Searches YouTube for videos based on the provided hashtags and an empty keyword list.
6. **Data Collection**: Gathers video details for all search results and stores them in a Pandas DataFrame for analysis.

In essence, the script automates YouTube video searches, collects relevant details, and stores them for further analysis.
