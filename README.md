# Speaker-Recognition-System-with-multi-language-model-detection

Speaker Recognition is a technique that uses a specific person's voice commands to improve a system. Everyone has their own vocal folds and track. Individuals are recognized by their vocal characteristics, as well as differences in spoken language, accents, and dialects. In recent times, security issues such as imposter attacks and speaker variability on speaker recognition systems have had a significant impact on the system's performance. (Wang Q. , 2020). In this paper, we will discuss the current security issues with speaker recognition systems and how to overcome them.

The feature extraction module and the classification module are the two main parts of the speaker recognition system. Pitch, tempo, and spectral characteristics are some examples of pertinent information that is extracted from the audio signal by the feature extraction module. The classification module then makes use of this data to locate the speaker by comparing it to a database of speaker models that already exist.

Using a custom multi-language dataset, we evaluated our novel and improved speaker recognition system thoroughly. This improved system incorporates several advanced techniques, such as speaker and language attribute training, attention mechanisms and LSTM layers, and testing on the trained model on test dataset.

I conducted an in-depth ablation study to understand the impact of each innovation, systematically analysing the contribution of each component within our model. This investigation revealed the importance of each component in improving recognition performance.

# Audio Dataset: 
Custom made dataset with 6 male speakers speaking 10 different languages each has over 7 utterances (recordings were made from the varying distance from the speaker[0.5m, 1m, 1.5m, 2m, 2.5m]).

# Languages: 
English, German, Spanish, Italian, Russian, Kannada, Telugu, Tamil, Malayalam and Hindi.

# Model: 
Using a pretrained RNN as a feature extractor for audio data, a simple RNN model is used. Capture relevant acoustic and linguistic features, the pretrained model is initially trained on a related task, such as language modeling or speech synthesis. These learned features are then fine-tuned using datasets from target speakers and language recognition. This method uses transfer learning to adapt the model to the specifics of the recognition task.

# Softwares and Libraries used: 
Audacity - 3.3.3
Python - 3.9.0
Jupyter Notebook - 1.0.0
Numpy - 1.21.6
Scikit-Learn - 1.0.2
SciPy - 1.7.3
Keras - 2.11.0
Tensorflow - 2.11.0
Matplotlib - 3.5.2
Librosa - 0.10.1

# File:
The entire project is uploaded as a PDF file along with the referneces in it.
