# Branching and Merging Convolutional Network with Capsules and Residual Connections
 A modified implementation of " A Branching and Merging Convolutional Network with Homogeneous Filter Capsules" paper

You can read the original paper <a href="https://arxiv.org/abs/2001.09136">A Branching and Merging Convolutional Network with Homogeneous Filter Capsules</a>

Changes made from the original architecture are:-
* Using original Capsule network instead of Homogeneous Filter Capsules
* Using Residual Connections after every two convolution layer
* added a trainable coefficient which determines the strength of residual connection, it is similiar to the idea of highboost filtering
