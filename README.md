# 🐶🐱 Dogs vs Cats Image Classification using CNN

This project implements a **Convolutional Neural Network (CNN)** for binary image classification (dogs vs cats) using **TensorFlow/Keras**.  
It trains on a dataset of dog and cat images and achieves good accuracy using data augmentation techniques.

---

## 📂 Project Structure
.
├── data/
│   ├── train/
│   │   ├── cats/
│   │   └── dogs/
│   ├── validation/
│       ├── cats/
│       └── dogs/
├── code.py
├── dogs_vs_cats_cnn.h5
└── README.md

---

## ⚙️ Requirements

- Python 3.7+
- TensorFlow / Keras
- NumPy
- Matplotlib (optional, for visualization)

Install dependencies:
1. Clone the repository:
2. Prepare dataset in the following structure:
3. Run the training script: python code.py
4. The trained model will be saved


---

## 📊 Model Architecture

- Conv2D + MaxPooling (32 filters)
- Conv2D + MaxPooling (64 filters)
- Conv2D + MaxPooling (128 filters)
- Flatten
- Dense (512, ReLU) + Dropout (0.5)
- Dense (1, Sigmoid)

---

## 🔮 Results

- Achieves ~85–90% validation accuracy (varies by dataset size & quality).
- Data augmentation is used to improve generalization.

---

## 📌 Future Improvements
- Use transfer learning (e.g., ResNet, VGG16, Inception).
- Add confusion matrix & accuracy plots.
- Deploy as a Flask/Django web app for real-time predictions.

---

## 🙌 Acknowledgments
Dataset inspiration: Kaggle Dogs vs Cats Dataset  
Built with: TensorFlow
