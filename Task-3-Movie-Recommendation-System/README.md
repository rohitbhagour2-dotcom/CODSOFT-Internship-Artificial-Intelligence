# Task 3 - Movie Recommendation System 🎬

## 📌 Overview
A content-based Movie Recommendation System that suggests movies to users based on similarity in genres, keywords, cast, or user preferences. The system uses similarity measures to recommend movies similar to a given title or matching a user's interest profile.

This task is part of the **CodSoft Artificial Intelligence Internship**.

## 🧠 Concept Used
- **Content-Based Filtering**: Recommends items similar to what the user already likes, based on item attributes (genre, description, cast, etc.)
- **Cosine Similarity / TF-IDF Vectorization**: Used to measure similarity between movies based on textual features.
- *(If collaborative filtering is used instead, mention: User-Item rating matrix and similarity-based recommendations)*

## ⚙️ How It Works
1. Movie dataset is loaded containing details like title, genre, overview, cast, etc.
2. Text features are converted into numerical vectors using techniques like TF-IDF.
3. Cosine similarity is calculated between movies to find the closest matches.
4. When a user selects/enters a movie, the system returns the top N most similar movies.

## 🛠️ Tech Stack
- Python
- Pandas, Scikit-learn (TF-IDF, Cosine Similarity)
- *(Add Streamlit/Flask here if a web interface was built)*

## 🚀 Live Demo
🔗 [Movie Recommendation System](https://rohitbhagour2-dotcom.github.io/CodSoft-Internship-Artificial-Intelligence/Task-3-Movie=Recommendation-Syatem/recommendationsystem.html)

## ▶️ How to Run Locally
1. Clone this repository
```bash
   git clone https://github.com/asthakumari-max/CodSoft-Internship-Artificial-Intelligence.git
```
2. Navigate to the `Task-3-MovieRecommendation` folder
3. Install required libraries (if Python-based)
```bash
   pip install pandas scikit-learn
```
4. Run the script or open the file in a browser (depending on implementation)

## ✨ Features
- Recommends similar movies based on content similarity
- Clean and simple search/recommendation interface
- Fast and lightweight similarity computation

## 📸 Screenshot
*(Add a screenshot of the recommendation interface here after upload)*

## 👩‍💻 Author
**Rohit Kumar**
🔗 [LinkedIn](https://www.linkedin.com/in/rohit-bhagour-302571382) | [GitHub](https://github.com/rohitbhagour2-dotcom)

---
⭐ Part of the CodSoft AI Internship Task Series
