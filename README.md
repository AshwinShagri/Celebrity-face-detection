# Celebrity Detection Using Custom Inception V3 Model

## Overview

This project implements a **Convolutional Neural Network (CNN)** for celebrity face detection using a custom **Inception V3** architecture. The model is trained on a dataset of celebrity images, achieving an impressive accuracy of **90.14%** after **500 epochs** of training.

## Key Features

- **Custom Inception V3 Architecture**: Built to effectively recognize and classify celebrity faces.
- **Data Preprocessing**: Consistent resizing and normalization of a dataset containing **500 images** to prepare for model training.
- **Optimizer Comparisons**: Experimented with various optimizers to identify the most effective configurations for enhancing model performance.
- **Explainable AI (XAI)**: Incorporated multiple XAI methods to enhance the interpretability of model predictions, including:
  - **LIME** (Local Interpretable Model-agnostic Explanations)
  - **Smooth Grad**
  - **Occlusion Sensitivity**
  - **Saliency Maps**


## Usage
The entire code is implemented in a single Python file. Run the file to train the model and evaluate its performance on the dataset.
Results
The model demonstrates high accuracy and provides transparent explanations for its predictions through the implemented XAI methods.

## Conclusion
In conclusion, our project successfully developed a Convolutional Neural Network using a custom Inception V3 architecture, which achieved an impressive accuracy of 90.14% after 500 epochs of training. We effectively preprocessed a dataset of 500 images by resizing and normalizing them, ensuring consistency for model training. By experimenting with various optimizers, we identified the most effective configurations for enhancing model performance. We incorporated Explainable AI methods, such as LIME, Occlusion Sensitivity, Smooth Grad, and Saliency Maps, to provide transparency and interpretability of the model’s predictions. This approach not only improved our understanding of the model's decision-making process but also demonstrated practical application by accurately classifying new images.

## Acknowledgments
Special thanks to the developers of the libraries and frameworks used in this project.
Inception V3 Model Documentation for insights into the model architecture.
