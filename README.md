# Youtube-Data-Harvesting
The YouTube Data Analyzer is a Streamlit application that allows users to access and analyze data from multiple YouTube channels. The application leverages the Google API to retrieve data such as channel name, subscribers count, total video count, playlist ID, video ID, likes, dislikes, and comments for each video.

Features Data Retrieval: Input a YouTube channel ID to fetch relevant data using the Google API.

Data Storage: Store the collected data in a MongoDB database as a data lake.

Data Collection: Collect data from up to 10 different YouTube channels and save them in the data lake.

Data Migration: Migrate data from the data lake to a SQL database, organized in tables.

Data Search and Retrieval: Search and retrieve data from the SQL database using various search options, including joining tables for comprehensive channel details.

Usage Input a YouTube channel ID to retrieve relevant data from the Google API.

Click the "Collect Data" button to store the data in the MongoDB data lake.

Select a channel name to migrate its data from the data lake to the SQL database.

Explore the different features and analyze YouTube channel data effortlessly.
