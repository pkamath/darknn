# Dark Neural Network Construction

The Dark Neural Network Constructor is a tool to discover neural network 
structures from a shallow specification of a problem (a shallow 
specification consists of input dataset and output and but no problem 
definition (such as image classification, language translation etc.)).
The goal is to understand, whether we can discover structures such as 
CNNs, LSTMs, GRUs given just an input dataset and output, and a set of
processing and storage blocks.

More concretely, the goal is to solve two problems:

* Given a shallow problem specification, discover the network structure 
that is best suited to solving the problem. 
* Given an arbitrary network discover if there exist shallow problems 
that it is suited to solving


Other related problems:
* Neural Architecture Search (NAS): Discovers a network for a problem 
such as image recognition or language modeling by discovering an instance of 
a know architecture type such as a CNN or RNN. 
* MetaLearning: Discovers a network for a new problem based on performance of 
known networks on known problems

#Status
Under implementation
