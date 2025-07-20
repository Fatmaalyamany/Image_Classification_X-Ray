# Medical Image Classification for Chest X-Ray Analysis

## Overview
This project focuses on classifying chest X-ray images into four categories: COVID-19, Normal, Viral Pneumonia, and Bacterial Pneumonia. It leverages deep learning with **transfer learning using the ResNet50 architecture** to efficiently build a robust medical image classifier.

## Key Features
* **Transfer Learning**: Utilizes pre-trained ResNet50 for feature extraction.
* **Data Augmentation**: Enhances model generalization through various image transformations.
* **Early Stopping & Checkpointing**: Optimizes training and saves the best performing model weights.
* **Comprehensive Evaluation**: Assesses model performance with accuracy, confusion matrices, and detailed classification reports.
* **Visualizations**: Includes plots for training progress and prediction examples.

## How to Run
1.  **Dataset Setup**: Organize your chest X-ray images into `train` and `test` directories, each containing subfolders for `COVID-19`, `Normal`, `Viral Pneumonia`, and `Bacterial Pneumonia` classes.
2.  **Install Dependencies**:
    ```bash
    pip install tensorflow opencv-python numpy pandas matplotlib seaborn scikit-learn
    ```
3.  **Update Data Path**: Modify the `base_path` variable in the `setup_data_directories()` function within the notebook to point to your dataset's root directory.
4.  **Execute Notebook**: Open the `Medical Image Classification for Chest X-Ray Analysis.ipynb` file in Jupyter Notebook/Lab or Google Colab and run all cells.

## Dependencies
* `tensorflow`
* `opencv-python`
* `numpy`
* `pandas`
* `matplotlib`
* `seaborn`
* `scikit-learn`
