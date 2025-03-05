
# 🎬 Movie Recommender System

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--learn-orange?style=for-the-badge)
![API](https://img.shields.io/badge/API-TMDb-green?style=for-the-badge)

## 📌 Overview
This **Movie Recommender System** suggests movies based on user input using **cosine similarity** and **TF-IDF vectorization**. The system is built using **Python, Streamlit, and TMDb API** to fetch movie posters. It helps users find movies similar to their favorites with an interactive UI.

## 🚀 Features
- ✅ **Content-Based Filtering**: Uses movie metadata (title, overview, genres, keywords, cast, and crew) for recommendations.
- ✅ **Cosine Similarity Algorithm**: Finds the most relevant movies based on their descriptions.
- ✅ **Interactive UI with Streamlit**: Easy-to-use interface for seamless movie recommendations.
- ✅ **Movie Posters Fetching**: Uses TMDb API to display recommended movies visually.
- ✅ **Fast & Efficient**: Optimized for quick recommendations with preprocessed data.

## 🏗️ Tech Stack
- **Programming Language**: Python 🐍
- **Libraries Used**:
  - Pandas 📊 (for data processing)
  - Scikit-learn 🤖 (for machine learning)
  - Streamlit 🎨 (for the web app)
  - Requests 🌐 (for API calls)
  - Pickle 📦 (for model storage)
- **API Used**: TMDb (The Movie Database)
- **Deployment**: Streamlit Cloud / Local

## 📂 Project Structure
```
📁 Movie-Recommender-System
│── 📄 README.md             # Project documentation
│── 📄 app.py                # Streamlit web app
│── 📄 main.ipynb            # Jupyter Notebook for model development

```

## 🔥 Installation & Usage

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/Movie-Recommender-System.git
cd Movie-Recommender-System
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit App
```sh
streamlit run app.py
```

## 📜 Dataset
The dataset consists of essential features for recommendations:
- **movie_id**: Unique identifier for each movie
- **title**: Name of the movie
- **overview**: Short description of the movie
- **genres**: Categorization of the movie
- **keywords**: Key descriptors of the movie
- **cast**: Lead actors in the movie
- **crew**: Director and key contributors

This dataset is preprocessed, transformed into TF-IDF vectors, and stored for efficient similarity calculations.

## 📊 How It Works
1. **User selects a movie** from the dropdown menu.
2. **Cosine similarity** is calculated between the selected movie and the rest.
3. The **top 5 most similar movies** are retrieved.
4. **Movie posters** are fetched dynamically using the TMDb API.
5. The **recommended movies and posters** are displayed in a structured format.

## 🛠️ Model Development Process
The **main.ipynb** file contains the complete model-building process:
### 1️⃣ Data Preprocessing
- Removing missing values.
- Combining relevant metadata into a single text format.
- Tokenization and transformation.

### 2️⃣ Feature Extraction using TF-IDF
- Textual metadata is converted into numerical form using **TF-IDF Vectorization**.
- High-dimensional feature vectors are created for each movie.

### 3️⃣ Cosine Similarity Calculation
- Measures how similar two movies are based on their textual features.
- Used to find the closest movies to the selected one.

### 4️⃣ Model Storage
- The precomputed similarity matrix is **pickled** and saved.
- The model is loaded in **app.py** for real-time recommendations.


## 🚀 Future Enhancements
- [ ] **Hybrid Recommendation System** (Combining Content-based & Collaborative filtering)
- [ ] **User Login System** (Personalized recommendations based on watch history)
- [ ] **More Filtering Options** (Sort by popularity, release date, etc.)
- [ ] **Deployment on Cloud** (AWS, Heroku, or Streamlit Cloud)

## 🤝 Contributing
Contributions are welcome! Feel free to **fork** this repo, create a new branch, and submit a **pull request**.

### Steps to Contribute:
1. Fork this repository 🍴
2. Create a new branch (`git checkout -b feature-branch`) 🌿
3. Commit your changes (`git commit -m 'Add new feature'`) 💾
4. Push to the branch (`git push origin feature-branch`) 🚀
5. Open a **Pull Request** 📩

## 📝 License
This project is licensed under the **MIT License**.

---
Made with ❤️ by [Chirag HALAN](https://github.com/chiraghalan/)
```

