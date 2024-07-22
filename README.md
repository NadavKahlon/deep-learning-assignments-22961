# Deep Learning Assignments (22961)

My solutions to the assignments in a Deep Learning course I took in Spring 2022 at The Open University of Israel. All were graded 100/100.

The solutions are self explanatory - and so I omitted the associated questionaires. For completeness, I provide the following brief description of the tasks in each assignment.

We used PyTorch throughout the course.

## 1st Assignment

1. Implementation of the [alias method](https://en.wikipedia.org/wiki/Alias_method) algorithm for instantiation of tensors from from discrete probability distributions.
2. Custom implementation of tensor broadcasting.
3. Custom implementation of an autograd system (automatic derivative evaluation for arbitrarily-calculated scalars).

## 2nd Assignment

1. An implementation of a custom neural-netwrok layer named `SplitLinear` - a linear layer with shared weights.
2. An implementation of a custom neural-netwrok layer named `DropNorm` - an intelligent composition of a Dropout layer an a Batch Normaliztion layer.
3. Regression Network for Predicting Diabetes Progression

## 3rd Assignment

1. Custom implementation of a Convolutional layer.
2. Derivation of the backpropagation formula for a convolutional layer.
3. Transfer learning ResNet18 for CIFAR-10 classification.

## 4th Assignment

2. An implementation of a custom RNN cell named `ElmanResetCell` - an Elman cell with a "reset" gate. We also test it on the SST2 sentence classification dataset.
3. Implementation of fully-connected & convolutional autoencoders. We also explore such autoencoders by analyzing their performance, explainability, and noise-resilience, using the MNIST dataset
