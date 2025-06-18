Digit Clustering using Unsupervised Machine Learning

This project demonstrates digit clustering using unsupervised learning techniques, primarily K-Means clustering, on the MNIST handwritten digits dataset. The goal is to group similar digit images together without using the labels (unsupervised approach).

digit-clustering/
├── data/                  # Contains MNIST dataset (if stored locally)
├── notebooks/             # Jupyter notebooks for exploratory work
├── src/                   # Source code: data loaders, clustering models
│   ├── preprocess.py
│   ├── cluster.py
│   └── visualize.py
├── results/               # Visualizations, confusion matrix, etc.
├── app/                   # Optional: Gradio or Streamlit app
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
└── main.py                # Main script to run clustering

 Features

✅ Load and preprocess MNIST data

✅ Dimensionality reduction using PCA or t-SNE

✅ Clustering using K-Means (optionally DBSCAN, Gaussian Mixture)

✅ Visualization of clusters

✅ Evaluation using cluster-label mapping and accuracy

✅ Interactive web app (Gradio/Streamlit)

🧰 Technologies Used

Python 3.x

Scikit-learn

NumPy, Pandas

Matplotlib, Seaborn

TensorFlow/Keras (for MNIST loader)

Gradio or Streamlit (for UI)
