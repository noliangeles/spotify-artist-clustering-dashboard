# 🎵 Spotify Artist Clustering & Growth Dashboard

This project analyzes Spotify artist data to explore musical styles and growth trends. Using machine learning, it clusters artists based on audio features, enabling recommendations and visualizing genre shifts over time. It also includes an interactive Tableau dashboard for exploration.

## 🔍 Project Objectives

- Analyze audio features of tracks from diverse artists
- Cluster artists by musical style using unsupervised learning
- Visualize artist growth, genre patterns, and clusters
- Recommend similar artists based on audio profile
- Combine SQL, Python, ML, and Tableau for full-stack delivery

## 📦 Tools & Technologies

- Spotify API + Spotipy (Python)
- SQL (MySQL or PostgreSQL)
- scikit-learn (for clustering)
- pandas, seaborn, matplotlib
- Tableau (for dashboards)

## 📁 Folder Structure
project-root/
│
├── data/ # Raw or cleaned data (CSV or SQL dumps)
├── notebooks/ # Jupyter Notebooks for analysis and modeling
├── sql/ # Database schema and queries
├── scripts/ # Python scripts for data pull and processing
├── dashboard/ # Tableau workbook and visuals
├── README.md
├── requirements.txt
└── .gitignore


## 🚧 Project Status

> **In Progress**  
> Currently setting up the database schema and pulling artist data from the Spotify API.

## 📋 Project Checklist

### 📦 Phase 1: Data Engineering + Dashboard (Data Analytics)

- [x] Set up GitHub repo and folder structure
- [x] Define database schema (SQL)
- [x] Create tables in MySQL
- [ ] Authenticate Spotify API via `spotipy`
- [ ] Pull artist + album + track data
- [ ] Pull audio features for tracks
- [ ] Load data into SQL tables
- [ ] Export data for Tableau
- [ ] Design and publish Tableau dashboard:
  - [ ] Artist popularity growth
  - [ ] Audio feature trends
  - [ ] Genre breakdown
  - [ ] Interactive filters

---

### 🤖 Phase 2: Machine Learning (Artist Clustering)

- [ ] Clean + merge features for clustering
- [ ] Scale/normalize audio features
- [ ] Apply KMeans or DBSCAN
- [ ] Visualize clusters (PCA or t-SNE)
- [ ] Assign cluster labels to artists
- [ ] (Optional) Add cluster labels to Tableau

---

### 🧠 Phase 3: AI Feature (NLP or Recommender)

Choose one:
- [ ] Lyrics Sentiment Analysis via Hugging Face or TextBlob
  - [ ] Pull lyrics via Genius API
  - [ ] Run sentiment model
  - [ ] Save results in SQL or CSV

**OR**

- [ ] Build mini artist recommender using cosine similarity
- [ ] (Optional) Wrap it in Streamlit chatbot

---

### 🧹 Final Touches

- [ ] Polish README with visuals + model summary
- [ ] Add project summary to portfolio site
- [ ] Push final dashboard to Tableau Public


## 📌 Author

Noli Angeles

---

Stay tuned for more updates as this project evolves!
