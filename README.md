
## 🧠 Convolutional Neural Network (CNN) for Fashion MNIST

In this phase, a **Convolutional Neural Network (CNN)** is implemented to classify images from the Fashion MNIST dataset into 10 categories. CNNs are more suitable for image data as they can automatically learn spatial features such as edges, textures, and shapes.

A complete training pipeline is used, including data loading, batch processing, model training, and evaluation.

---

### 📊 Results

The CNN model achieved:

* **Training Accuracy: ~98%**
* **Test Accuracy: ~92%**

This shows a significant improvement over the ANN model, highlighting the effectiveness of CNNs for image classification tasks.

---

### ⚠️ Overfitting Observation

The gap between training and test accuracy indicates that the model is still experiencing **overfitting**, meaning it learns the training data very well but does not generalize equally well to unseen data.

---

### 🚀 Future Improvements

To further improve generalization and push accuracy beyond current performance, the following techniques will be applied:

* **Data Augmentation**
  (e.g., random rotations, flips, scaling) to artificially increase dataset diversity

* **Hyperparameter Tuning**
  (learning rate, batch size, number of filters, kernel sizes, etc.)

* **Transfer Learning**
  using pre-trained models (e.g., ResNet, VGG) to leverage learned features and compare performance

---

### 📌 Summary

The transition from ANN (≈83–88%) to CNN (**~92% test accuracy**) demonstrates a clear improvement, but also highlights the importance of controlling overfitting for better real-world performance.
