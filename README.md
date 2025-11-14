# 🎌 Anime Recommendation System  

## 💡 Project Overview  
This project builds an intelligent **Anime Recommendation System** that suggests anime titles to users based on similarity, user ratings, and genre preferences.  

Using **machine learning and data preprocessing techniques**, this system leverages cosine similarity and content-based filtering to deliver personalized anime recommendations — just like how Netflix or MyAnimeList would!  

---

## 🧠 Objectives  
- Clean and preprocess the Anime dataset (handling missing values, encoding, etc.)  
- Apply **Content-Based Filtering** to recommend similar anime  
- Utilize **Cosine Similarity** to measure similarity between anime titles  
- Build a recommendation function that provides top relevant suggestions  

---

## ⚙️ Technologies Used  
- **Python** 🐍  
- **Pandas**, **NumPy** — Data manipulation and preprocessing  
- **Scikit-learn** — Feature extraction & similarity calculation  
- **Matplotlib**, **Seaborn** — Data visualization and analysis  

---

## 📁 Files Included  
| File Name | Description |
|------------|-------------|
| `Anime_Recommendation_System.ipynb` | Jupyter Notebook with data cleaning, EDA, and recommendation logic |
| `anime.csv` | Dataset containing anime names, genres, ratings, and other attributes |
| `recommendations.csv` | Sample output of recommended anime |
| `README.md` | Project documentation |

---

## 📊 Visualizations  
- Anime rating distributions  
- Genre frequency charts  
- Similarity heatmaps between anime titles  

*(Upload colorful plots and output screenshots to make your repo visually appealing!)*  

---

## ⚙️ Methodology  
1. **Data Cleaning:**  
   - Handled missing values and standardized text fields.  
   - Converted “Unknown” or null episodes to numeric values for analysis.  

2. **Feature Engineering:**  
   - Extracted keywords and genres for vectorization.  
   - Applied **TF-IDF Vectorization** to capture important textual features.  

3. **Similarity Calculation:**  
   - Used **Cosine Similarity** to measure closeness between anime descriptions.  

4. **Recommendation Function:**  
   - Returns top *N* similar anime titles for any given anime name.  
