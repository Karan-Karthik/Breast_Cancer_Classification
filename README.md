## README: Breast Cancer Classification Using Neural Networks

### **The Problem**
Breast cancer is one of the most common cancers worldwide, affecting millions annually. Early and accurate detection is critical for effective treatment. The main challenge lies in classifying tumors as **malignant** (cancerous) or **benign** (non-cancerous).

---

### **The Dataset**
The **Breast Cancer Wisconsin (Diagnostic) Dataset** contains 569 samples with 30 numeric features derived from digitized images of breast masses. These features include measurements such as radius, texture, perimeter, and smoothness. The target label indicates whether the tumor is malignant (M) or benign (B).

---

### **The Neural Network Model**
We trained a neural network for binary classification using two hidden layers. The architecture is:
- Input layer: 30 features.
- Hidden layers: 16 neurons and 8 neurons respectively, each with ReLU activation.
- Output layer: 1 neuron with a sigmoid activation function, mapping predictions to probabilities between 0 and 1.

The model minimizes **Binary Cross-Entropy Loss (BCE)**:
where:
- True label (0 for benign, 1 for malignant).
- Predicted probability from the sigmoid function.

This setup ensures the model learns to predict probabilities aligned with the true labels for accurate classification.

