#Customer Segmentation using K-Means Clustering

Welcome to the **second project** in my **Machine Learning Mini Project Series**, where I dive into unsupervised learning models to understand real-world customer behavior. 
In this project, I implemented a **K-Means Clustering** model to segment retail customers based on their purchasing habits.

#Dataset :-
The dataset is taken from **Kaggle’s Customer Segmentation Tutorial**:  
[Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

From the dataset, I used the following features:
✤ `Age`  
✤ `Annual Income (k$)`  
✤ `Spending Score (1-100)`  
✤ `Gender` (encoded to numeric)

#Tech Stack :- 
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn (for EDA + Visualizations)  
- Scikit-learn
- Opendatasets

#What I Did :-
✤ Cleaned and explored the data  
✤ Encoded categorical variables  
✤ Scaled numerical features using StandardScaler  
✤ Used the **Elbow Method** to choose optimal K  
✤ Trained a K-Means model with 5 clusters  
✤ Visualized the customer segments in a scatter plot  
✤ Saved the clustered output to a new `.csv` file


#Results :-
- Segmented customers into 5 distinct groups based on income and spending behavior  
- Uncovered valuable insights like high-income/low-spending vs. low-income/high-spending customers  
- Ideal for businesses wanting to **personalize marketing** and boost customer retention

#Future Work :-
- Add more features like occupation or family size (if available)  
- Try **Hierarchical Clustering** or **DBSCAN**  
- Deploy on a web app for interactive segmentation

#How to Run :-
1. Clone this repo  
2. Navigate to the project folder  
3. Open the notebook in **Google Colab** or **Jupyter Notebook**  
4. Install required libraries:  
pip install pandas numpy matplotlib seaborn scikit-learn opendatasets
5. Download the dataset manually or using opendatasets (remove any personal API keys before uploading)
