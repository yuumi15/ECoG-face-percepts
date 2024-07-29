## How Face Precepts are Influenced by Noise
_This project was completed as part of the Neuromatch Academy's Computational Neuroscience course (Summer 2024)_

**Project Goal:**

This project aimed to analyze the Miller et al. ECoG dataset to understand the role of the Fusiform Face Area (FFA) in face recognition under noisy conditions. We compared different machine learning techniques to identify the most effective method for recognizing faces based on specific thresholds within the data.

![FFA Miller D](https://github.com/user-attachments/assets/cfe634dd-e153-4ec9-abc8-d111634f5c7b)


**Machine Learning Techniques Explored:**
* Logistic Regression 
* Recurrent Neural Networks(RNNs)
* Convolutional Neural Networks(CNNs)
* Linear Discriminant Analysis(LDA)
* Support Vector Regression(SVR)

**This repository contains the code for the Convolutional Neural Network (CNN) model.**

Due to teammate collaboration, the code for RNNs, LDA, and SVR is not included here. 


### Getting Started~
To run the Convolutional Neural Network (CNN) code, follow the following instructions:

**Environment Setup**
1. **Jupyter Notebook**:
   - The code is designed to be executed in a Jupyter Notebook environment using Python.

2. **Files Included**:
   - **NS_ECoG_faceshouses_Vis**: Contains visualizations for the dataset to help understand the data distribution and characteristics.
   - **CNN_Model_ECoG_faceshouses**: Contains the complete implementation of the CNN model, including data preprocessing, model architecture, training, and evaluation.

**Dependencies**

All necessary imports are included in the "Imports" cell at the beginning of each notebook. You will need to install the following libraries:
- **scikit-learn**: For machine learning utilities and data preprocessing.
- **PyTorch**: For building and training the neural network.
- **NumPy**: For numerical operations and data manipulation.
- **Matplotlib/Seaborn**: For data visualization.

**Further Information:**
* [Link to Neuromatch Academy Course](https://compneuro.neuromatch.io/tutorials/intro.html)
* ECoG dataset: K. J. Miller, “A library of human electrocorticographic data and analyses,” Nature Human Behaviour, vol. 3, no. 11, pp. 1225–1235, Aug. 2019, doi: https://doi.org/10.1038/s41562-019-0678-3
* Reference Paper: K. J. Miller, D. Hermes, F. Pestilli, G. S. Wig, and J. G. Ojemann, “Face percept formation in human ventral temporal cortex,” Journal of Neurophysiology, vol. 118, no. 5, pp. 2614–2627, Nov. 2017, doi: https://doi.org/10.1152/jn.00113.2017

**Team Members**
* Nada Salah
* Paula Rodriguez, MSc
* Noah Song 
* Omotayo Afolabi 
