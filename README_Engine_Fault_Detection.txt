
# 🔧 Engine Fault Detection Using Sound and Machine Learning

This project uses acoustic signals (engine sounds) to detect faults in engine systems using machine learning.

---

## 📌 Project Overview

Engines make distinct sounds when operating normally or when a fault is present (e.g., knocking, belt slipping, valve issues). This project aims to classify these faults automatically by analyzing sound features such as MFCCs (Mel-Frequency Cepstral Coefficients) and training a Convolutional Neural Network (CNN).

---

## 🧠 Key Features

- Preprocessing of engine audio using `librosa`
- MFCC feature extraction
- CNN-based classification model
- Supports multiple fault classes (e.g., Normal, Knocking, Valve Faults)
- Easily extendable with more audio samples

---

## 🛠 Technologies Used

- Python
- Librosa (audio processing)
- TensorFlow/Keras (machine learning)
- Scikit-learn (label encoding, train/test split)
- Google Colab / Jupyter Notebook

---

## 📁 Folder Structure

```
/engine_sounds/
    ├── normal/
    ├── knocking/
    ├── valve/
    └── belt/
```

Each folder should contain `.wav` files representing that category.

---

## 🚀 How to Use

1. Upload your dataset to `/content/engine_sounds/` in Colab.
2. Run each code cell to train and test the model.
3. Use the `predict()` function with your test `.wav` file to detect engine faults.

---

## 📈 Future Improvements

- Add more classes (e.g., turbo issues, exhaust problems)
- Real-time detection from microphone input
- Integration with a mobile or web interface

---

## 📄 License

For academic and non-commercial use only.
