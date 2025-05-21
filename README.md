# Netflix-Clustering
This project uses TF-IDF and KMeans clustering to group Netflix titles based on their descriptions. The goal is to categorize content into themes or genres to improve recommendations and insights
<<<<<<< HEAD
=======
# Netflix Clustering

This project focuses on clustering Netflix titles (movies and TV shows) using natural language processing techniques on their descriptions.

## 📌 Objective

Group Netflix titles based on thematic similarity using TF-IDF vectorization and KMeans clustering, helping discover content-based patterns.

## 🧰 Tech Stack

- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn
- Natural Language Processing (NLP)

## 🧪 Methodology

1. **Data Preprocessing**
   - Cleaned description text (lowercase, removed punctuation and stopwords)
2. **Vectorization**
   - Used `TfidfVectorizer` to convert descriptions to numerical form
3. **Clustering**
   - Applied KMeans clustering
   - Evaluated using Silhouette Score
4. **Visualization**
   - Word clouds, heatmaps, pair plots, and cluster samples

## 📊 Results

Clusters were formed grouping titles with similar themes and genres based on their descriptions. Some interesting clusters were found related to horror, documentaries, romance, and foreign titles.

## 📁 Project Structure

- `netflix_clustering.ipynb`: Main notebook
- `data/`: Contains the dataset
- `results/`: Visualizations and cluster samples (optional)

## 🚀 How to Run

```bash
git clone https://github.com/21ayeshashaik/Netflix-Clustering.git
cd Netflix-Clustering
jupyter notebook

>>>>>>> 528ba6c62f8d2ab52dd628117734afd7019d2083
