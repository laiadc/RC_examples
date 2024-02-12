# Reservoir computing examples

Recurrent neural networks (RNN) are a deep learning tool used to deal with sequential data, such as text or time series. Within this context RNNs have proven to give optimal results, due to their ability to keep the knowledge learnt from past data. However, RNNs are known to be computationally expensive during training, and such training may be complicated due to the problem of exploding gradients during back propagation. *Reservoir computing (RC)* is a novel technique which is devoted to solve these problems when working with sequential data.
In the RC framework, the learning complexity of the problem is reduced to performing a linear regression. The key is to design a dynamical system (the internal network) which learns the input-output dynamics. For this reason, the internal states of the network are called *echo states*, since they can be though as an echo of their past. Such internal states are univocally determined by the input and output of the network.

In this repository, we explore the echo states properties and show how to properly train a reservoir computing model. The repository is organized with two jupyter notebooks:

+ **EchoStates_Properties-Periodic.ipynb**: In this notebook we are going to check some of the echo state properties of Reservoir Computing.
+ **Training_Periodic_function.ipynb**: In this notebook we explore different strategies and tricks to train a neural network in the context of Reservoir Computing. In particular, we will use the reservoir computing model to predict a periodic dynamics. 


### BibTex reference format for citation for the Code
```
@misc{DomingoRC,
title={Reservoir Computing examples},
url={https://github.com/laiadc/RC_examples/},
note={GitHub repository containing a guide to train a reservoir computing model.},
