# YouTube_Data_Harvesting
This web app is designed to fetch data from YouTube using their YouTube's Data API v3 based on user input for a channel username. The fetched data is stored in my personal MongoDB Atlas Database and provides facilities for users to migrate the channel data to their local MySQL database. The project also includes custom-made queries for basic data analysis and visualization using Streamlit.

Prerequisites

Before you begin, you will need to have a few tools and libraries installed on your machine:

Python 3.7 or higher [Note: Streamlit only supports .py files as of now. So, notebook(.ipynb) files are not recommended]
Git software
MySQL software
MongoDB Atlas account
The streamlit, google-api-client-python, pymongo, mysql-connector-python packages, pandas, plotly, altair, wordcloud and few other packages
Python

Python is a versatile programming language known for its simplicity and readability. In this project, Python is the core language used for developing the entire application, including data fetching, processing, analysis, and visualization.

MongoDB Atlas

MongoDB Atlas is a fully managed cloud database service for MongoDB. In this project, MongoDB Atlas is used to store the fetched data from YouTube's Data API v3. It provides a reliable and scalable database solution for efficient data storage and retrieval.

MySQL

MySQL is an open-source relational database management system. In this project, MySQL is used to store the migrated channel data from MongoDB Atlas. It offers a structured and efficient way to store and query data, ensuring data integrity and scalability.

Streamlit

Streamlit is a Python library used for building interactive web applications. In this project, Streamlit is utilized to create a user-friendly interface for users to interact with the fetched YouTube data, select channels, playlists, and visualize data using various charts and plots.

Pandas

Pandas is a popular Python library used for data manipulation and analysis. We used pandas to clean and preprocess the data, create new features, and perform data analysis. It provides a wide range of functions and methods for working with data.

Visualization libraries such as Plotly, Altair, Matplotlib

These visualization libraries in Python are used to create various charts, plots, and visualizations based on the fetched YouTube data. Plotly, Altair, and Matplotlib offer a wide range of options for visualizing data, making it easier to understand patterns, trends, and insights.

Wordcloud

Wordcloud is a Python library used to create visual representations of text data, where the size of each word is proportional to its frequency. In this project, the Wordcloud library is used to generate word clouds based on the tags or comments associated with the YouTube videos, providing a visual summary of the most commonly used terms.

Pymongo

pymongo is a Python library that provides tools for working with MongoDB databases. In this project, pymongo is used to establish a connection to the MongoDB Atlas database and perform operations such as inserting, updating, and querying data.

MySQL Connector

mysql.connector is a Python library used to connect and interact with MySQL databases. In this project, mysql.connector is used to establish a connection to the local MySQL database and execute SQL queries to migrate the channel data from MongoDB Atlas.

Google API Client

googleapiclient is a Python library that enables interaction with various Google APIs. In this project, googleapiclient is used to make requests to YouTube's Data API v3 and fetch the required data, such as channel details, video details, and comments. It provides a convenient interface to access YouTube's vast collection of data programmatically.

Ethical Perspective of scraping youtube data

From an ethical standpoint, it is essential to approach the scraping of YouTube content with caution and responsibility. It is important to respect the terms and conditions set by YouTube, obtain proper authorization, and adhere to data protection regulations. The collected data should be used responsibly, ensuring privacy and confidentiality, and avoiding misuse or misrepresentation. Additionally, considering the potential impact on the platform and its community is crucial to ensure a fair and sustainable scraping process. By following these ethical guidelines, we can maintain integrity while harnessing YouTube data for valuable insights.
