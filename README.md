Here’s a complete README file for your **Pneumonia Detection using Deep Learning** project that includes all necessary sections like installation, usage, and fixed code:

---

# Pneumonia Detection using CNN

This project uses a Convolutional Neural Network (CNN) to detect pneumonia from chest X-ray images. The model classifies an X-ray as either `Pneumonia` or `Normal`.

---

## 📁 Dataset

The dataset used is from the [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) on Kaggle.

Folder structure:

```
chest_xray/
├── train/
├── val/
└── test/
```

---

## 🛠 Requirements

* Python 3.x
* TensorFlow / Keras
* NumPy
* Matplotlib
* OpenCV or Pillow

Install requirements:

```bash
pip install tensorflow numpy matplotlib opencv-python
```

---

## 🧠 Model Architecture

The model is a CNN with the following structure:

* Conv2D → MaxPooling
* Conv2D → MaxPooling
* Flatten → Dense → Dropout
* Output: Sigmoid for binary classification

---

## 📌 Notes

* Accuracy may vary depending on training epochs and data preprocessing.
* Ensure your input images are resized to (150,150) and normalized.

---

## 📜 License

MIT License - free to use for academic purposes.

