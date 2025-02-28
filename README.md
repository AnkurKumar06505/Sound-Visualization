# Sound-Visualization

This project involves speech or sound recognition by extracting features from audio data and training a Long Short-Term Memory (LSTM) model for classification.

### Key Steps:
#### Data Collection & Preprocessing:
Audio files are loaded from a directory.
Labels are extracted based on filenames.
A DataFrame is created to store file paths and their respective labels.

#### Exploratory Data Analysis (EDA):
Basic analysis and visualization of the dataset.
Audio waveform representations using librosa.

#### Feature Extraction:
Audio features such as Mel-frequency cepstral coefficients (MFCCs) or spectrograms are extracted for model input.
Model Development:

An LSTM-based deep learning model is implemented for sound classification.
