# Perceptron Logic Gates

This project contains an implementation of logic gates perceptron. The logic gates handled are:

This project is based on Andrew Ng&#39;s Machine learning course on Coursera

https://www.coursera.org/learn/machine-learning/lecture/rBZmG/examples-and-intuitions-i

We use numpy to implement the logic gates

**Logic Gates:**

According to wikipedia

_&quot;a logic gate is an idealized or physical device implementing a Boolean function; that is, it performs a logical operation on one or more binary inputs and produces a single binary output. Depending on the context, the term may refer to an ideal logic gate, one that has for instance zero rise time and unlimited fan-out, or it may refer to a non-ideal physical device[1] (see Ideal and real op-amps for comparison).&quot;_

**Perceptron**

The neurons in the brain look a bit like this.

![neurons in the brain](https://github.com/SudhaHariharan/perceptronlogicgates/blob/master/images/perceptron1.png)
 
Image courtesy: [https://www.coursera.org/learn/machine-learning/supplement/jtFHI/lecture-slides](https://www.coursera.org/learn/machine-learning/supplement/jtFHI/lecture-slides)

A set of inputs (X) is passed to the neuron. Using weights(w) and an activation function, this will produce an output and a bias.

A perceptron is a single layer neural network and multi-layer perceptron is called Neural networks.

_ &#39;In _[_machine learning_](https://en.wikipedia.org/wiki/Machine_learning)_, the perceptron is an algorithm for _[_supervised learning_](https://en.wikipedia.org/wiki/Supervised_classification)_ of _[_binary classifiers_](https://en.wikipedia.org/wiki/Binary_classification)_ (functions that can decide whether an input, represented by a vector of numbers, belongs to some specific class or not)._[_[1]_](https://en.wikipedia.org/wiki/Perceptron#cite_note-largemargin-1)_ It is a type of _[_linear classifier_](https://en.wikipedia.org/wiki/Linear_classifier)_, i.e. a classification algorithm that makes its predictions based on a _[_linear predictor function_](https://en.wikipedia.org/wiki/Linear_predictor_function)_ combining a set of weights with the _[_feature vector_](https://en.wikipedia.org/wiki/Feature_vector)_.&quot; - Wikipedia_

**Representation:**
![Perceptron Representation](https://github.com/SudhaHariharan/perceptronlogicgates/blob/master/images/perceptron2.png)
 
The sigmoid function is a commonly used activation function.

g(z) = 1(1+e−z)


A sigmoid function when plotted looks like:

![Sigmoid](https://github.com/SudhaHariharan/perceptronlogicgates/blob/master/images/perceptron3.png)

The sigmoid function returns 1 if the z is over 4 and 0 if it is less than -4.

Replacing z with our hypothesis:

hꝊ(x) = 1/(1+e−θTx)
