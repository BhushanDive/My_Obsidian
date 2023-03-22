
**We have thought of three different methods to classify the audio data**

- The first method is simply by creating spectrogram (Mel spectrograms) of the audio files and using CNN to classify them.

- Second method is by using MFCC's ( Mel Frequency cepstral coefficients ) in this method we preprocess the data by applying window function then applying some filters and after that we take its loagrithms. After that we apply DCT (Discrete Cosine Transform) and after that we can use any multiclass classification algorithm to classify the data.

- Third method is an unique unproven method in which we create a time-series of the audio data and then train the models on that data.