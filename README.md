# 🎵 Harmony Hub: AI-Powered Instrument Classification & Feedback

## 📌 Overview
Harmony Hub is an AI-powered music learning system that provides **instrument classification** and **real-time feedback** to enhance self-learning. Using **CNN-LSTM models**, the system analyzes audio input and classifies instruments like the **violin, piano, and flute**, offering performance insights.

## 🎯 Objectives
- **Develop an AI-based system** for instrument classification and real-time feedback.
- **Utilize deep learning models** to improve classification accuracy.
- **Enhance self-learning** by providing personalized insights into audio performance.

## 📊 Dataset
- **Source**: IRMAS Dataset for instrument recognition in musical audio signals.
- **Structure**: Training and testing folders with categorized samples.
- **Input**: Raw audio files processed for feature extraction.

## 🛠️ Methodology
1. **Feature Extraction**
   - **Mel Frequency Cepstral Coefficients (MFCCs)**
   - Spectral centroid, zero-crossing rate, and additional audio features.

2. **Modeling**
   - **CNN-LSTM Hybrid**: Combines convolutional feature extraction with temporal sequence modeling.
   - **Training**: 50 epochs for optimal accuracy.

3. **Feedback Generation**
   - Computes accuracy scores and provides classification insights.

## 📈 Results
- **MFCC Analysis**: Box plots, scatter plots, and violin plots highlight distinct spectral characteristics of instruments.
- **Feature Correlation Matrix**: Identifies redundant features and potential for dimensionality reduction.
- **Model Accuracy**:
  - **CNN Model**: Moderate accuracy but shows overfitting.
  - **LSTM Model**: Achieved **65.42% accuracy**, indicating room for improvement.

## Dataset
https://zenodo.org/records/1290750#.WzCwSRyxXMU

