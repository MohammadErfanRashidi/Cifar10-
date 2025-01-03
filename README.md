
# CIFAR-10 Colab Notebook

This repository contains a Jupyter Notebook for processing and training models on the CIFAR-10 dataset.

## Steps Covered in the Notebook

1. **Installing Required Libraries**: Installation of Kaggle API and other required libraries.
2. **Downloading the Dataset**: Using the Kaggle API to download the CIFAR-10 dataset.
3. **Extracting the Dataset**: Unzipping and preparing data for further processing.
4. **Exploring the Data**: Displaying and analyzing the dataset using filenames and labels.
5. **Data Preprocessing**:
    - Mapping labels to numeric values.
    - Converting images to NumPy arrays.
    - Splitting the dataset into training and testing sets.
    - Normalizing pixel values to [0, 1].
6. **Building Models**:
    - A basic neural network for classification.
    - A more advanced ResNet50-based transfer learning model.
7. **Training and Evaluating Models**:
    - Training models on the training set.
    - Evaluating performance on the test set.
8. **Visualization**: Plotting training and validation loss and accuracy.

## Requirements

- Python 3.x
- TensorFlow
- Kaggle API
- Py7zr
- OpenCV
- Other standard Python libraries (NumPy, Pandas, Matplotlib, etc.)

## Instructions

1. Ensure you have a Kaggle API key (`kaggle.json`) ready.
2. Run the cells step-by-step in the provided notebook.
3. Follow the comments for detailed explanations of each step.

## Notes

- The CIFAR-10 dataset is used for multi-class classification, consisting of 10 classes (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck).
- Transfer learning with ResNet50 improves model accuracy significantly.

Feel free to modify and experiment with the models to enhance performance or adapt to similar datasets.
