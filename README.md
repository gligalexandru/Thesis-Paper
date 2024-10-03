# Bachelor's Thesis – Data Science and AI  
**Maastricht University**

## Overview

This repository contains my Bachelor's thesis titled *"From Traditional to Cutting-Edge: An Analysis of Advanced Recommender System Architectures for Boels Rental."* The thesis investigates various recommender system architectures to enhance item recommendations for active rental contracts at Boels Rental, one of Europe's leading equipment rental companies. The research explores both traditional and advanced models, ranging from KNN to cutting-edge architectures like LightFM, LightGCN, GRU4Rec, and SASRec.

## Abstract

In this thesis, I evaluate multiple recommender system architectures aimed at improving item recommendations for newly created rental contracts. The baseline model is a Contract-based KNN algorithm, with advanced architectures such as LightFM (Matrix Factorization), LightGCN (Graph Neural Networks), GRU4Rec (Recurrent Neural Networks), and SASRec (Transformers) being explored. GRU4Rec showed the best performance, excelling in capturing sequential patterns, while LightFM demonstrated robust results, especially with larger datasets. This work provides insights into the deployment potential of these models for personalized recommendations at Boels Rental.

## Repository Structure

- `Thesis_Paper.pdf`: The full thesis document including methodology, experiments, and results.
- `Figures/`: Visualizations and figures used in the thesis.
- `References/`: References to all sources cited in the thesis.

## Technologies and Tools

The thesis involved the use of the following tools and frameworks:
- **Programming Languages**: Python, SQL
- **Libraries**: Pandas, NumPy, Scikit-learn, TensorFlow, PyTorch Geometric
- **Machine Learning Models**: LightFM, LightGCN, GRU4Rec, SASRec
- **Evaluation Metrics**: MAP@5, Recall@5, Hit@5

## Results

Key findings include:
- **GRU4Rec**: Best overall performance, particularly in capturing sequential dependencies.
- **LightFM**: Strong performance with large datasets and metadata-rich environments.
- **KNN-Based Models**: Effective for explainability but limited scalability and performance.
- **LightGCN and SASRec**: Underperformed on the given dataset but offer future potential with further tuning and preprocessing.

## Acknowledgments

This research was conducted in collaboration with Boels Rental and Maastricht University as part of the KE@Work honors program. Special thanks to my supervisors and the data science team at Boels for their support and guidance.
