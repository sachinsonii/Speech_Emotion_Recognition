# Speech Emotion Recognition using Deep Learning

This project implements a Speech Emotion Recognition (SER) model using deep learning techniques to classify emotions from speech audio data.

## Features

- **Deep Learning Model**: Utilizes neural networks to classify speech emotions.
- **Audio Preprocessing**: Extracts relevant features from speech signals.
- **Jupyter Notebook Implementation**: Interactive workflow for experimentation.
- **Visualization**: Displays emotion classification results.

## Installation

### Prerequisites

Ensure you have the required dependencies installed:

```sh
pip install numpy pandas librosa matplotlib tensorflow keras scikit-learn
```

### Clone the Repository

```sh
git clone https://github.com/sachinsonii/Speech_Emotion_Recognition.git
cd Speech_Emotion_Recognition
```

## Running the Notebook

Since this project is implemented in a Jupyter Notebook, follow these steps:

1. Install Jupyter Notebook if not already installed:
   ```sh
   pip install notebook
   ```
2. Open the notebook:
   ```sh
   jupyter notebook Speech_Emotion_Recognition.ipynb
   ```
3. Run all the cells in order to train the model and make predictions.

## Model Overview

- **Input**: Audio recordings.
- **Processing**: Extracts Mel-frequency cepstral coefficients (MFCCs) and feeds them into a deep learning model.
- **Output**: Predicted emotion labels.

## Visualization

The notebook provides various plots to analyze feature extraction and classification results.

## Future Improvements

- Improve accuracy with larger datasets.
- Implement real-time emotion detection from live audio input.
- Optimize the model for deployment as an API.

## License

This project is licensed under the MIT License.

