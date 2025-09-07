🎬 Netflix Viewing Insights using NLP & Clustering
📌 Project Overview

This project analyzes personal Netflix viewing history using Natural Language Processing (NLP) and unsupervised clustering techniques.
By extracting show descriptions and applying embeddings, I clustered shows into genres, built a recommendation engine, and derived time-based viewing insights.

🔍 Objectives

Apply NLP to show descriptions to understand themes.

Group shows into clusters/genres using embeddings + KMeans.

Extract keywords with TF-IDF for labeling clusters.

Build a content-based recommendation system using cosine similarity.

Explore time-based insights (trends, binge patterns, most-watched shows).

Visualize results to tell a clear story.

🛠️ Tech Stack

Python

pandas, numpy – data handling

scikit-learn – embeddings, clustering, similarity

sentence-transformers – MiniLM embeddings

matplotlib, seaborn – visualizations


📂 Dataset

Exported Netflix Viewing Activity from my profile.

Enriched with metadata (description, genre, release year) using external APIs.

📊 Key Steps

Data Preprocessing

Cleaned descriptions, lowercased, removed stopwords, lemmatized text.

Embeddings & Clustering

Generated embeddings using all-MiniLM-L6-v2.

Applied KMeans for clustering shows into genres.

Used TF-IDF keywords to label clusters manually.

Recommendations

Built a cosine similarity-based recommender.

Able to filter by cluster or year.

Time-Based Insights

Monthly viewing trends.

Genre preferences over time.

Estimated watch hours (approximated by cluster genre).

Top binge-watched shows.

Visualization

Genre distribution.

PCA visualization of clustered embeddings.

📈 Results

Successfully clustered viewing history into meaningful genres (e.g., Horror/Supernatural, Historical Adventure, Documentaries).

Recommendations were genre-consistent (e.g., Death Note → Tokyo Ghoul, Erased).

Time-based analysis revealed clear binge periods and genre shifts.


👩‍💻 Author

Harshita Gupta
Data Science Enthusiast | NLP & Machine Learning
