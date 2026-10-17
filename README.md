# \# Cross-Domain Sentiment Analysis System 📊

# 

# !\[Python](https://img.shields.io/badge/Python-3.9+-blue.svg)

# !\[Framework](https://img.shields.io/badge/Framework-PyTorch%20%7C%20TensorFlow-orange.svg)

# !\[Module](https://img.shields.io/badge/Module-7PAM2033%20Data%20Science-success.svg)

# 

# \## Project Overview

# This repository contains the codebase and documentation for a production-level machine learning pipeline evaluating \*\*Cross-Domain Sentiment Analysis\*\*. Developed under the CDIO (Concept, Design, Implement, Operate) engineering framework, this project investigates the performance degradation and adaptability of sentiment models when trained on a source domain (e.g., e-commerce) and deployed on an unseen target domain (e.g., film or restaurant reviews).

# 

# \## The Datasets

# The models are trained and evaluated on 3,000 labeled sentences extracted from three distinct domains:

# \*   \*\*Amazon (Electronics/Products)\*\*

# \*   \*\*IMDb (Movies/Entertainment)\*\*

# \*   \*\*Yelp (Restaurants/Hospitality)\*\*

# 

# \*Data Source: Kotzias et al., KDD 2015. "From Group to Individual Labels using Deep Features."\*

# 

# \## Model Architecture

# To satisfy the project specifications, this system compares three distinct architectures:

# 1\.  \*\*Baseline Neural Network:\*\* A standard feedforward/LSTM network trained on TF-IDF or Word2Vec embeddings.

# 2\.  \*\*Pre-trained Transformer (Transfer Learning):\*\* A Hugging Face Small Language Model (e.g., RoBERTa/DistilBERT) fine-tuned on the source domain.

# 3\.  \*\*Custom Hybrid Model:\*\* An architecture combining deep semantic transformer embeddings with statistical linguistic features (e.g., VADER polarity scores).

# 

# \## Repository Structure

# \*   `app/` - Streamlit web application for real-time inference

# \*   `data/raw/` - Raw datasets (Ignored in version control)

# \*   `docs/` - Weekly CDIO project plans and governance documents

# \*   `notebooks/` - Exploratory Data Analysis (EDA) and prototyping

# \*   `src/` - Core pipeline scripts (preprocessing, training, evaluation)

# \*   `tests/` - Unit tests and User Acceptance Testing (UAT) scripts

# 

# \## Team Roles \& Governance

# \*   \*\*Team Leader:\*\* Atif Ahmed

# \*   \*\*GitHub Document Manager:\*\* Manik Goud Kata

# \*   \*\*Scrum Master:\*\* Mahesh Nanduri 

# \*   \*\*Communications Leader:\*\* Yeturi Dinesh babu 

# \*   \*\*Test Plan Manager:\*\* Tirumani Bhavana 

# \*   \*\*Code Review Manager:\*\* Murali Mukesh Reddy Daka

# 

# \---

# \*Developed for the Data Science Professional Team Project\*

