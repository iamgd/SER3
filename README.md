﻿***To run the speech emotion recognition project, you'll need the following requirements:***

**Python:**

Ensure you have Python installed on your system. You can download and install Python from the official Python website https://www.python.org/downloads/

**Libraries:**

- pandas: For data manipulation and handling Excel files.
- scikit-learn: For machine learning algorithms and evaluation metrics.
- NumPy: For numerical operations.
- librosa: For audio feature extraction.
- pydub: For audio processing and manipulation.
- SciPy: For signal processing and filtering.
- Keras with TensorFlow backend: For building and training deep learning models.

**You can install these libraries using pip:**

pip install pandas scikit-learn numpy librosa pydub scipy keras tensorflow


***Steps for running this project:***

- actor 1's 138 audio files are loaded in the dataset folder

- then 1_noise_reduction is performed to remove the noise from the audio files and cleaned audio files are stored in the output folder

- 2_feature_extraction is performed and the features from the audio files are saved as output_data.xlsx

- 3_feature_scaling is done and the output is saved to scaled_output_data.xlsx

- 4_split_data is done and the output is saved as 2sheets one for training and other for testing as train_test_data.xlsx

- 5_audio_classification_svm - in this the audio classification is done using SVM classifier and the output is saved as classify_report_svm.xlsx

- 5_audio_classification_lstm - in this the audio classification is done using LSTM classifier and the output is saved as classify_report_lstm.xlsx

- 5_audio_classification_cnn - in this the audio classification is done using CNN classifier and the output is saved as classify_report_cnn.xlsx  