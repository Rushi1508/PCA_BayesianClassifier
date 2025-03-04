# PCA Bayesian Classification

## Project Overview
This project consists of two major parts:
1. **Collaborative Filtering-based Recommender System**
   - Utilizes a user-book sparse matrix derived from a `.libsvm` file.
   - Computes cosine similarity to identify top-k similar users.
   - Generates book recommendations based on weighted ratings of similar users.

2. **PCA-based Bayesian Classification**
   - Implements Principal Component Analysis (PCA) for dimensionality reduction.
   - Assumes normal distributions for each class and estimates parameters.
   - Uses Bayesian Decision Theory for classification.
   - Classifies images from the Fashion MNIST dataset (`T-shirt` vs. `Sneaker`).

## Installation
Ensure you have Python installed. Then install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage
1. Open `Merged_Project_Notebook.ipynb` in Jupyter Notebook.
2. Run the cells to process data, train models, and generate results.
3. The recommender system saves the recommendations to `final_recommendations_from_libsvm.csv`.
4. The classifier outputs training and testing accuracy along with visualizations of PCA-reduced data.

## Dataset Information
### **Recommender System**
- Uses a dataset with user-book interactions stored in `.libsvm` format.
- Requires `Books.csv` for mapping ISBNs to book titles.

### **PCA-based Classification**
- Utilizes a subset of Fashion MNIST dataset.
- 6,000 training images and 1,000 test images per class.
- Images are 28x28 grayscale, transformed into a 784-dimensional feature vector.

## Outputs
- **Recommender System:** `final_recommendations_from_libsvm.csv`
- **Classifier Performance:** Training accuracy, testing accuracy, and visualizations.

## Contributors
- **Rushi Parikh**

## License
This project is for educational purposes.

