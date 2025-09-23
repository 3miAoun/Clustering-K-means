# Customer Segmentation with K-Means

This project applies **K-Means clustering** to the popular **Mall Customers dataset** to segment customers based on their **Annual Income** and **Spending Score**.  
The analysis helps identify customer groups for better marketing and business decision-making.

---

## 📂 Project Structure
- **kmeans_sem_5.py** → Main script containing data loading, preprocessing, clustering, and visualization.

---
## 📌 Dataset

The dataset used is the Mall Customers dataset, which contains customer information such as:

  - Customer ID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)
  - 
---

## 📊 Features
- Loads and explores the Mall Customers dataset.
- Standardizes data for better clustering results.
- Uses:
  - **Elbow Method** (WCSS) to find the optimal number of clusters.
  - **Silhouette Score** to evaluate clustering quality.
- Trains a **K-Means model** with the chosen number of clusters.
- Visualizes:
  - Elbow curve
  - Silhouette scores
  - Customer clusters with centroids
- Provides detailed **cluster profiles** (age, income, spending score, gender distribution).

---
### 📈 Example Outputs

- Elbow Curve: Helps determine optimal number of clusters  
- Silhouette Score Plot: Evaluates clustering quality  
- Customer Segmentation Plot: Visualizes clusters by income and spending behavior  
---
▶️ How to Run

Place the dataset file `Mall_Customers.csv` in the project directory.

Run the script:
```bash
python kmeans_sem_5.py
```
View outputs:

  - Console: dataset info, cluster statistics, and profiles.
  - Graphs: Elbow method, Silhouette scores, and cluster visualizations.
## 🛠️ Requirements
Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
