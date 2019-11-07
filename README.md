# Python_Project on Speech Emotion Recognition.
The main objective of this project is to build a model to recognize emotion from speech using the librosa and sklearn libraries and the RAVDESS dataset.


Speech Emotion Recognition is a process in order to recognize human emotion and affective states from speech.Voice often reflects underlying emotion through tone and pitch.
Librosa, a python library used for analyzing audio and music, is used for this recognition. It has a flatter package layout, standardizes interfaces and names, backwards compatibility, modular functions, and readable code. Soundfile is used to read and write sound files. It is an audio library based on libsndfile, CFFI and NumPy.
In order to install librosa and soundfile, following are the commands with anaconda prompt:-
  Librosa:-
     conda install -c conda-forge librosa
     conda install -c conda-forge/label/gcc7 librosa
     conda install -c conda-forge/label/cf201901 librosa
  Soundfile:-   
     conda install -c conda-forge pysoundfile
     conda install -c conda-forge/label/gcc7 pysoundfile
     conda install -c conda-forge/label/cf201901 pysoundfile
We will load the data, extract features from it, then split the dataset into training and testing sets. Then, we’ll initialize an MLPClassifier and train the model.
MLPClassifier implements a multi-layer perceptron (MLP) algorithm that trains using Backpropagation.A Multi-layer Perceptron (MLP) is a supervised learning algorithm that learns a function f(.):R^m-->R^o by training on a dataset, where m is the number of dimensions for input and  o is the number of dimensions for output. Given a set of features X and a target y, it can learn a non-linear function approximator for either classification or regression. It is different from logistic regression, in that between the input and the output layer, there can be one or more non-linear layers, called hidden layers.
