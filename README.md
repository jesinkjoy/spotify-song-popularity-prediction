# 🎵 Spotify Song Popularity Prediction

This project aims to enhance Spotify’s recommender system by predicting which songs are likely to become hits, using audio features and metadata. It was completed as part of the INFO 648 – Business Data Analytics course at VCU.

## 📁 Project Structure

- **Q1:** Predict whether a song’s popularity score will exceed 64 using ML models.
- **Q2:** Optimize the recommendation model using profit/cost analysis.
- **Q3:** Analyze song clusters and valence patterns to refine playlist curation.

---

## 🧠 Objectives

- **Classification**: Determine whether a song will be popular (popularity ≥ 65).
- **Profit Optimization**: Evaluate models based on financial outcomes, not just accuracy.
- **Clustering & Pattern Discovery**: Group songs using audio features and mine patterns associated with hits.

---

## 🔧 Tools & Technologies

- Python, pandas, NumPy, matplotlib, seaborn
- scikit-learn (Logistic Regression, Decision Tree, KNN)
- Clustering (KMeans, Agglomerative, DBSCAN)
- Association Rule Mining
- Google Colab 

---

## 📈 Key Highlights

- **Best Predictive Model (Q1):** K-Nearest Neighbors (59.33% test accuracy)
- **Best Profit Model (Q2):** Decision Tree (Net loss reduced to $33,000)
- **Feature Importance:** Energy, speechiness, loudness, and explicit content strongly influence popularity
- **Clustering Insight:** High danceability + energy = high popularity clusters
- **Valence Impact:** Mood matters differently across clusters; no universal effect

---

## 💡 Business Recommendations

- Prioritize upbeat, high-energy songs in recommendation pipelines.
- Use profit-driven model evaluation to guide algorithm selection.
- Create cluster-specific playlists based on genre and mood preferences.
- Leverage association rules (e.g., high energy + speechiness → hit) to discover future hits.

---

## 📂 Files

- `spotify_modeling_notebook.ipynb` – Full model implementation
- `songs_utf.csv` – Dataset (1998–2020 U.S. Spotify chart songs)
- `spotify_project_report.docx` – Full project write-up
- `spotify_project_presentation.pptx` – Executive presentation summary

---

## 📌 Note

This was a university project and is not affiliated with Spotify Inc. All data was publicly available and used for educational purposes only.
