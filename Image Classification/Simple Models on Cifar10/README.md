**Conclusion** 

In the classification problem using Cifar-10 dataset, the accuracy of the baseline model (code 1) can be increased by doing below things:

- increase the number of epochs (good effect)
- using global max pooling at the end, instead of flatten (good effect)
- increase the size of the filters in convolusion layers (small effect)
- increase the number of filters in convolusion layers (small effect)

And bad effects on accuracy caused by below things:

- using batch normalization after each layer

My emerged question: Shall we use batch normalization before the activation at each layer? or we should use it after activation?

It seems to be dependent on the task and be experimental.
