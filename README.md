# Spotify-Global-Trends-Analysis-SQL-Python-Power-BI-Data-Pipeline
End-to-end data analytics project analyzing global Spotify streaming trends across tracks, artists, genres, and countries. The project leverages a structured data pipeline using Python (Pandas) for data ingestion, PostgreSQL for storage and transformation, and Power BI for interactive visualization.

Key insights include streaming performance, viral trends, growth dynamics, genre distribution, and regional listening behavior. The dashboard highlights top-performing tracks, artist rankings, and correlations between streams, virality, and longevity.

This project analyzes global Spotify streaming trends to uncover insights into track performance, artist popularity, genre distribution, and regional listening behavior.

The goal is to demonstrate an end-to-end data analytics pipeline—from data ingestion to visualization—while deriving meaningful insights from streaming, virality, and growth metrics.

Data Pipeline Flow:

Kaggle Dataset → Python (Pandas) → PostgreSQL → Power BI → Dashboard & Insights

-Python (Pandas) – Data ingestion and transformation

-PostgreSQL – Data storage and querying

-SQL – Data modeling and aggregation

-Power BI – Data visualization and dashboard creation

-Kaggle Dataset – Source of Spotify global trends data

-GitHub – Version control and project hosting

1. Data Collection
Downloaded dataset from Kaggle
Loaded into Python using Pandas
2. Data Cleaning & Transformation
Handled missing values
Standardized column formats
Verified data types (e.g., BIGINT for streams)
Prepared dataset for SQL ingestion
3. Database Setup
Created PostgreSQL database and table schema
Imported cleaned CSV data into SQL table
Validated data integrity using queries
4. Data Analysis
Wrote SQL queries to explore:
Top-performing tracks and artists
Genre and country distributions
Growth trends and viral performance
5. Visualization (Power BI)
Connected Power BI to PostgreSQL
Built interactive dashboards featuring:
KPI cards
Bar charts
Scatter plots
Clustered comparisons
Distribution analysis (histograms)
📈 Key Metrics & Analysis

This project explores several important performance indicators:

Streaming Performance
Total and average streams
Top tracks and artists
Growth & Momentum
Stream change
Growth rate
Streams per day
Virality
Viral score comparisons
Viral efficiency metrics
Geographic Trends
Streams by country
Genre popularity by region
Genre Analysis
Distribution of streams across genres
Genre performance vs virality
Longevity & Lifecycle
Days on trend
Relationship between longevity and streams
📊 Dashboard Features (Power BI)
KPI overview (streams, artists, viral score averages)
Top N rankings (tracks, artists, countries)
Genre and country breakdowns
Scatter plots showing relationships between:
Streams vs Viral Score
Streams vs Growth
Distribution analysis (histograms)
Trend and popularity segmentation
Clustered comparisons across multiple metrics
🔍 Key Insights
Streaming data is highly skewed, with a small number of tracks dominating total streams
Viral score does not always correlate directly with total streams
Certain genres dominate specific regions
Tracks with high growth rates are not always the most streamed overall
Longevity varies significantly across tracks, indicating different lifecycle patterns
