📘 Numerical Linear Algebra for Data Science & Machine Learning

A collection of projects applying numerical linear algebra techniques to real-world data science and machine learning problems.

🔍 Overview

This repository contains four applied projects demonstrating how numerical linear algebra supports modern data science, machine learning, and data mining tasks.
Each project implements core linear algebra algorithms from scratch and applies them to real datasets such as EMNIST, MNIST, and 20 Newsgroups.

Techniques explored include:

Eigenvalue problems

Power iteration

QR decomposition (Householder & incremental Givens)

Nonnegative Matrix Factorization (NMF)

Principal Component Analysis (PCA)

t-SNE

Clustering metrics (ARI, AMI, Silhouette)

Sparse matrix operations

Graph algorithms (PageRank)

📌 Project 1 — PageRank via Eigenvectors & Power Iteration

Description
Implemented the PageRank algorithm on a real web-graph dataset using two core numerical methods:

Eigenvector-based PageRank using the dominant eigenvector of the transition matrix

Power iteration method with teleportation/damping

Proper handling of dangling nodes and column normalization

Benchmarking against NetworkX’s built-in PageRank function

Skills demonstrated

Sparse matrix operations

Markov chains and stationary distributions

Floating-point stability & convergence analysis

Large-scale graph processing

Technologies: Python, NumPy, SciPy, NetworkX

📌 Project 2 — EMNIST Handwritten Character Classification using QR Decomposition

Description
Built a full machine learning pipeline for EMNIST letter classification using QR decomposition techniques, implemented from scratch:

Householder QR

Incremental Givens QR for adding samples batch-by-batch

Linear classifier training using least squares

Use of 28×28 raw EMNIST images without dimensionality reduction

Preprocessing, training/testing split, and model evaluation

Skills demonstrated

Numerical stability of QR factorizations

Incremental matrix updates using Givens rotations

Linear regression for classification

Working with large image datasets

Technologies: NumPy, Python, Scipy, Matplotlib

📌 Project 3 — Clustering 20 Newsgroups with NMF + KMeans

Description
Performed topic-based clustering of the 20 Newsgroups dataset using:

TF-IDF vectorization

Nonnegative Matrix Factorization (NMF)

KMeans clustering on the NMF embeddings

Model performance was evaluated using:

Adjusted Rand Index (ARI)

Adjusted Mutual Information (AMI)

Silhouette score

Skills demonstrated

Dimensionality reduction via NMF

Text preprocessing & vectorization

Cluster evaluation and interpretation

Understanding trade-offs in unsupervised learning

Technologies: scikit-learn, NMF, KMeans, Python, NumPy

📌 Project 4 — PCA and t-SNE Analysis on MNIST

Description
Developed a compact but complete dimensionality-reduction pipeline for MNIST digit images using:

Principal Component Analysis (PCA)

t-Distributed Stochastic Neighbor Embedding (t-SNE)

The pipeline includes:

Preprocessing and scaling

2D embeddings for visualization

Trustworthiness and KL divergence evaluation

Comparison between PCA and t-SNE behavior

Skills demonstrated

High-dimensional data visualization

Linear vs nonlinear dimensionality reduction

Quantitative evaluation of embeddings

Interpretation of manifold structure

Technologies: scikit-learn, NumPy, Matplotlib
