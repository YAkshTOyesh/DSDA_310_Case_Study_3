# Overview: Seizure Detection Using CNN
This case study focuses on developing and applying Convolutional Neural Networks (CNNs) for detecting seizures using EEG data in Bonn Dataset. It highlights the use of machine learning to automate seizure detection and provides insights into neurological disorders.

# Repository Contents
## 1. Report
   - Files
      - Case_Study_3_Report.pdf
      - Case_Study_3_Slides.pdf
  - Decription
      - Detailed report and presentation on the methodology, including data preprocessing, CNN architecture, and results. Insights into model accuracy and clinical applicability are discussed.

## 2. Code
  - Files
       - CS_3_Code.ipynb
  - Description
       - Jupyter Notebook implementing the CNN model, with steps for preprocessing, training, and evaluating EEG signal data.

## 3. Datasets
   - Files
       - Datasets Folder
   - Description
       - The study uses the Bonn EEG dataset, containing 500 full signals (400 seizures, 100 non-seizures) and 11,500 short signals (2,300 seizures, 9,200 non-seizures).

# Results
- ## Performance Metrics
  - Achieved 99% accuracy for short signals and 90% accuracy for full signals.
  - High accuracy in detecting seizure patterns validates CNN effectiveness for clean, structured data.
- ## Challenges
  - Full signal accuracy was lower due to limited data.
  - Future testing on noisy, real-world data is recommended.

# Recommendations
1. Fine-tune CNN parameters for better accuracy on full signals.
2. Test model on noisy datasets and real-world scenarios.
3. Develop user-friendly interfaces for medical professionals.

# Skills
Below is a list of skills we acquired during this project:
- Signal Processing
- Signal Data Exploration
- CNN Model Architecture (Including Pooling Layer, Convolution Layer and Activation Functions)
- Machine Learning Training Strategies (Epochs, Batch Size, Loss Function, Optimizer, Patience)
- Machine Learning Evaluation Techniques(Accuracy, Precision, Recall)
- Python
- TensorFlow
- Scikit Learn
