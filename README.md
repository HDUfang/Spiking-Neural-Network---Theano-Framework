# Spiking-Neural-Network---Theano-Framework
Spiking neural networks are biologically plausible CNNs which learn through a temporally dependent learning method known as Spike Time Dependant Plasticity (STDP)- an alternate to gradient descent.  This repository contains layers built on top of Lasagne layers for spiking neural networks. This is the first implementation of spiking neural networks in any tensor based framework to the best of my knowledge.   The various layers can be found in snn.py for dense layer and snn_conv.py for other layers. These layers are to be processed for each time step which is done using the Theano scan as a quick hack - in the snn class.  The results can be found the ppt.  Further details on how to use the code will be put up after later.