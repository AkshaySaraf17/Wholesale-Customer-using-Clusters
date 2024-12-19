# Wholesale Customers Clustering

This project demonstrates various clustering techniques using machine learning to analyze the wholesale customers dataset. The notebook implements different clustering algorithms to uncover patterns and group similar customers.

## Project Structure
The notebook consists of code cells with the following key components:

### 1. **Libraries Used**
- `numpy`: For numerical computations.
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For data visualization.
- `scikit-learn`:
  - `KMeans`: Partition-based clustering.
  - `AgglomerativeClustering`: Hierarchical clustering.
  - `DBSCAN`: Density-based clustering.
- `scipy`:
  - `dendrogram`, `linkage`: For hierarchical clustering visualization.
- `StandardScaler`: For feature standardization.

### 2. **Data Preprocessing**
- Standardizes the features using `StandardScaler` to ensure consistent scaling across variables.

### 3. **Clustering Techniques**
The notebook implements the following clustering algorithms:

#### - KMeans Clustering:
  - Groups data into predefined clusters.
  - Uses the elbow method to determine the optimal number of clusters.

#### - Hierarchical Clustering:
  - Uses linkage methods to create a hierarchy of clusters.
  - Visualizes results using dendrograms.

#### - DBSCAN Clustering:
  - Groups data points based on density.
  - Identifies core points, border points, and noise.

### 4. **Visualization**
- Scatter plots to display clusters.
- Dendrograms for hierarchical clustering.

## Prerequisites
- Python 3.8+
- Required libraries:
  ```bash
  pip install numpy pandas matplotlib scikit-learn scipy
  ```

## Usage
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project-directory>
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Wholesale\ Cluster-Students.ipynb
   ```

## Dataset
The dataset is assumed to be included in the notebook. Ensure the data is loaded correctly before running the clustering algorithms.

## Results
- Provides insights into customer segmentation based on purchasing patterns.
- Visual representations of clustering results.

## License
This project is licensed under the MIT License.

