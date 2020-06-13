This is my **Image preprocessing and encoding baseline, based on [Keras](https://keras.io/)**. 
I'm using `Python 3.6`.
# Contents

[***Objective***](https://github.com/DmitryIo/animefaces#objective)

[***Concepts***](https://github.com/DmitryIo/animefaces#concepts)

[***Implementation***](https://github.com/DmitryIo/animefaces#implementation)

[***Results***](https://github.com/DmitryIo/animefaces#results)

# Objective

**To build a model that can convert pixel images into array of numbers**

My main goal was creating a programm which would be able to preprocess and work with images. At that time i was watching some Japaneese cartoons, and that is why i decided to make a project connected to machine learning problem. How can computer work with such images?

![](./img/girls1.jpg)

![](./img/girls2.jpg)

It is easy to see similarity for human between these photos. But how can a computer solve this problem?

# Concepts

**Encoder**

For this task i have implemented machine learning architecture, which is called 'Encoder&Decoder architecture'
Typically, a model that generates arrays will use an Encoder to encode the input into a fixed form and a Decoder to decode it, pixel by pixel, into an array.

`How it works:`
![](./img/encoder.jpg)

**Decoder**

Decoder is used just for training encoder and for my task i dont use it more.

# Implementation

**Dataset**

For this task i have found [Kaggle](https://www.kaggle.com/) dataset. The link to download it - https://drive.google.com/file/d/10DAA6GOT6K9I7w0ibYnt_HzNPac03s6b/view?usp=sharing

It contains 100.000 pixel images 64x64. The kind of it you could see at [Objective](https://github.com/DmitryIo/animefaces#objective)

**Coding**

Full process of coding described in my [Notebook](autoencoder.ipynb) `All comments are Russian there`

# Results

The result of my work is: 

 **1) I have learned how to use autoencoder and decoder to process images**
 
 **2) Now i can work with all these arrays of images like i want to. And there is my next project, in which i have used all this stuff [Project](https://github.com/DmitryIo/animebot)**
 
Thank you for attention!
