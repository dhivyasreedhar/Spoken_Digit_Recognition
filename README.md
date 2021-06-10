# Spoken_Digit_Recognition

Classification Methods for Audio MNIST Dataset

Dataset consists of recordings of spoken digits in wav files at 8kHz. The recordings are trimmed so that they have near minimal silence at the beginnings and ends.

The Samples recorded by 4 speakers with English pronunciations and there are totally 2,000 recordings (50 of each digit per speaker) in the dataset.

Files are named in the following format: {digitLabel}{speakerName}{index}.wav Example: 7_jackson_32.wav


If you want to know more about how dataset is created and contribute to creating more data, please check the below repository:

https://github.com/Jakobovski/free-spoken-digit-dataset

#Files/Folders Information

audio_plot.ipynb: Plot audio signal and spectrogram using Librosa

audio_to_spectrograms.ipynb: convert audios to images and store them to spectrograms directory.

model.ipynb: convert images to numpy arrays, classification task based on different cnn architectures.

cnn1,cnn2: contains models graphs and plots


