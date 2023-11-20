# Image-Captioning

Image captioning is the process of generating a textual description of an image. It utilizes both Natural Language Processing and Computer Vision to create captions.
This task resides at the intersection of computer vision and natural language processing. The majority of image captioning systems employ an encoder-decoder framework, wherein an input image is encoded into an intermediate representation of the information within the image. Subsequently, this representation is decoded into a descriptive text sequence.

CNNs + RNNs (LSTMs)

To perform Image Captioning we will require two deep learning models combined into one for the training purpose.

Convolutional Neural Networks (CNNs) extract features from the image, resulting in a vector of a specific size, known as vector embeddings. The dimensionality of these embeddings depends on the type of pre-trained network utilized for feature extraction.

LSTMs are employed in the text generation process. The image embeddings are concatenated with the word embeddings, forming a combined input that is then passed to the LSTM to predict and generate the subsequent word in the sequence.


