# Chapter 1
## Vocabulary:
- Autoencoder: combination of an encoder function that converts the input data into a different representation and a decoder function that converts the new representation back into the original format.    
- multilayer perceptron (MLP): a mathematical function mapping some set of input values to output values.  

## Notes 1.0:    
Deep learning resolves solving difficult problems by making hidden layers that distinguish between abstract mappings of unique features of classification.  The **visible layer** is the base layer where the data is input.  The **hidden layer(s)** are the interior layers that determine mappings which distinguish the characteristics of objects.     

> Given the pixels, the first layer can easily identify edges, by comparing the brightness of neighboring pixels. Given the first hidden layer’s description of the edges, the second hidden layer can easily search for corners and extended contours, which are recognizable as collections of edges. Given the second hidden layer’s description of the image in terms of corners and contours, the third hidden layer can detect entire parts of specific objects, by finding specific collections of contours and corners. Finally, this description of the image in terms of the object parts it contains can be used to recognize the objects present in the image.

![Overview of Machine Learning](https://github.com/nschampions2004/deep_learning_notes/chapter_1/images/machine_learning_overview.png)    

## Notes 1.1:
- Part 1: Applied Math and Learning Basics
  - Chapter 2: Linear Algebra
  - Chapter 3: Probability and Information Theory
  - Chapter 4: Numerical Computation
  - Chapter 5: Machine Learning Basics
- Part 2: Deep Network Modern Practice
  - Chapter 6: Deep Feedforward Networks
  - Chapter 7: Regularization
  - Chapter 8: Optimization
  - Chapter 9: CNN's
  - Chapter 10: RNN's
  - Chapter 11: Practical Methodology
  - Chapter 12: Applications
- Part 3: Deep Learning Research
  - Chapter 13: Linear Factor Models
  - Chapter 14: Autoencoders
  - Chapter 15: Representation Learning
  - Chapter 16: Structured Probabilistic Models
  - Chapter 17: Monte Carlo Methods
  - Chapter 18: Partition Functions
  - Chapter 19: Inference
  - Chapter 20: Deep Generative Models

## Notes 1.2:

Deep learning dates back to the 1940's.  The field has been through ebbs and flows of popularity in the research community and re-branded many times.  At the beginning it was called **cybernetics** which gave way to **connectionism** which leads to present day **neural networks**.  Cybernetics brought in **stochastic gradient descent** to minimize error.  Connectionism identified **back-propagation** as a means to train a neural net with one or two layers.  Though neural networks are modeled after the human brain, we are very far from being able to more closely align with the human brain due to amount of neurons needed to be monitored.  Today, most neural networks are modeled off the **rectified linear unit** neuron.  Though displayed in the main stream media as a mirror to the brain, instead deep learning draws from:
  - linear algebra
  - probability
  - information theory
  - numerical optimization.    

Throughout the connectionist phase, the main thread to be pulled through was that a large number of simple computational units can demonstrate intelligent behavior when networked together.  Other, secondary ideas came about in this time period too like **distributed representation**.  This concept holds that each feature should be involved in the representation of many possible inputs.  < Fill this in when you care about it>     
> As of 2016, a rough rule of thumb
is that a supervised deep learning algorithm will generally achieve acceptable
performance with around 5,000 labeled examples per category, and will match or
exceed human performance when trained with a dataset containing at least 10
million labeled examples.
