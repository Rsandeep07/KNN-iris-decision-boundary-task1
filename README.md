# KNN-iris-decision-boundary-task1

<!-- =============================================== -->
<!--                ABOUT THE REPOSITORY             -->
<!-- =============================================== -->
# KNN Iris Decision Boundary

This repository demonstrates **K-Nearest Neighbors (KNN)** classification on the **Iris dataset**, focusing on **decision boundary visualization** for different values of `k` and distance metrics.

<!-- =============================================== -->
<!--                     FEATURES                   -->
<!-- =============================================== -->
- Explore Iris dataset (Sepal Length & Sepal Width, Setosa vs Versicolor)  
- Train KNN models with different values of `k`  
- Visualize 2D decision boundaries  
- Compare Euclidean vs Manhattan distance  

<!-- =============================================== -->
<!--                   HOW TO RUN                   -->
<!-- =============================================== -->
1. Clone the repository:
```bash
git clone https://github.com/Rsandeep07/KNN-iris-decision-boundary-task1.git
cd knn-iris-decision-boundary
2.Install dependencies:
pip install -r requirements.txt
3.Open the notebook:
jupyter notebook notebooks/knn_iris.ipynb
4.Run all cells to see data exploration, KNN models, and decision boundary visualizations.

<!-- =============================================== -->
<!--                  REQUIREMENTS                   -->
<!-- =============================================== -->

- Python 3.x
- numpy
- pandas
- matplotlib
- scikit-learn



<!-- =============================================== -->
<!--                  OBSERVATIONS                   -->
<!-- =============================================== -->

- Small k -> jagged boundaries, may overfit
- Large k -> smooth boundaries, may underfit
- Euclidean -> circular neighborhoods
- Manhattan -> diamond-shaped neighborhoods
- Recommended: k = 5, Euclidean distance
