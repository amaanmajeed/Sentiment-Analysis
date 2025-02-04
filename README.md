# Sentiment Analysis using Audio Recordings

## Project Overview

This project aims to develop and compare the performance of various machine learning models for sentiment analysis using audio recordings. The goal is to investigate the effectiveness of different algorithms, such as Logistic Regression, K-Nearest Neighbors (KNN), Naive Bayes, and Support Vector Machines (SVM), in classifying the emotional sentiment expressed in audio data.

## Dataset

The dataset used in this project consists of audio recordings labeled with sentiment categories, including Disgust, Fear, Happiness, Neutral, and Sadness. The audio files are in the WAV format and are located in the Google Drive folder '/content/drive/MyDrive/Colab Notebooks/data/SentimentAnalysisDataset/NoiseAudioWAV/'.

## Methodology

The project follows these key steps:

1. **Data Preparation**:
   - Load the audio files from the dataset
   - Preprocess the audio data, such as resampling, normalization, and splitting into training and testing sets

2. **Feature Extraction**:
   - Extract relevant audio features using libraries like librosa, such as spectrograms, Mel-Frequency Cepstral Coefficients (MFCCs), and other time-domain and frequency-domain features

3. **Model Implementation and Evaluation**:
   - Implement the following machine learning models for sentiment analysis:
     - Logistic Regression
     - K-Nearest Neighbors (KNN)
     - Naive Bayes
     - Support Vector Machines (SVM)
   - Train and evaluate the performance of each model using appropriate metrics, such as accuracy, precision, recall, and F1-score

4. **Model Comparison and Analysis**:
   - Compare the performance of the different machine learning models
   - Analyze the strengths and weaknesses of each model, and discuss the factors that may have influenced their performance
   - Provide insights and recommendations for selecting the most suitable model for the given sentiment analysis task

## Notebooks

The project is implemented in the following Jupyter notebooks:

1. `1. ML_Project_Audio.ipynb`: This notebook focuses on the audio data preprocessing and feature extraction steps.
2. `2. Project_Logistic_Regression,_KNN,_NB,_SVM.ipynb`: This notebook contains the implementation and evaluation of the machine learning models for sentiment analysis.

## Dependencies

The project requires the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `librosa`
- `IPython.display`

You can install the required dependencies using pip:

```
pip install pandas numpy matplotlib seaborn librosa ipython
```

## Usage

1. Clone the repository or download the Jupyter notebooks.
2. Mount the Google Drive containing the dataset.
3. Run the notebooks in the following order:
   - `1. ML_Project_Audio.ipynb`
   - `2. Project_Logistic_Regression,_KNN,_NB,_SVM.ipynb`
4. Explore the results, analyze the model performance, and draw conclusions about the effectiveness of the different machine learning algorithms for sentiment analysis using audio recordings.

## Contributions

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please feel free to create a new issue or submit a pull request.

## Conclusion

This project provides a comprehensive exploration of using various machine learning techniques for sentiment analysis based on audio recordings. By implementing and comparing the performance of Logistic Regression, KNN, Naive Bayes, and SVM models, the project aims to offer insights into the strengths and limitations of each approach, ultimately helping to guide the selection of the most suitable model for audio-based sentiment analysis tasks.
