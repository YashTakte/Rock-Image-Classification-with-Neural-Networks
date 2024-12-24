# **Rock Image Classification Project**

This project aims to classify rock images into three categories: I, M, and S, based on their features. Various techniques, including dimensionality reduction, clustering, and deep learning, are used to analyze and classify the images.

## **Dataset**

The rock image dataset used in this project is available at the following link:
https://osf.io/d6b9y/

## **Key Features:**

- **Dimensionality Reduction**:
  - **PCA**, **t-SNE**, **LLE**, and **MDS** are used to reduce the dimensionality of the image data.
  - Visualization of the reduced dimensions to understand how different rock categories are represented.

- **Clustering**:
  - **K-Means** and **EM** clustering techniques are applied to group similar images.
  - Evaluation of clustering accuracy and generation of new synthetic rock images.

- **Neural Network**:
  - A **feedforward neural network** is used to classify the images based on their category.
  - The network is trained using images from the '120 Rocks' folder for validation.
  - Performance is evaluated by comparing the neural network's embedding layer with human-provided data using **Procrustes analysis**.

- **Performance Analysis**:
  - Training and validation loss, accuracy, and the network’s parameters are reported.
  - A comparison of model performance, including clustering and neural network-based classification.

## **Technologies Used:**

- **Keras** or **PyTorch** for deep learning.
- **PCA**, **t-SNE**, **LLE**, and **MDS** for dimensionality reduction.
- **K-Means** and **Expectation Maximization (EM)** for clustering.
- **Procrustes analysis** for comparing embeddings.

## **Steps in the Project:**

1. **Data Exploration**: Analyzing the dataset and categorizing images.
2. **Dimensionality Reduction**: Reducing dimensionality and visualizing the data.
3. **Clustering**: Applying K-Means and EM to group images.
4. **Neural Network Training**: Training a deep learning model to classify the images.
5. **Evaluation**: Evaluating the model performance using loss, accuracy, and Procrustes analysis.
