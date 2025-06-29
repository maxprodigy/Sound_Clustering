# Sound Clustering Project

This project focuses on clustering a dataset of **unlabeled sound files** using machine learning techniques. The goal is to group similar sounds together and explore the effectiveness of different clustering methods after reducing the complexity of the audio features.

---

## Project Structure
- **Feature Extraction:**  
  Extracted Mel Frequency Cepstral Coefficients (MFCCs) from each audio file to represent the key features of the sounds.
  
- **Dimensionality Reduction:**  
  Applied Principal Component Analysis (PCA) and t-Distributed Stochastic Neighbor Embedding (t-SNE) to reduce the number of features and make the data easier to visualize.

- **Clustering Algorithms:**  
  Used K-Means and DBSCAN to find natural groupings in the data.
  
- **Evaluation:**  
  Assessed the clustering results using visual inspection and silhouette scores.

---

## Key Findings
- **K-Means** successfully formed clear and well-separated clusters.
- **DBSCAN** struggled to form distinct groups, possibly due to the density of the dataset and sensitivity to parameter settings.
- **Dimensionality reduction was essential** to visualize and understand the high-dimensional audio data.

---

## Dataset

`unlabelled_sounds/` – [Link](https://drive.google.com/file/d/1bme1IuScdIWjzFkYPOcWzFOgD50MS_zR/view?usp=drive_link)

---

## How to Run
1. Open the Jupyter Notebook.
2. Run all cells in order to extract features, reduce dimensions, apply clustering, and visualize results.
3. Review the markdown cells for analysis and reflections.

---

## Requirements
- Python 3.x
- Libraries: `librosa`, `numpy`, `matplotlib`, `sklearn`

---

## Acknowledgments
This project was completed as part of the Sound Clustering Assignment.
