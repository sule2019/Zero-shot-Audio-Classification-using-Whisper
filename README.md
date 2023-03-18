# Zero-shot-Audio-Classification-using-Whisper

This GitHub repository contains code for zero-shot audio classification using whispers in Turkish. The objective of this project is to classify audio signals based on their content without the need for any prior training on specific keywords or phrases. 

It performs this in 2 steps
1. Classify the background noise in English in a zero-shot setting using the average log probabilities
2. Translate noise to Turkish

The model is built using Open AI whisper speech model. Zero shot classification allows the model to predict the class label of an input audio file even if it has not seen any examples of that class during training. The dataset used in this the class names of background noises class_names.txt

Sample audio files are also in the files and can be used for testing

This code is an extension of https://github.com/jumon/zac.
