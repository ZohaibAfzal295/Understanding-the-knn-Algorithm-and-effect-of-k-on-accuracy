# KNN Classification on the Iris Flower Dataset

## Overview

This project showcases a hands-on implementation of the **K-Nearest Neighbors (KNN)** algorithm using the well‑known **Iris Flower Dataset**.  
Rather than treating it as a simple classification task, the goal was to explore how tuning the value of **K** influences decision boundaries and prediction accuracy.

---

## What This Project Is About

The Iris dataset is a classic introduction to supervised learning.  
In this project, I used it to build intuition around:

- How KNN behaves with different neighborhood sizes  
- The impact of data splitting on model reliability  
- Visual inspection of patterns in a multi-class dataset  
- Evaluating performance using accuracy metrics  

The entire workflow was developed in **Google Colab**, ensuring portability and ease of experimentation.

---

## Technologies & Tools

- **Python**
- **Google Colab Notebook**

### Dataset Source
- `sklearn.datasets.load_iris()`

### Project Workflow Involves
- Data preprocessing  
- Hyperparameter variation  
- Visualization of results  
- Model evaluation  

---

## Required Libraries

### Preinstalled in Google Colab
- **numpy** – numerical calculations  
- **matplotlib** – plotting graphs  

### External Install (if missing)
- **scikit-learn** for:
  - Loading the Iris dataset  
  - Splitting data into training/testing sets  
  - KNN classifier  
  - Accuracy measurement  

Install with:

```bash
!pip install scikit-learn
```

---

## Closing Note

This project helped deepen my intuition about non‑parametric models and their sensitivity to hyperparameters like K.  
Exploring the Iris dataset with KNN offers a simple yet powerful introduction to classification concepts.

Thanks for taking a look at this work!
