YOUTUBE DATA HARVESTING AND WAREHOUSING

OVERVIEW :
This Python script fetches data from YouTube channels, playlists, videos, and comments using the YouTube API. It stores the data in a MongoDB database and migrates it to a PostgreSQL data warehouse. The fetched data can be analyzed and displayed using a Streamlit web app YouTube Data Harvesting and Warehousing

ACKNOWLEDGEMENTS
* Google APIs Client Library for Python
* MongoDB
* Psycopg - PostgreSQL adapter for Python
* Pandas
* Streamlit

GOOGLE APIS CLIENT LIBRARY FOR PYTHON:
Description: The Google APIs Client Library for Python is a client library for accessing Google APIs, including the YouTube Data API used in this project. It simplifies the process of making requests to Google APIs and handling responses.

Usage in Project: This library is used to interact with the YouTube Data API, enabling the retrieval of various data from YouTube, such as channel information, playlist details, video details, and comments.

MONGODB:
Description: MongoDB is a popular open-source NoSQL database that provides a flexible, scalable, and high-performance solution for storing and managing data. It is a document-oriented database, meaning it stores data in flexible, JSON-like documents.

Usage in Project: MongoDB is used in this project to store the fetched data from YouTube. It provides a schema-less data model, which allows for easy storage of various types of data without a predefined schema. The fetched data, including channel information, playlist details, video details, and comments, are stored in MongoDB collections.

PSYCOPG - POSTGRESQL ADAPTER FOR PYTHON:
Description: Psycopg is a PostgreSQL adapter for Python that provides a connection between Python and PostgreSQL databases. It enables Python applications to interact with PostgreSQL databases by executing SQL queries, fetching data, and managing transactions.

Usage in Project: Psycopg is used in this project to establish a connection to a PostgreSQL database and perform various database operations, such as creating tables, inserting data, and executing SQL queries. It facilitates the migration of data from MongoDB to PostgreSQL and the execution of predefined SQL queries against the PostgreSQL data warehouse.

PANDAS:
Description: Pandas is a powerful Python library for data manipulation and analysis. It provides data structures and functions for efficiently handling and processing structured data, such as tabular data and time series data.

Usage in Project: Pandas is used in this project to work with data retrieved from YouTube and stored in MongoDB. It enables tasks such as transforming data into pandas DataFrames, performing data analysis, and preparing data for migration to a PostgreSQL database. Pandas simplifies data manipulation tasks and enhances the efficiency of data processing workflows.

STREAMLIT:
Description: Streamlit is an open-source Python library for building interactive web applications for data science and machine learning projects. It allows users to create web applications with simple Python scripts, providing features for data visualization, user interaction, and deployment.

Usage in Project: Streamlit is used in this project to create a user-friendly web interface for interacting with the fetched YouTube data and querying the PostgreSQL data warehouse. It facilitates the creation of interactive data visualization components, such as tables and dropdown menus, and enables seamless deployment of the web application for data exploration and analysis.

Key Features
* Fetch channel information (name, ID, subscription count, views, total videos, description, etc.)
* Fetch playlist information (ID, title, channel ID, channel name, published date, video count)
* Fetch video information (ID, title, channel name, tags, thumbnail, description, published date, duration, views, likes, comments, favorite count, definition, caption status)
*	Fetch comment information (ID, video ID, comment text, author, published date)
* Store data in MongoDB collections
*	Migrate data to a PostgreSQL database with predefined tables
*	Display data using a Streamlit web application
*	Execute predefined SQL queries against the PostgreSQL data warehousecation.

