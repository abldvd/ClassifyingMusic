# Classifying Music

Here are my attempts at classifying music with convolutional networks.

I'm converting some mp3 files to a sort of an image by calculating the FFT and then feeding it to a convolutional network.

I've also tried using the MEL spectrogram but I didn't find any improvements.

## Code Context
### Spectrogram
I've tried to replicate a lighter version of the VGG19 network.

### ConvolutionalOptimization
Attempts at optimizing hiperparameters with the keras-tuner package.
Experiment that colab didn't allow me to finish and I don't have a cuda enabled gpu lying around so I'll have to wait to complete this one.

### SupervisedContrastiveSpectrogram
Here I try to implement [supervised contrastive learning](https://keras.io/examples/vision/supervised-contrastive-learning/#supervised-contrastive-learning) for training the convolutional stack.
