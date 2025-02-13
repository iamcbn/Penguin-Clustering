![Alt text](https://imgur.com/orZWHly.png=80)
source: @allison_horst https://github.com/allisonhorst/penguins

# **Penguin Clustering Analysis 🐧**  

## **Overview**  
This project applies **K-Means clustering** to the **Palmer Penguins dataset**, grouping penguins based on their morphological features. The goal is to identify natural clusters that may correspond to different species or ecological adaptations.  

## **Dataset**  
The dataset contains measurements of penguins, including:  
- **Culmen Length (mm)**  
- **Culmen Depth (mm)**  
- **Flipper Length (mm)**  
- **Body Mass (g)**  
- **Sex (Encoded for Clustering)**  

## **Key Steps in Analysis**  
1. **Data Preprocessing**  
   - Handled missing values.  
   - Encoded categorical variable (Sex).  
   - Standardized numerical features.  

2. **Clustering with K-Means**  
   - Determined the optimal number of clusters using **Elbow Method** and **Silhouette Score**.  
   - Applied **K-Means with k=5**, extracting cluster centroids.  

3. **Results & Insights**  
   - Identified five distinct clusters with meaningful differences in penguin size and morphology.  
   - Found that **flipper length and body mass** play a key role in cluster differentiation.  

## **Project Structure**  
```
📂 Penguin-Clustering  
│── 📜 README.md            # Project overview  
│── 📜 penguins.csv         # Raw dataset  
│── 📜 clustering_analysis.ipynb # Jupyter Notebook with code
|── 📜  Clustering_Antarctic_Penguin_Species.pdf
│── 📂 results              # Visualizations and outputs   
```

## **How to Run**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/iamcbn/penguin-clustering.git
   cd penguin-clustering
   ```
2. Open and run `clustering_analysis.ipynb` in Jupyter Notebook.

## **Next Steps**  
- Compare clusters with actual species labels.  
- Try different clustering methods like **DBSCAN** or **Hierarchical Clustering**.  
- Incorporate environmental factors to enhance analysis.  

## **Contributions**  
Feel free to fork this repo, open issues, or submit pull requests! 🚀 
