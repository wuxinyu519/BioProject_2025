# 🧬 BioProject_2025
This is the final project for the Bioinformatics course.

## 📘 Introduction
This project focuses on **protein sequence classification** using various machine learning and deep learning models. All code is implemented and executed in **👉 [Google Colab](https://colab.research.google.com/drive/1LfYuIfqacJCP3vSzIJqMgwsapfnAisyM#scrollTo=-AB8avkNk3ua)
**, leveraging GPU acceleration when available.

We build a comparative framework to evaluate different classification models on a balanced UniProt dataset across five protein categories.

## 📂 Project Structure
- `notebooks/` – Jupyter/Colab notebooks for training and evaluation
- `data/` – (optional) Example links or scripts to prepare datasets
- `models/` – Saved model checkpoints and architectures
- `results/` – Plots and evaluation metrics
- `README.md` – Project overview

## 🧪 Methodology
We compare the following models:
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Recurrent Neural Network (RNN/LSTM)**
- **Transformer-based pretrained model (ESM-2)**

### Feature Representations:
- Amino acid frequency vectors
- Embedding-based representations (e.g., ESM-2 embeddings)

## 📊 Evaluation Metrics
- Classification Accuracy
- Confusion Metric
- t-SNE Visualization

## 📈 Results Summary
- Pretrained models (ESM-2) perform best overall
- Traditional models remain competitive for small datasets or limited resources

## 🔗 Dataset
Dataset are available at:  
👉 [Google Drive](https://drive.google.com/drive/u/0/folders/1F-uUIM2a99NvgmziA_ccYQL034U7-Y9Q)

## 🚀 How to Run
1. Download .ipynb and then open it on Notebook
2. Download five fasta.gz files provided above (Use the [link]([https://github.com/your-username/BioProject_2025](https://drive.google.com/drive/u/0/folders/1F-uUIM2a99NvgmziA_ccYQL034U7-Y9Q)))
3. Run all cells for training and evaluation

## 👩‍🔬 Contributors
- Xinyu Wu (Xinyu_Wu1@baylor.edu)

## 📜 License
This project is for academic purposes. No license is provided by default.
