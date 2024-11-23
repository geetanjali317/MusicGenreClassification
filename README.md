# MusicGenreClassification

This project predicts the genre of music based on audio features extracted from audio files. The system analyzes audio signals and spectrograms using machine learning techniques to classify music into different genres.
📋 Table of Contents

    Load Dataset from Kaggle
    Importing Libraries
    Visualizing the Audio
    The Audio Signal is for 30 Seconds
    Play Sound
    Doing Visualization on Chunks of Audio
    Melspectrogram Visualization
    Data Preprocessing
    Train Test Split
    Building the Model
    Model Evaluation
    Loss and Accuracy Visualization

🎵 Load Dataset from Kaggle

The dataset used is the GTZAN Music Genre Dataset from Kaggle. It contains audio files representing 10 genres, each with 100 files of 30 seconds duration.
📚 Importing Libraries

Key libraries used in the project include:

    Librosa for audio analysis and feature extraction
    Matplotlib and Seaborn for data visualization
    TensorFlow/Keras for building and training the deep learning model

🎶 Visualizing the Audio

The waveform of each audio file is visualized to understand the amplitude and structure of the signal over time.
⏱️ The Audio Signal is for 30 Seconds

Each audio file has a duration of 30 seconds, sampled at a standard rate of 22,050 Hz.
▶️ Play Sound

The audio files are played directly for quick verification of their content and genre.
🧩 Doing Visualization on Chunks of Audio

Audio signals are divided into smaller chunks for analysis to focus on specific patterns and variations.
🌈 Melspectrogram Visualization

The Melspectrogram, which represents the frequency content of the audio, is generated and visualized. This provides insights into the harmonic structure and temporal behavior of the audio.
🧹 Data Preprocessing

Audio features such as MFCC (Mel-frequency cepstral coefficients) and chroma are extracted. The features are normalized for better performance during model training.
🔀 Train Test Split

The dataset is split into training, validation, and testing subsets to evaluate the model's generalization performance.
🏗️ Building the Model

A Convolutional Neural Network (CNN) architecture is used for genre classification. The model is trained to learn patterns in the Melspectrograms and other extracted features.
📊 Model Evaluation

The model’s performance is assessed using metrics such as accuracy, precision, recall, and F1-score.
📈 Loss and Accuracy Visualization

The training and validation loss and accuracy trends over epochs are plotted to evaluate the model's performance and identify overfitting or underfitting.
