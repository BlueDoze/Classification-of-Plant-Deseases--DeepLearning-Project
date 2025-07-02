# Comparative Analysis of Deep Learning Models for Plant Disease Classification

## Dataset

This project uses a subset of the [PlantVillage dataset (Color version)](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset?select=color) available on Kaggle. From the full dataset, we randomly selected 5 classes from the `color/` directory to create a manageable and balanced subset for experimentation.

The selected classes are:
- `Apple__Black_rot`
- `Grape__Black_rot`
- `Potato__Late_blight`
- `Strawberry__Leaf_scorch`
- `Tomato__Bacterial_spot`

The code will be trained with 500 images of each class, resulting in a perfectly balanced dataset with 2,500 images in total.

---

##  Project Objective

The main objectives of this project are:

1. To **train deep learning models** capable of accurately **identifying plant diseases** from leaf images.
2. To **compare the performance** of various convolutional neural network (CNN) architectures using transfer learning.
3. To understand the strengths and weaknesses of each model through visualizations, classification metrics, and error analysis.

This contributes toward the development of **automated plant disease diagnosis systems**, which can assist farmers and agronomists in real-world scenarios.

---
