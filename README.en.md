> 📘 Este README está disponível : [Português](README.md) | [English](README.en.md)

# Aulas-IA (AI Lessons)
A collection of notebooks developed during my Artificial Intelligence classes.

---

## 1. Iris Dataset
Performs an exploratory analysis of the Iris Dataset with focus on visualizations and supervised classification.
### This notebook includes:
- Loading the Iris Dataset using seaborn and initial visualization with pandas.
- Descriptive statistics, missing value checks, and class distribution analysis.
- Graphical visualizations using matplotlib and seaborn:
  - Histograms, pairplots, boxplots, violin plots, and correlation heatmaps.
- Splitting the data into training and test sets using train_test_split.
- Training a Logistic Regression model with scikit-learn.
- Model evaluation with accuracy, confusion matrix, and classification report.
- Simulated prediction of a new sample based on morphological attributes.
### Ideal for showcasing a complete modeling pipeline for a multiclass structured classification problem.

---

## 2. Data Engineering
Applies advanced data engineering transformations on a synthetic health-related dataset to prepare data for analysis or modeling.
### This notebook includes:
- Generation of synthetic patient data (age, gender, smoking status, cholesterol, etc.).
- Conversion of continuous variables into binary thresholds.
- Classification into categorical ranges to support segmentation.
- Calculation and categorization of BMI (Body Mass Index).
- Creation of dummy variables for categorical encoding.
- Logarithmic transformation of skewed variables.
- Visual comparison of original and transformed data through histograms.
### Ideal for demonstrating good data preparation practices in biomedical contexts and understanding the impact of transformations on dataset structure.

---

## 3. Perceptron
Applies a simple Perceptron classifier along with an MLP (Multilayer Perceptron) on both synthetic and real binary classification problems.
### This notebook includes:
- Manual implementation of a basic Perceptron with Heaviside activation.
- Creation of a synthetic dataset with two clearly separated classes using NumPy.
- Training and visualization of decision boundaries with Matplotlib.
- Testing different learning rates and epoch configurations.
- Application of scikit-learn’s MLPClassifier to the Breast Cancer dataset.
- Data scaling with StandardScaler and splitting with train_test_split.
- Hyperparameter tuning using GridSearchCV.
- Model evaluation using accuracy and classification report.
### Ideal for understanding linear learning fundamentals, experimenting with parameters, and applying neural networks to real problems.

---

## 4. K-Means
Uses the K-Means algorithm for unsupervised clustering on the Wine Dataset to identify natural patterns among cultivars.
### This notebook includes:
- Loading the Wine Dataset via scikit-learn.
- Scaling numeric features with StandardScaler.
- Training the KMeans model with 3 clusters.
- Evaluating clustering quality with Silhouette Score.
- Reducing dimensionality with PCA.
- Visualizing the resulting clusters in 2D scatter plots.
- Optional comparison with real class labels for illustration.
### Ideal for exploring clustering on real datasets, dimensionality reduction, and cluster evaluation techniques.
---

## 5. Practice Test 1
Executes a full data analysis and machine learning pipeline using the 'Marketing Campaign' dataset, integrating preprocessing, clustering, and supervised classification.
### This notebook includes:
- Loading and initial inspection of real customer data.
- Date processing, feature selection, and handling of missing values.
- Numeric feature scaling with StandardScaler.
- Dimensionality reduction using PCA for visualization.
- K-Means clustering:
  - Determining the optimal number of clusters via Elbow Method.
  - Evaluating cluster cohesion with Silhouette Score.
- Generating pseudo-labels from cluster outputs.
- Training a supervised classification model (LogisticRegression).
- Evaluating model performance with accuracy and classification report.
### Ideal for reinforcing clustering on real datasets, feature engineering, and hybrid applications of supervised and unsupervised learning.

---

## 6. Practice Test 2
Explores fundamental image processing techniques using OpenCV within Google Colab, applied to both real and synthetic images.
### This notebook includes:
- Installing and using opencv-python-headless for Colab compatibility.
- Loading and displaying images with cv2 and Matplotlib.
- Color space conversion: BGR, RGB, Gray, and HSV.
- Histogram generation and comparison.
- Histogram equalization to enhance image contrast.
- Applying smoothing filters: mean, Gaussian, and median.
- Global and adaptive thresholding for binary segmentation.
- Edge detection with Canny and contour extraction using cv2.findContours.
### Ideal for introducing practical computer vision concepts and preparing images for segmentation, recognition, and visual analysis in AI projects.

---

## 7. Titanic Classifier
Performs supervised classification to predict passenger survival based on Titanic Dataset using statistical techniques and machine learning.
### This notebook includes:
- Loading the Titanic Dataset via seaborn.
- Data exploration: descriptive stats, visualizations (histograms, boxplots, pairplots, heatmaps), and missing value analysis.
- Categorical variable conversion with direct mapping.
- Feature selection for prediction.
- Train/test split using train_test_split.
- Training a HistGradientBoostingClassifier with scikit-learn.
- Model evaluation with accuracy, confusion matrix, and classification report.
- Confusion matrix visualization with heatmap.
- Simulated prediction for random passenger profiles.
### Ideal for demonstrating a complete supervised modeling workflow on real-world data with a focus on feature engineering, evaluation, and historical applications.
