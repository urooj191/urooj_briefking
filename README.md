# Phase 1
1. Studied different data types of Python programming.
2. Studied about the libraries of Python.
3. Studied numpy, pandas and matplot libraries of Python.
4. Completed the crash course introduction to  machine learning in which I learned about the linear regression, gradient descent, training, validating and test sets. I also learned about logistic regression, classification and regularization. I also learned basics of artificial neural network.

# Phase 2 of Project
1. Libraries to convert speech to text
Read about the speech recognition library in python which is used to convert speech to text.
Read about the google speech recognition API which can be used in speech recognition library to convert the speech to text.
Google API requires wav format therfore I read about the libraries which convert mp4 or mp3 to wav format and found moviepy and pydub can convert mp4 and mp3 to wav format respectively. Applied these libraries on mp4 and mp3 files and converted them to wav format.
Applied the speech recognition API on the few audio files and found that text generated was not totally correct.
Problem with google speech recognition library is that only particular length of audio can be converted if it goes beyond the threshold value than it will not convert and give an error. It also requires internet to work.
2. Models to convert speech to text
2.1 Transformers model
Applied the pretrained transformers model to different audio sets and found that it is working better than google api. 
Models doesnot have any threshold of using files.
Model doesnot require any internet
2.2 NVIDIA ASR model
Applied the NVIDIA automatic speech recognition model and found that it is also working better than google api.
This model have constraint of length of audio
From all the models and libraries I have applied I found transformers model is best model out of all the models.



