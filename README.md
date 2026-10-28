# 🎬 Movie Recommendation System

## 📌 About the Project

The **Movie Recommendation System** is a machine learning project that recommends similar movies based on their genres, keywords, and descriptions. It uses Natural Language Processing (NLP) techniques to analyze movie information and identify similarities between movies.

## 🎯 Project Objectives

- Recommend movies similar to a user's selected movie.
- Analyze movie genres, keywords, and overviews.
- Convert text data into numerical features using TF-IDF.
- Calculate movie similarities using Cosine Similarity.

## 🛠️ Technologies Used

- **Python**
- **Pandas** — Data manipulation and preprocessing
- **Scikit-learn** — TF-IDF Vectorization and Cosine Similarity
- **TMDB 5000 Movie Dataset** — Movie data source
- **Jupyter Notebook** — Development environment

## 📂 Dataset

This project uses the **TMDB 5000 Movie Dataset**, which contains movie-related information.

The project uses the following features:

- Movie Title
- Genres
- Keywords
- Overview

## ⚙️ How It Works

1. **Data Loading:** Load the movie dataset using Pandas.
2. **Data Preprocessing:** Handle missing overview values and prepare movie information.
3. **Feature Creation:** Combine genres, keywords, and overviews into a single text feature called `tags`.
4. **TF-IDF Vectorization:** Convert movie text into numerical vectors using `TfidfVectorizer`.
5. **Similarity Calculation:** Use Cosine Similarity to measure how similar movies are.
6. **Movie Recommendation:** Find and display the top 5 similar movies based on the selected movie.

## 🧠 Recommendation Technique

### Content-Based Filtering

This project uses a content-based recommendation approach. It recommends movies by comparing their content-related information rather than using individual users' viewing histories or ratings.

- **TF-IDF Vectorization:** Converts text data into numerical representations.
- **Cosine Similarity:** Measures the similarity between movie vectors.

## 💻 Installation and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/arzuantor/Movie-Recommendation-System.git
```

### 2. Navigate to the Project Folder

```bash
cd Movie-Recommendation-System
```

### 3. Install Required Libraries

```bash
pip install pandas scikit-learn jupyter
```

### 4. Run the Notebook

Open Jupyter Notebook and run the project notebook cells in order.

## 📊 Example

If a user selects **The Dark Knight**, the system finds movies with similar genres, keywords, and descriptions.

```python
recommend("The Dark Knight")
```

The function returns up to five recommended movie titles.

## 🚀 Future Improvements

- Build an interactive web application using Streamlit.
- Add movie posters and additional movie details.
- Explore collaborative filtering using user rating data.
- Develop a hybrid recommendation system.

## 👨‍💻 Author

**Arzu Antor**

- GitHub: [arzuantor](https://github.com/arzuantor)

---

⭐ If you find this project interesting, feel free to explore the repository!
