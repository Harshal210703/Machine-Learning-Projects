# Handwritten Digit Recognition using Support Vector Machines (SVM)

## Overview:
This project aims to recognize handwritten digits using Support Vector Machines (SVM), a powerful classification algorithm. The dataset consists of gray-scale images of hand-drawn digits ranging from zero through nine.

## Methodology:
1. **Data Preparation:**
   - The dataset is loaded from CSV files (`train.csv` and `test.csv`).
   - Features are extracted from the images by dropping the label column.
   - Spatial moments of the image data are calculated to provide information about the distribution of pixel intensities.

2. **Image Preprocessing:**
   - Deskewing: Images are corrected for skewness using affine transformation.
   - Scaling: The deskewed images are scaled between 0 and 1 for improved performance.

3. **Model Building:**
   - Linear SVM: A basic linear SVM model is trained and evaluated.
   - PCA Decomposition: Principal Component Analysis (PCA) is applied to reduce dimensionality.
   - RBF Kernel SVM: SVM with 'rbf' kernels is explored for enhanced accuracy.

4. **Evaluation:**
   - Accuracy Measurement: The accuracy of SVM models is measured using appropriate metrics.
   - Hyperparameter Tuning: Grid search is performed for fine-tuning hyperparameters.

## Useful Links:
- [Navigate to the Dataset](https://www.kaggle.com/c/digit-recognizer/data)
- [View My Jupyter Notebook File](https://github.com/Harshal210703/Machine-Learning-Projects/blob/main/Handwriting%20Text%20Recognition/Support%20Vector%20Machines/Digit%20Recognition%20Using%20SVM.ipynb)
- [Related Article (by Harshal Sharma)](https://medium.com/@harshal210703/exploring-fundamentals-in-handwriting-text-recognition-2-a8de22123389)
