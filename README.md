🚕 Uber NYC Taxi Analysis Using NLP, Word Cloud & Time Series
A comprehensive data analysis project on Uber New York City taxi rides that combines geospatial insights, sentiment analysis from rider comments, keyword visualization using word clouds, and time series modeling for trip durations and fare trends.

📁 Repository Name
uber-nyc-taxi-nlp-analysis

📄 Project Description
This project aims to analyze Uber taxi ride data in New York City using data science techniques. The key goals are:

Clean and preprocess geospatial and transactional ride data

Extract insights from customer comments using Natural Language Processing (NLP)

Visualize frequent words via WordCloud

Perform sentiment analysis on user feedback using TextBlob

Conduct time series analysis using ARIMA to forecast metrics like trip duration and fare amount

Use clustering to group similar ride patterns

📊 Key Features
🧹 Data Cleaning & Preprocessing: Handle missing values, rename columns, convert datatypes, calculate trip duration.

🌐 Geospatial Analysis: Understand pickup and dropoff trends using lat-long coordinates.

💬 Text Analytics: Clean and analyze textual feedback from users.

🌥️ WordCloud Generation: Visual representation of the most common keywords in user comments.

📈 Time Series Forecasting: Predict trip duration and fare trends over time using ARIMA.

🎯 Sentiment Analysis: Identify rider sentiment using polarity scores from TextBlob.

🤖 KMeans Clustering: Group trips into clusters based on distance, fare, and duration.

🧠 Tools and Libraries Used
Pandas & NumPy – Data manipulation and computation

Matplotlib & Seaborn – Data visualization

Scikit-learn (KMeans) – Clustering

WordCloud – Text visualization

TextBlob – Sentiment analysis

ARIMA (Statsmodels) – Time series modeling

Excel I/O – Data loading and export

🗂️ Dataset
File Used: updated_taxi_trips_with_new_columns.xlsx

Shape: 2348 rows × 40 columns

Main Fields: pickup/dropoff datetime, coordinates, fare, tips, ratings, comments, and distance.

📌 Key Columns after Cleaning
pickup_datetime, dropoff_datetime

trip_distance, fare_amount, tip_amount, total_amount

rating, comment, trip_duration

pickup_longitude, pickup_latitude, dropoff_longitude, dropoff_latitude

🚀 How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/uber-nyc-taxi-nlp-analysis.git
Navigate to the directory

bash
Copy
Edit
cd uber-nyc-taxi-nlp-analysis
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter Notebook or Python script to explore the data

📊 Sample Visuals
Word Cloud of most frequent comment terms

Sentiment score distribution

KMeans cluster visualization

Time series plots for trip durations and fare

📈 Future Enhancements
Deploy the dashboard using Streamlit

Integrate geospatial visualizations using Folium or Mapbox

Use deep learning (LSTM) for time series prediction
