# 🖼️ Image Classification with CIFAR-10 Using Convolutional Neural Networks (CNN)

## 📝 **Project Overview**

This project focuses on building a **Convolutional Neural Network (CNN)** to classify images from the **CIFAR-10 dataset**, which consists of 60,000 color images across 10 different classes. The goal is to demonstrate how deep learning can be applied to image recognition tasks effectively.

---

## 🎯 **Objectives**

- Implement a **CNN architecture** from scratch using TensorFlow and Keras.
- Train the model on the CIFAR-10 dataset to classify images into 10 distinct categories.
- Apply **data preprocessing** techniques to normalize images and improve model performance.
- Visualize training progress through **loss and accuracy plots**.
- Evaluate model performance using **real-world test data**.

---

## 📂 **Dataset Description**

- **Source:** CIFAR-10 dataset (available via TensorFlow/Keras datasets).
- **Classes:** Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck.
- **Image Shape:** 32x32 pixels with 3 color channels (RGB).

---

## ⚙️ **Technologies Used**

- **Python Libraries:** NumPy, Matplotlib
- **Deep Learning Framework:** TensorFlow, Keras
- **Optimizer:** Stochastic Gradient Descent (SGD) with Exponential Decay
- **Environment:** Jupyter Notebook / Google Colab

---

## 🧠 **Model Architecture**

1. **Convolutional Layers:**
   - Multiple Conv2D layers with ReLU activation and MaxPooling for down-sampling.
   - Dropout layers added to prevent overfitting.

2. **Flattening:**
   - Flatten layer to convert the 2D matrices into a 1D vector.

3. **Fully Connected Layers:**
   - Dense layers with ReLU activation followed by Dropout layers.
   - Final Dense layer with Softmax activation for multi-class classification.

4. **Compilation:**
   - Loss Function: Categorical Cross-Entropy
   - Optimizer: SGD with learning rate scheduling
   - Metrics: Accuracy

---

## 🚀 **How to Run the Project**

1. **Clone the Repository:**
   ```bash
   git clone [GitHub Repository Link]
   ```
2. **Install Dependencies:**
   ```bash
   pip install tensorflow numpy matplotlib
   ```
3. **Run the Notebook:**
   ```bash
   jupyter notebook CIFAR10_CNN_Classification.ipynb
   ```
4. **Execute the Cells:**
   - Train the model.
   - Evaluate performance on the test set.
   - Visualize predictions and model metrics.

---

## 📈 **Key Results & Insights**

- Achieved **62.12% accuracy** on the CIFAR-10 test set.
- The model effectively classifies common objects like airplanes, cars, and animals.
- **Training vs Validation Loss** and **Accuracy plots** indicate model performance trends.

---

## 🔍 **Future Improvements**

- Implement **data augmentation** to improve generalization.
- Experiment with **deeper CNN architectures** like ResNet or VGG.
- Apply **learning rate schedulers** for optimized training.
- Fine-tune hyperparameters (batch size, epochs, dropout rates).

---

## 🙌 **Contributions**

Contributions are welcome! Fork the repository, create a pull request, or submit issues for improvements.

---

**Author:** Nikitha Kadaparthi  
**GitHub:** [GitHub Profile](https://github.com/Nikithakadaparthi)  
**LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/nikitha-kadaparthi-4a42321a8/)

> *"Empowering machines to see the world, one pixel at a time."*

