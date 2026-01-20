# Intro to HPC: Solar Cell Project Workthrough

## 📌 Project Overview
This repository contains my completed workthrough of the project **"Solar Power for Affordable Housing through Computational Design of Low-Cost/High-Efficiency Solar Cells"**. 

The goal of this study is to analyze and predict the optical properties of dyes in the `DyeDB` database to assist in the design of low-cost, high-efficiency solar cells.

## 🧪 Technical Implementation
I followed the six-part instructional series to process chemical data and develop machine learning models:

* **Part 1: Data Cleaning & Canonization:** Used `RDKit` to clean SMILES strings and generate molecular fingerprints to "teach" the computer chemistry.
* **Part 2: Data Exploration:** Performed statistical analysis and visualization (distributions and scatter plots) of spectral properties like `lambda_sTDA`.
* **Part 3 & 4: Molecular Mapping:** Applied **t-SNE** and **PCA** clustering to visualize high-dimensional chemical space and distinguish between different molecular structures (e.g., rings vs. chains).
* **Part 5: Supervised Learning:** Implemented **Random Forest (RF)** and **Gaussian Process Regression (GPR)** using `Scikit-learn` to predict the first excitation energy of molecules.
* **Part 6: Advanced GPR with GPU:** Utilized `Tensorflow` and `GPflow` to accelerate regression models on GPU architectures, optimizing hyperparameters for better model fit.

## 🛠️ Tools Used
* **Cheminformatics:** RDKit
* **Machine Learning:** Scikit-learn, GPflow, Tensorflow
* **Data Science:** Pandas, NumPy, Matplotlib, Seaborn

## ⚖️ License & Attribution
This project is licensed under the **Mozilla Public License 2.0 (MPL 2.0)**.

* **Original Author:** Alvaro Vazquez Mayagoitia ([alvarovm.github.io](http://alvarovm.github.io)).
* **Original Copyright:** All rights reserved. Copyright Argonne National Laboratory UChicago LLC.
* **Workthrough Implementation:** Completed by Amelia Mikos as part of the Argonne National Laboratory Introduction to High Performance Computing Bootcamp curriculum.

For the original instructions and wiki documentation, please visit the [original repository](https://github.com/alvarovm/solarcelldata/wiki).

---
*Disclaimer: This repository is a personal workthrough for portfolio purposes. If you are currently enrolled in this course, please use this as a reference only after attempting the exercises yourself.*
