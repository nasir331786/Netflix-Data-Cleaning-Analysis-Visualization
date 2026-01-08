# Netflix Data Cleaning, Analysis and Visualization

Comprehensive exploratory data analysis and visualization of Netflix Movies and TV Shows dataset using Python.

## 📊 Project Overview

This project performs comprehensive data cleaning, exploratory data analysis (EDA), and visualization on the Netflix Movies and TV Shows dataset. It demonstrates strong data science and analytics fundamentals.

## 🎯 Project Objectives

- Load and explore Netflix dataset
- Clean and preprocess the data
- Handle missing values
- Remove duplicates
- Perform exploratory data analysis
- Visualize content distribution trends
- Analyze ratings, countries, genres, and directors
- Generate insights from data

## 📁 Project Structure

```
Netflix-Data-Project/
├── Netflix_Data_Analysis.ipynb    # Main Jupyter Notebook with all analysis
├── netflix1.csv                    # Netflix dataset
├── README.md                       # Project documentation
└── requirements.txt                # Python dependencies
```

## 🛠️ Tools & Technologies

**Programming Language:**
- Python 3.x

**Libraries Used:**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Data visualization
- **seaborn** - Statistical data visualization
- **wordcloud** - Word cloud generation

## 📊 Analysis Performed

### 1. Data Cleaning
- Removed duplicate entries
- Handled missing values
- Converted date columns to proper datetime format

### 2. Exploratory Data Analysis (EDA)
- Dataset shape: 8,790 entries × 10 columns
- Content type distribution analysis
- Rating patterns analysis
- Geographic distribution analysis

### 3. Visualizations Created
- Movies vs TV Shows (Bar & Pie charts)
- Ratings distribution chart
- Top 10 countries with content
- Monthly content trend analysis
- Yearly content growth trends
- Top 10 movie genres
- Top 10 TV show genres
- Top 15 directors analysis
- Word cloud of movie titles

## 🔍 Key Findings

### Content Distribution
- **Movies**: 6,126 (69.7%)
- **TV Shows**: 2,664 (30.3%)

### Geographic Distribution
- USA leads with 3,240+ entries
- India has 1,057 entries
- UK has 638 entries

### Rating Patterns
- Most common rating: TV-MA (3,205 entries)
- Second most common: TV-14 (2,157 entries)

### Genre Preferences
**Movies:**
- International Movies (2,752)
- Dramas (2,426)
- Comedies (1,674)

**TV Shows:**
- International TV Shows (1,349)
- TV Dramas (762)
- TV Comedies (520)

### Content Growth Trends
- Significant growth from 2015-2019
- Peak year: 2019 with 1000+ movies and 600+ TV shows
- Steady monthly additions averaging 500+ content pieces

## 📝 Dataset Information

**Dataset Name:** Netflix Movies and TV Shows
**File:** netflix1.csv

**Columns:**
- show_id
- type (Movie/TV Show)
- title
- director
- country
- date_added
- release_year
- rating
- duration
- listed_in (genres)

## 🚀 How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/nasir331786/Netflix-Data-Cleaning-Analysis-Visualization.git
cd Netflix-Data-Cleaning-Analysis-Visualization
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Analysis
- Open `Netflix_Data_Analysis.ipynb` in Jupyter Notebook or Google Colab
- Execute cells sequentially to see the analysis and visualizations

## 📦 Dependencies

See `requirements.txt` for all required packages:
- pandas
- numpy
- matplotlib
- seaborn
- wordcloud

## 👨‍💻 Author

**Nasir Husain**
- Data Science Enthusiast
- Data Science Intern at Innomatics Research Labs
- GitHub: [@nasir331786](https://github.com/nasir331786)

## 📚 Skills Demonstrated

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Python Programming
- Pandas Data Manipulation
- Statistical Analysis
- Data Storytelling

## 📧 Contact

For questions or collaboration opportunities, feel free to reach out!

## 📄 License

This project is open source and available under the MIT License.

---

**Last Updated:** January 2026

**Status:** Complete ✅
