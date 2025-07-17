# Movierecommendationsystem

🎬 Movie Recommendation System
A simple content-based movie recommender built using the TMDb 5000 Movies Dataset, vectorization, and Streamlit.

🔍 Features
Recommends similar movies based on selected title

Uses NLP (CountVectorizer / TF-IDF) for similarity

Interactive UI with Streamlit

🧠 How It Works
Merges movies and credits datasets

Creates tags from overview, genres, cast, crew, keywords

Vectorizes tags and computes cosine similarity

Displays top 5 similar movies with optional posters

▶️ Run Locally
bash
Copy
Edit
pip install -r requirements.txt
streamlit run app.py
📦 Dataset
TMDb 5000 Movies Dataset – Kaggle

🚀 Future Improvements
Add collaborative filtering

Use TMDb API for dynamic data

Improve UI and poster integration
