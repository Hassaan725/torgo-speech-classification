# torgo-speech-classification
A machine learning project for detecting dysarthric speech using the TORGO dataset and audio features like MFCCs.
# 🗣️ Dysarthric Speech Classification using TORGO Dataset

This project uses **machine learning** techniques to classify speech audio samples from the **TORGO Dataset**. It focuses on detecting dysarthric (speech-impaired) vs. non-dysarthric speech using extracted audio features like **MFCCs**.

## 📁 Dataset

- **Name**: TORGO Speech Dataset
- **Use Case**: Dysarthria (speech disorder) detection
- **Format**: `.wav` audio files

> ⚠️ Dataset must be downloaded and placed locally (due to license restrictions). Modify `dataset_path` in the code to point to your local copy.

## 🔧 Libraries Used

- `librosa` – for audio processing and MFCC feature extraction  
- `scikit-learn` – for machine learning models and evaluation  
- `numpy` – for numerical operations  
- `resampy` – for audio resampling

## 🧠 Models Used

- Support Vector Machine (SVM)
- Random Forest Classifier

## 🎯 Features Extracted

- **MFCCs** (Mel Frequency Cepstral Coefficients)  
  Used to represent audio signals in a form suitable for ML models. The MFCCs are padded or truncated to a fixed size (e.g., 40 × 200).

## 🧪 How to Run

1. Clone the repository.
2. Make sure your dataset path is correctly set in the notebook:
   ```python
   dataset_path = 'path_to_your_TORGO_dataset'

