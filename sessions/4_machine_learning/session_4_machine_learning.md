[Home](../../README.md) / [Sessions](../README.md) / Session 4: Machine Learning

# Session 4: Machine Learning

* [Lecture](#lecture)
* [Reading](#reading)
* [Hands-On Exercise](#hands-on-exercise)
	* [Files](#files)

## Lecture

### History of AI Continued

> Slides: [History of AI continued](lecture/slides_history_of_ai_continued.md)

Continuing our introduction to the history of artificial intelligence the lecture explores the connectionist approach to AI. Statistical methods in the form of Neural Networks and implemented in Rosenblatt's Perceptron as early as 1958 didn't quite catch on until the mid 1980's. Not only due to the obstacles outlined in the last lecture, but also due to the unavailability of suitable training data, sufficient computing power and, last but definitely not least, the absence of a suitable algorithm to train multi-layer neural networks, which are required to solve problems that are not linearly separable.

Despite the publication of the [Backpropagation](https://en.wikipedia.org/wiki/Backpropagation) algorithm for training multi-layer neural networks in 1986, the dominant AI methods until 2015 used other approaches. [IBM Deep Blue](https://en.wikipedia.org/wiki/Deep_Blue_(chess_computer)), the AI that beat [Garry Kasparov](https://en.wikipedia.org/wiki/Garry_Kasparov) in chess, ran a search algorithm that calculates every possible sequence of moves and counter-moves, effectively taking a brute-force approach to winning at chess enabled by increasing computational power.

[Deep Learning](https://en.wikipedia.org/wiki/Deep_learning), the arguably most popular AI method at the time of writing, took off after a Deep Neural Network outperformed all previously available techniques in the 2015 [ImageNet Challenge](http://www.image-net.org/challenges/LSVRC/). 

### Introduction to Neural Networks

The second lecture outlines the mechanisms by which a neural network functions. Rather than employing the metaphor of neurons and the brain, neural networks are presented as a type of [computational graph](lecture/notes_3_functions_as_computational_graphs.md)) and a function for making predictions based on data.

Students are introduced to (linear) functions and how they can be used to make predictions based on the technique of [linear regression](https://en.wikipedia.org/wiki/Linear_regression). Computational graphs are then introduced and the mechanisms of how an arbitrary computational graph can be used to model data is demonstrated using an [interactive tool]((lecture/exercise_1_computational_graph.md)).

Finally, the distinct features of neural networks are outlined and the importance of the [activation function](https://en.wikipedia.org/wiki/Activation_function) for training them.

The lecture uses a whiteboard and an [online exercise](lecture/exercise_1_computational_graph.md). The sketches and explanations are reproduced here:

* [Introduction](lecture/notes_0_introduction_to_neural_networks.md)
* [Linear Functions](lecture/notes_1_linear_functions.md)
* [Modelling Data with Linear Functions](lecture/notes_2_modelling_data_with_linear_functions.md)
* [Representing Functions as Computational Graphs](lecture/notes_3_functions_as_computational_graphs.md)
* [Training a Computational Graph on Data](lecture/notes_4_training_a_computational_graph.md)
* [Computational Graph Exercise](lecture/exercise_1_computational_graph.md)
* [Neural Networks](lecture/notes_5_neural_networks.md)

### Further notes and resources

We now know what a neural network is and how it functions. But how to train it? Here are some resources and example on neural network training:

* Visit the [Tensorflow Playground](https://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=&seed=0.04538&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false)
* Train a Neural Network [in your browser](https://cs.stanford.edu/people/karpathy/convnetjs/demo/cifar10.html)
* Train a Neural Network with your [webcam](https://teachablemachine.withgoogle.com)
* Understand how why an image receives a certain label through this [reverse classification tool](https://lrpserver.hhi.fraunhofer.de/image-classification)
* Explore examples of [Generative Adversarial Networks](https://machinelearningmastery.com/impressive-applications-of-generative-adversarial-networks/)
* Explore how individual neurons encode visual features using [SUMMIT](https://fredhohman.com/summit/)
* Explore the latent space of a GAN with [GANbreeder](https://artbreeder.com/)
* Try a [demo](https://talktotransformer.com/) of the GPT-2 text prediction model.


## Reading

This sessions reading focuses on an often overlooked aspect of machine learning and training data: the human labour involved in creating training datasets.

### Neural nets are just people all the way down

_Vicki Boykis_

Boykis, V. (2019). Neural nets are just people all the way down. https://vicki.substack.com/p/neural-nets-are-just-people-all-the


### Crowdproduktion von Trainingsdaten: Zur Rolle von Online-Arbeit beim Trainieren autonomer Fahrzeuge

_Florian Alexander Schmidt_


Schmidt, Florian A. (2019). Crowdproduktion von Trainingsdaten: Zur Rolle von Online-Arbeit beim Trainieren autonomer Fahrzeuge. Hans-Böckler-Stiftung. https://www.boeckler.de/pdf/p_study_hbs_417.pdf


## Hands-On Exercise

In the hands-on exercise students get to train a text generator model similar to, though not quite as powerful as, the [GPT-2](https://talktotransformer.com/) model that can be tried out in the browser.


### Interactive textgenrnn Demo w/ GPU

A Jupyter notebook to train a custom text generator model by [Max Woolf](https://minimaxir.com/)

#### Files

- Access and copy the Jupyter notebook here: https://colab.research.google.com/drive/1mMKGnVxirJnqDViH7BDJxFqWrsXlPSoK

### How to Develop a Word-Level Neural Language Model and Use it to Generate Text

A Jupyter notebook based on the code of Jason Brownlees [blog post](https://machinelearningmastery.com/how-to-develop-a-word-level-neural-language-model-in-keras/.). The code uses [Keras](https://keras.io/), a deep learning library for Python.

#### Files

- Train the model using [Keras_Text_Generator_Training.ipynb](hands_on/keras_text/Keras_Text_Generator_Training.ipynb)
- Generate text using [Keras_Text_Generator_Run.ipynb](hands_on/keras_text/Keras_Text_Generator_Run.ipynb)