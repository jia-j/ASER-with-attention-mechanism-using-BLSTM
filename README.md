# ASER-with-attention-mechanism-using-BLSTM

 audio -> log mel spectrogram (unlike traditional spectrogram , it will have 3 layers like RGB image , static spectrogram, its delta nd double delta respectively)-> 2D CNN layers -> BLSTM layers-> Attention layer -> Fully Connected Layer -> Softmax Layer -> Emotion Probability Distributions

**Note: It is very much starting version of Project. There will be further modification in algo and code in future. This model does not perform well enough as of now, I am still working on it**

[**_EmoDB database_**](https://drive.google.com/open?id=1zugRF4UfJQjfZqzE-zZjJN5_lyx2Ax9o)

# Libraries used

- Keras
- Tensorflow (not necessarily required)
- librosa
- python_speech_features 
- Numpy


#
atten_layer.py is not written by me. It is taken from someone's github project. (Will cite a project a soon as i find the project link)

For understanding attention model in speech emotion recognition you can see

[Automatic Speech Emotion Recognition Using Recurrent Neural Networks with Local Attention](https://www.youtube.com/watch?v=NItzgTQ9lvw)


[**_emodb.pkl_**](https://drive.google.com/open?id=1DmmMtHPZUcA16tYGWjFId0wgnxgj2cvh)

[**_emodb_test.pkl_**](https://drive.google.com/open?id=1XHea79-2uBFSkl5-wEYpqTE_N8ZoiaxB)
