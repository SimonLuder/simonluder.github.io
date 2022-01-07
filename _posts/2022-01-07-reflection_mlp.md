---
title: Reflection Multilayer Perceptron from Scratch
tags: [Reflection, Algorithms]
style: 
color: 
description: A reflection of my implementation and application of a multilayer perceptron.
---

{% include elements/figure.html image="https://github.com/SimonLuder/SimonLuder.github.io/blob/main/pictures/mlp.png?raw=true" caption="" %}

Within one of my studiy modules we were given the challenge to implement an own Multilayer Perceptron. Afterwards it should be used to classify car brands based on features like fuel capacity, vehicle price or the color of the paint. The implementation should be realized in Python and the use of libraries should be limited to NumPy and Pandas.

Since I had only very limited experience with multilayer perceptrons or other neural networks, I had a lot of respect for the task at hand. I previously implemented a single layer perceptron, but at a much lower level of complexity than was expected in the current case.

In the task we had various specifications that severely narrowed its methods. I suppose the idea behind this was that we could focus more on the actual implementation and didn't have to worry too much about the pros and cons of the different methods. For example, we had to use the Gradient Descent method for optimization of the multilayer perceptron and the logistic sigmoid method for the activation function.

During implementation, a number of challenges had to be faced. The biggest challenge for me was the implementation of the backpropagation and it was very rewarding when it finally worked. Unfortunately, it was not possible for me to achieve a satisfying accuracy in the classification that would justify the use of my multilayer perception over other classification methods.

Overall, the task of implementation turned out to be much more time-consuming than expected. However, this effort was worth it, as it improved my understanding of neural networks in general more than would have been possible with my previous training material on this topic.
