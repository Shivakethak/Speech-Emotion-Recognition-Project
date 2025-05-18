# SpeechProcessingProject
This is our project on Speech Emotion Recognition
A Deep Learning (LSTM) model with keras.
This study aims to investigate and implement an Artificial Intelligence (AI) algorithm that will analyze an audio file in real-time, identify and present the expressed emotion within it.
A classification model is developed in a Deep Learning method, meaning a Deep Neural Network (DNN) while an advanced model for time-series analysis has been chosen, which is the Long Short-Term Memory (LSTM).
For the train of the model, expressed emotions by actors have been used from The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) from the Ryerson University, as well as the Toronto Emotional Speech Set (TESS) from the University of Toronto. 
Results had shown an accuracy of 87% of emotional recognition from speech.
A real-time implementation of the model is executed, receiving microphone signal as input and analyzing it cyclicly, outputs the distribution of emotions expressed every time cycle. When recognizing silence of 2 seconds or more, the system autonomously stops.

files :-
1- preprocessing_of_single_audio_file.ipynb ( Consist of preprocessing code for single file)

2- Model_Implementation.ipynb ( Consist of model implementation and training code)

3- real_time_emotion_recognition.ipynb ( Consist of real-time emotion recognition code)
