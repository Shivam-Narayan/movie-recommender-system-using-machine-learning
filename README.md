# 🎬 Movie Recommender System using Machine Learning

## 🔄 Overview
This project demonstrates a Movie Recommender System built using machine learning techniques. The system suggests movies based on user preferences and historical interactions, providing personalized recommendations.

## ✨ Features
- 🔄 Content-based Filtering
- 🔢 Collaborative Filtering (using matrix factorization)
- 🔗 Hybrid Recommendation Models
- 🛠️ Interactive user interface for movie search and recommendations

## 📂 Dataset
The system uses publicly available movie datasets such as the [MovieLens Dataset](https://www.kaggle.com/datasets/ahsanaseer/top-rated-tmdb-movies-10k?fbclid=IwAR2MpWrWpcw2QNCv_FZg2l0sjBh9xAvhrqtnZBO9K-QS6PHI1aHkdB6qLa0) which contains movie ratings, titles, genres, and more.

## 🛠️ Installation

1. 🔧 Clone the repository:
   ```bash
   git clone https://github.com/Shivam-Narayan/movie-recommender-system-using-machine-learning.git
   cd movie-recommender-system-using-machine-learning
   ```

2. ⚙️ Set up a virtual environment:
   ```bash
   python -m venv myenv
   source myenv/bin/activate  # For Windows: venv\Scripts\activate
   ```

3. 🛠️ Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. 💻 Run the application:
   ```bash
   streamlit run app.py
   ```

## 💡 Usage
- Start the application and access the web interface.
- Search for movies by title.
- Get personalized recommendations based on your interactions.

## 🗒 Project Structure
```
movie-recommender-system/
├── data/                # Dataset files
├── models/              # Trained models
├── notebooks/           # Jupyter notebooks for experimentation
├── src/                 # Source code
│   ├── data_loader.py    # Data loading utilities
│   ├── recommender.py    # Recommendation algorithms
│   └── app.py            # Web application entry point
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

## ⚙️ Recommendation Techniques

### 🔄 Content-Based Filtering
- Uses movie metadata (e.g., genres, keywords) to recommend similar movies.

### 🔢 Collaborative Filtering
- Implements matrix factorization techniques (such as Singular Value Decomposition, SVD) to recommend movies based on user interactions.

### 🔗 Hybrid Model
- Combines content-based and collaborative filtering for enhanced recommendations.

## 📊 Example Output
```
Recommended Movies for User 123:
1. Inception (2010)
2. The Dark Knight (2008)
3. Interstellar (2014)
```

## 📜 Dependencies
- Python 3.8+
- Pandas
- NumPy
- Scikit-learn
- Flask (for the web interface)
- Surprise (for collaborative filtering)

## 📚 Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## 🛦️ License
This project is licensed under the MIT License.

## 👏 Acknowledgements
- [MovieLens Dataset](https://www.kaggle.com/datasets/ahsanaseer/top-rated-tmdb-movies-10k?fbclid=IwAR2MpWrWpcw2QNCv_FZg2l0sjBh9xAvhrqtnZBO9K-QS6PHI1aHkdB6qLa0)
- [Scikit-learn](https://scikit-learn.org/)
- [Flask](https://flask.palletsprojects.com/)

