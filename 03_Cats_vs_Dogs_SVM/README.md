# Digit Recognition using Support Vector Machine (SVM)

This is a part of my **Machine Learning Mini Project Series**, where I dive into classic ML models on real-world and benchmark datasets. 
In this project, I implemented a **Support Vector Machine (SVM)** to recognize handwritten digits (0–9) using Scikit-learn’s built-in dataset.

## Model: Support Vector Machine (SVM)

SVM is a supervised learning algorithm that finds the hyperplane which best separates classes. 
It's well-suited for image classification tasks like digit recognition due to its ability to handle high-dimensional data.

## Dataset :-

 **Dataset Used:** `sklearn.datasets.load_digits()`  
No external downloading needed — it's built-in!  
The dataset contains:
- 1,797 grayscale 8x8 images (flattened to 64 features)
- Labels from 0 to 9
- Each image is a handwritten digit

## Tech Stack :-

✤ **Python**
✤ **Scikit-learn**
✤ **Matplotlib** (for visualization)
✤ **Seaborn** (optional, for heatmaps & plots)
✤ **NumPy**

## What I Did :-

- Loaded and explored the digits dataset  
- Visualized sample images using Matplotlib  
- Preprocessed data (flattened, normalized if needed)  
- Split into train-test sets (80-20)  
- Trained **SVM Classifier** using `SVC()` from Scikit-learn  
- Evaluated using:
  - Accuracy Score  
  - Confusion Matrix  
  - Classification Report  
- Visualized predictions vs actual labels

## Results :-
✤ Achieved **~98%+ accuracy** on the test set.
✤ Confusion matrix showed strong performance across all classes.  
✤ SVM proved solid for small-to-medium scale image classification.

## How to Run :-
1. Clone the repo
2. Open the Jupyter Notebook / Colab notebook
3. Make sure to install required libraries:
   
pip install scikit-learn matplotlib numpy seaborn
