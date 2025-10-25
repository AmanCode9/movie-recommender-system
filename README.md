# 🎬 Movie Recommender System

A machine learning-based movie recommendation system that suggests similar movies based on user selection. Built with Python and Streamlit, powered by content-based filtering and The Movie Database (TMDB) API.

## ✨ Features

- **Smart Recommendations**: Get 5 similar movie suggestions based on your selection
- **Visual Experience**: Displays movie posters fetched from TMDB API
- **Interactive UI**: Clean and intuitive interface built with Streamlit
- **Content-Based Filtering**: Uses movie metadata and similarity algorithms
- **Real-time Results**: Instant recommendations as you select movies

## 🚀 Demo
<img width="1783" height="652" alt="image" src="https://github.com/user-attachments/assets/4bfb43b8-76d4-4576-a5e2-53aa4ea9182c" />


## 🛠️ Technologies Used

- **Python 3.x**
- **Streamlit** - Web application framework
- **Pandas** - Data manipulation
- **Scikit-learn** - Machine learning algorithms
- **TMDB API** - Movie data and posters
- **Pickle** - Model serialization

## 📋 Prerequisites

Before running this application, make sure you have:

- Python 3.7 or higher installed
- pip (Python package manager)
- TMDB API key ([Get one here](https://www.themoviedb.org/settings/api))

## 💾 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/AmanCode9/movie-recommender-system.git
   cd movie-recommender-system
   ```

2. **Create a virtual environment (recommended)**
   ```bash
   python -m venv .venv
   
   # On Windows
   .venv\Scripts\activate
   
   # On macOS/Linux
   source .venv/bin/activate
   ```

3. **Install required packages**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up TMDB API key**
   - Get your API key from [TMDB](https://www.themoviedb.org/settings/api)
   - Add it to your `app.py` file or create a config file

## 🎯 Usage

1. **Run the application**
   ```bash
   streamlit run app.py
   ```

2. **Open your browser**
   - The app will automatically open at `http://localhost:8501`
   - If not, navigate to the URL shown in your terminal

3. **Get recommendations**
   - Select a movie from the dropdown menu
   - Click the "Recommend" button
   - View 5 similar movies with their posters

## 📁 Project Structure

```
movie-recommender-system/
├── app.py                  # Main Streamlit application
├── movie_dict.pkl          # Preprocessed movie data
├── similarity.pkl          # Similarity matrix
├── movies.pkl              # Movie dataset
├── requirements.txt        # Python dependencies
├── .gitignore             # Git ignore rules
├── Procfile               # Deployment configuration (if any)
└── README.md              # Project documentation
```

## 🧠 How It Works

1. **Data Processing**: Movie metadata is preprocessed and vectorized
2. **Similarity Calculation**: Cosine similarity is computed between movies
3. **Recommendation Engine**: When a user selects a movie, the system finds the most similar movies based on the similarity matrix
4. **Poster Fetching**: Movie posters are dynamically fetched from TMDB API
5. **Display**: Results are displayed in an attractive grid layout

## 📊 Dataset

This project uses movie data from [TMDB (The Movie Database)](https://www.themoviedb.org/). The dataset includes:
- Movie titles
- Genres
- Keywords
- Cast and crew information
- Movie overviews

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Aman**
- GitHub: [@AmanCode9](https://github.com/AmanCode9)
- Repository: [movie-recommender-system](https://github.com/AmanCode9/movie-recommender-system)

## 🙏 Acknowledgments

- [TMDB](https://www.themoviedb.org/) for providing the movie database API
- [Streamlit](https://streamlit.io/) for the amazing web framework
- The open-source community for inspiration and resources

## 📧 Contact

If you have any questions or suggestions, feel free to:
- Open an issue on GitHub
---

⭐ If you found this project helpful, please give it a star on GitHub!
