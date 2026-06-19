# 🎬 Movie Recommender System

## 📌 Project Overview
A content-based movie recommendation system built with Python and deployed using Streamlit. The system recommends movies based on similarity using Cosine Similarity algorithm.

## 🚀 Live Demo
Coming soon - Will deploy to Streamlit Cloud

## 📊 Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)

- **Python** - Core programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Scikit-Learn** - Machine learning (Cosine Similarity, CountVectorizer)
- **Streamlit** - Web application framework
- **TMDB API** - Movie data and posters
- **Pickle** - Model serialization
- **Requests** - API calls

## ✨ Features
- Content-based recommendations using Cosine Similarity
- Dynamic movie poster fetching via TMDB API
- Interactive UI with 5-column recommendation grid
- Dataset of 4,800+ movies
- Sidebar for movie selection
- Responsive design

## 📁 Project Structure
```
movie-recommender-system/
├── app.py                  # Streamlit application
├── model/
│   ├── movie_list.pkl     # Movie dataset (4800+ movies)
│   └── similarity.pkl     # Cosine similarity matrix
├── data/
│   └── tmdb_5000_movies.csv  # TMDB dataset
├── notebooks/
│   └── EDA.ipynb          # Data exploration notebook
├── requirements.txt        # Dependencies
├── .gitignore
└── README.md
```

text

## 🛠️ Installation

### Prerequisites
- Python 3.8+
- Git

### Steps
```bash
# 1. Clone the repository
git clone https://github.com/dahalsamir222111/movie-recommender-system.git
cd movie-recommender-system

# 2. Create virtual environment
python -m venv venv

# 3. Activate virtual environment
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run the app
streamlit run app.py

🔮 Future Improvements
User rating-based recommendations

Filter by genre

Watchlist feature

More detailed movie info

User authentication

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first.

📝 License
MIT

📧 Contact
Samir Dahal
📧 dahalsamir111222@gmail.com
🔗 LinkedIn
🐙 GitHub

⭐️ If you like this project, please give it a star!
