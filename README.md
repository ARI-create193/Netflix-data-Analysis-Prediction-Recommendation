# 🎬 Netflix Data Analysis-Prediction-Recommendation Dashboard
A comprehensive data science project that analyzes Netflix content data and provides ML-powered insights. Built with Python and Gradio for an interactive web interface.

## 📖 Introduction
This project helps analyze Netflix streaming data to understand:
- Content distribution (Movies vs TV Shows)
- Popular genres and ratings
- Top countries and directors
- Content success prediction using ML
- Genre-based recommendation system

Perfect for data science internships and portfolio projects!

## 🚀 How to Run
### 1. Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/netflix-analytics.git
cd netflix-analytics

# Install requirements
pip install -r requirements.txt
```

### 2. Run the Dashboard
```bash
# Run the Python script
python netflix_dashboard.ipynb

# Or run in Jupyter Notebook
jupyter notebook
# Open netflix_dashboard.ipynb and run all cells
```

### 3. Open your browser
The Gradio interface will automatically open in your browser at `http://127.0.0.1:7860`

## 📊 Dashboard Features
### 📁 Data Overview
- Upload your Netflix CSV file or use sample data
- Data cleaning and preprocessing
- Dataset summary statistics
- Sample data table viewer

### 📈 Content & Rating Analysis
- **Content Distribution**: Movies vs TV Shows breakdown
- **Ratings Analysis**: Popular content ratings (PG, R, TV-MA, etc.)
- Interactive charts with insights

### 🌍 Geographic Analysis
- **Countries Analysis**: Top content-producing countries
- **Directors Analysis**: Most prolific directors
- Visual charts showing global content distribution

### 🎭 Genre Analysis
- Comprehensive genre breakdown
- Popular content categories
- Genre frequency analysis with visualizations

### 🤖 ML: Success Prediction
- Train Random Forest model for content success prediction
- Feature importance analysis
- Interactive prediction interface
- Predict success for new content based on metadata

### 🎯 ML: Recommendation System
- Genre-focused content recommendation engine
- Content-based filtering using TF-IDF
- Get personalized recommendations for any title
- Similarity scoring and genre matching

## 📊 Dataset
**Sample Data**: Included in the code (20 Netflix titles)
**Format**: CSV with columns:
- show_id, type, title, director
- country, date_added, release_year
- rating, duration, listed_in (genres)
File: netflix-data.csv (included in repository)

**Source**: [Kaggle - Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

## 🛠️ Technologies Used
- **Python** - Main programming language
- **Gradio** - Interactive web interface
- **Pandas** - Data processing and analysis
- **Matplotlib/Seaborn** - Data visualizations
- **Scikit-learn** - Machine learning models
- **TF-IDF Vectorizer** - Text analysis for recommendations
- **Random Forest** - Success prediction model

## 📁 Project Structure
```
netflix-analytics/
├── netflix_dashboard.ipynb     # Main dashboard script
├── requirements.txt          # Python dependencies
├── README.md                # This file
├── netflix-data.csv         # Optional Netflix dataset
└── screenshots/             # Dashboard screenshots
```

## 📧 Contact
*Aryan Kaminwar* - aryankaminwar@gmail.com

**GitHub**: [ Netflix Data Analysis-Prediction-Recommendation Dashboard](https://github.com/ARI-create193/Netflix-data-Analysis-Prediction-Recommendation-Dashboard)
