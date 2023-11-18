# Self-Supervised Lung Cancer Classification

## Overview

This project aims to classify lung cancer cases into three categories: Bengin, Malignant, and Normal. It employs a combination of SimCLR (contrastive learning) and a classification model built on ResNet50. The IQ-OTHNCCD lung cancer dataset is used for training and evaluation.

## Project Structure

- **Data Exploration and Preprocessing:** Explore and preprocess the dataset, including analyzing image sizes and applying transformations.

- **Data Augmentation:** Visualize augmented images for each class to enhance model generalization.

- **Data Balancing:** Implement SMOTE (Synthetic Minority Over-sampling Technique) to balance class distribution.

- **SimCLR Pretraining:** Pretrain a SimCLR model using contrastive loss on the lung cancer dataset.

- **Classification Model:** Build a classification model by adding a classification head on top of the SimCLR base.

- **Training:** Train the classification model using an ImageDataGenerator and evaluate its performance.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Imageio
- Plotly
- Scikit-learn
- Imbalanced-learn


## Installation

**Clone the Repository:**
   ```bash
   git clone https://github.com/Mourya-wizard/Self-Supervised-Lung-Cancer-Classification.git
   cd Self-Supervised-Lung-Cancer-Classification
```
To run this project, you need to install the required dependencies. You can use the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. **Dataset:**
   - Download the IQ-OTHNCCD lung cancer dataset from [Kaggle](https://www.kaggle.com/datasets/adityamahimkar/iqothnccd-lung-cancer-dataset).
   - Organize the dataset into three categories: 'Bengin cases,' 'Malignant cases,' and 'Normal cases.'

2. **Run the Code:**
   - Execute the provided Jupyter notebook or Python script in a compatible environment.

3. **Adjust Parameters:**
   - Modify hyperparameters, model architecture, or other settings as needed for your specific use case.

4. **Prediction:**
   - Use the trained model to make predictions on new lung cancer images by providing the file path in the prediction section of the code.

## Results

- SimCLR Pretraining: Evaluate the performance of the SimCLR model on the lung cancer dataset.

- Classification Model: Assess the accuracy, recall, precision, and other metrics of the final classification model.

## Acknowledgments

- Credits to the dataset provider: [Link to Dataset](https://www.kaggle.com/datasets/adityamahimkar/iqothnccd-lung-cancer-dataset)

Feel free to reach out for any questions or contributions!
