# Machine Learning for 2D Semantic Mapping (Project 2)

### Machine Learning Course — MEEC FEUP, 2025

### Project Grade
The project was awarded a grade of **20/20**.

### Project Objectives and Approach
This repository contains **Project 2** from the *Machine Learning* course at **FEUP**. The project applies **machine learning techniques** to **2D sensor data**, specifically using **LiDAR measurements** to model and predict the environment. The project compares the performance of **Neural Networks (NN)** with **K-Nearest Neighbors (K-NN)** for classification tasks, and uses **K-means clustering** to segment the data when multiple objects are present in the environment. The project focuses on the following:

- **2D state estimation** with **LIDAR measurements**
- **Semantic mapping**: The robot is capable of classifying nearby objects based on its LIDAR measurements.
- **Comparison of models**: **Neural Networks (NN)** vs. **K-Nearest Neighbors (K-NN)** for classification.
- **K-means clustering**: Used to segment the data when multiple objects are detected, enabling better classification of objects.
- **Evaluation of models** using **Mean Squared Error (MSE)** and **classification accuracy**.
- **Data visualization** to display predictions, object classifications, and the generated map.

This project demonstrates the application of machine learning techniques to predict and classify objects in a 2D space, using **LIDAR sensor data** for building semantic maps.

## Overview
In this project, the following steps were performed:
1. **Data Loading and Preprocessing**: The dataset, which includes LIDAR measurements and object classifications, was preprocessed.
2. **Modeling and Classification**: Applied **Neural Networks (NN)** and **K-Nearest Neighbors (K-NN)** for classification tasks. **K-means clustering** was used to segment the data when multiple objects were present in the environment.
3. **Evaluation**: The performance of both models was compared using **Mean Squared Error (MSE)** and **classification accuracy**, comparing predicted object classifications to ground truth.
4. **Visualization**: Visualized the robot's environment, the predicted classifications, and the generated semantic map.

The project relies on the following libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `tensorflow`
- `keras`

## Authors
This project was developed as part of **Machine Learning Project 2** at **FEUP** (2025).

* **Afonso Mateus**  afonso.tomas.mateus@gmail.com
* **David Brás**     davidfsbras@gmail.com

---

### *Machine Learning for 2D Semantic Mapping (Project 2), FEUP MEEC Machine Learning Course, 2025.*
