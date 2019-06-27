# hacoolkids

Supervised Learning - tasks where we have a metric for success, whether the data is labled or rewards are offered for performing the task well

Unsupervised Learning - refers to the problems where the model has no guidance and must infer patterns and features in the data indendently

Types of Supervised Learining:
  Classification - The model must classify input data; can be anything like flitering spam or choosing if an image is a cat or a horse
  
  Reinforcement Learning - The model interacts with a dynamic environment by observing the current state of the envinronment and rewards for good performance. Learning to play arcade games is one way to use reinforcememt learning.
  
How does a machine learning model "learn"?

First data is fed into the model. The parameters in the model take that data and return an answer.

The model's guess is then compared with the expected outcome. (Was the image a cat or a horse?)

Then the parameters are optimized in the direction of the expected outcome.

This process is repeated with new data until the model has optimized its parameters to be as likely as possible to guess the right answer.

WHAT'S IN A MODEL 

A machine learning model can be as simple as a single variable that changes over time to a whole network of thousands of neurons estimating complex processes. The more parameters a model has, the more nuanced the task it can learn becomes

Tuning your machine learning models is a matter of balancing complexity, processing time, and modle structure to be the best at its learning task.


INTRO TO TENSOR FLOW

WELCOME

Tensorflow is a library developed by gooole to faciitate the creation and training of machine learning models and neural networks

use Tensorflow to create and train machine learning models

STEPS:
-add imports
import tensorflow as tf

IMAGE RECOGNITION

Image recognition

A common usage of modern computing is image recognition.

Building your own Neural Net

Most machine learning-powered image recognition usues a technique called convolutional layers.

These neural network layers are somewhat similar to how neurons in the brain process visual data.

CONVOLUTIONAL NEURAL NETWORK

Neural networks learn to accomplish their tasks by reading training data and adjusting their neuron weights to imporve their chance of choosing the correct answer.

Densely connected networks, like the one you created earlier, work well for smaller training data, but image recognition requires processing much larger data

Convolutional neural networks imitate the structure of neurons that process images in the brain and use techniques to reduce neuron count, as well as maintainingg positional relationships in the data.

These networks are ideal for the task of learning information about what's in an image

BUILDING YOUR NETWORK

In order to make tuning parameters and make changes to yout network more easily, you'll create a class that sets up the neural network architecture in TensorFlow.

STEPS

Input Layers:

The first step in your network will be creating placeholders you can use to feed data into the network. You'll create these placeholders as class variables for easy access later.






