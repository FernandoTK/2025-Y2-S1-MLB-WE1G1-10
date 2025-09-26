# 🎷| Predicting Music Genre from Audio Features

## 1. Project Overview
** 🔍 Problem Statement:**  
Manual labeling of music genres is time-consuming and subjective. This project aims to predict the genre of a song using pre-extracted audio features from the Spotify Tracks dataset.

** 🎯 Goal:**  
- Build a supervised machine learning model to classify music tracks into 125 genres.  
- Demonstrate preprocessing, feature engineering, dimensionality reduction, and EDA.  
- Provide a clean and well-documented pipeline that can be reused.

** 💡 Motivation:**  
- Streaming platforms like Spotify and Apple Music rely on genre-based recommendations.  
- Accurate genre prediction improves playlist curation and user satisfaction.  
- Using pre-extracted audio features reduces heavy processing of raw audio.


## 2. Dataset Details 📂
**Dataset Name:** Spotify Tracks Dataset 
**Source:** [Kaggle](https://www.kaggle.com/datasets/thedevastator/spotify-tracks-genre-dataset)
**Size:** ~114,000 rows, 20+ numeric features  
**Target Variable:** `Genre` (125 categories) 

** 🎵 Features Include:**  
- `Tempo` (BPM)  
- `Danceability`  
- `Energy`  
- `Loudness` (dB)  
- `Duration` (ms)  
- `Liveness`  
- `Speechiness`

  
## 3. Preprocessing Techniques ⚙️
1. 🔍 **Handle Missing Values & Duplicates** – Identify and clean missing or duplicate rows to ensure data quality.  
2. 🏷️ **Label / One-hot Encoding** – Convert categorical features like `Genre` into numerical values for ML models.  
3. 📊 **Outlier Removal** – Detect and remove extreme numeric values to reduce bias and improve model performance.  
4. ⚖️ **Normalization / Scaling** – Scale numeric features so all values are in the same range.  
5. 🛠️ **Feature Engineering** – Create new meaningful features, e.g., `tempo_per_energy`.  
6. 🔹 **Dimensionality Reduction (PCA)** – Reduce feature dimensions for visualization and easier analysis.  


 ## 4. Group Members & Roles 🙋🙎‍♀️
| Member Name | IT Number | Name | Preprocessing Technique |
|-------------|-----------|------------------------|----------------|
| Member 1    | IT24100164  | Hansani P. T. K.  | Handle Missing Values & Duplicates |
| Member 2    | IT24100569  | Wathsiluni D.B.S.  | Label / One-hot Encoding |
| Member 3    | IT24100279  | Dissanayake D.M.V.I.  | Outlier Removal |
| Member 4    | IT24100252  | Bharathy S. S.  | Normalization / Scaling |
| Member 5    | IT24100664  | Prarthana J.A D.A.S.  | Feature Engineering |
| Member 6    | IT24100567  | Jeyakumar M.S.  | Dimensionality Reduction (PCA) |


## 5. How to Run the Code 🚀
**Step 1: Clone the repository**
```
git clone https://github.com/FernandoTK/2025-Y2-S1-MLB-WE1G1-10.git
cd Group_2025-Y2-S1-MLB-WE1G1-10
```

**Step 2: Install dependencies**
```pip install -r requirements.txt```

**Step 3: Open Jupyter Notebook**
```jupyter notebook```

**Step 4: Run individual preprocessing notebooks**
```
notebooks/IT24100164_preprocessing_missing_values.ipynb 
notebooks/IT24100569_Encoding_categorical_variables.ipynb
notebooks/IT24100279_OutlierRemoval.ipynb
notebooks/IT24100252_Preprocessing_scaling-Member 04.ipynb
notebooks/IT24100664_Feature_Engineering.ipynb
notebooks/IT24100567_Dimensionality_Reduction.ipynb
```

**Step 5: Run the integrated pipeline**
```
group_pipeline/2025-Y2-S1-MLB-WE1G1-10-group_pipeline.ipynb
```




