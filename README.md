# Sportify-Streaming-Python-visualization-project
This project implements an automated data engineering and analytical pipeline designed to clean, normalize, profile, and visualize multi-platform music streaming metrics. Processing a high-dimensional dataset of 20,718 historical records and 28 features, the system transforms unstructured media metrics into highly optimized data visualization

Core Technical Pipeline

Automated Cleaning Engine: The pipeline runs structural de-duplication and strips whitespace variation across critical text records (Artist, Track, Album, Channel, Title) to eliminate string fragmentation during processing. Imputation Matrix: Handles missing metrics dynamically using split-logic blocks. Core metric fields (Views, Likes, Comments, Stream) are zero-filled, while technical audio features (Danceability, Energy, Key, Loudness, Speechiness) are handled through series mean calculations. Outlier Auditing: Aggregates extreme distribution spreads across cross-platform data structures, mapping viral milestones reaching up to 8.08 Billion YouTube Views and over 3.38 Billion Spotify Streams.

Technology Stack & Components

Language Core: Python Data Processing: Pandas, NumPy Graphing Engines: Matplotlib, Seaborn Interface Layer: Native HTML5 / CSS3
