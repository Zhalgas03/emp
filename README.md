# Brain Tumor Classification using Optimized Deep Learning and Explainable AI

This project presents an optimized and interpretable deep learning framework for brain tumor classification from MRI images.

The work was developed as part of the Bachelor's thesis in Computer Science (Data Analysis curriculum) at the University of Messina.

The project investigates how modern convolutional neural networks, optimization strategies, attention mechanisms, and explainable AI techniques can improve classification performance in medical imaging.

---

## Research Goal

The goal of this research is to design a deep learning pipeline capable of accurately classifying brain tumor images while maintaining interpretability of the model decisions.

Medical AI systems must not only achieve high accuracy but also provide transparency for clinical environments.

---

## Key Contributions

• Implementation of an optimized CNN-based pipeline for brain tumor classification  
• Comparative evaluation of multiple architectures and optimization strategies  
• Integration of attention mechanisms to enhance feature representation  
• Exploration of explainable AI techniques for model interpretability  
• Experimental evaluation of multiple training improvements

---

## Models and Experiments

The project evaluates several deep learning configurations:

### Baseline Model
EfficientNetV2-S trained using the Adam optimizer.

### Optimized Model
Improved training pipeline including:

- AdamW optimizer
- tuned data augmentation
- improved preprocessing

### Attention Mechanisms

To enhance spatial feature extraction, the following modules were tested:

- **ECA (Efficient Channel Attention)**
- **GAM (Global Attention Mechanism)**
- **CBAM (Convolutional Block Attention Module)**

### Additional Optimization

Further experiments include:

- label smoothing
- improved preprocessing pipeline
- hyperparameter tuning

---

## Explainable AI

To improve model transparency, explainable AI techniques were applied to visualize model decisions and highlight image regions contributing to classification.

This step is important in medical applications where model interpretability is critical.

---

## Dataset

The models were trained and evaluated on a brain tumor MRI dataset containing labeled medical images.

Preprocessing steps include:

- image normalization
- resizing
- augmentation
- dataset balancing

---

## Evaluation Metrics

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC curves

---

## Technologies

Python  
TensorFlow / Keras  
NumPy  
Pandas  
OpenCV  
Scikit-learn  
Matplotlib  

---

## Repository Structure
