# Reproduce Capsules Result

Hinton has some recent work using capsules as an architecture
component in neural networks (https://arxiv.org/abs/1710.09829,
dynamic routing between capsules).  This project is about learning
some of the basics of capsules, and getting them to work in
tensorflow.  As a concrete goal we intend to reproduce the results
of http://www.cs.toronto.edu/~fritz/absps/transauto6.pdf.  That is

1. Get a working interaction with a GPU instance on AWS
2. Set up the networks as described in the paper
3. Train and get similar results (e.g. transformed, but somewhat
  fuzzy looking images)
4. Experiment with different numbers of capsules
5. Try introspection on the network to understand/visualize how it works

Team:
- Bart Kastermans
- Wouter Theune
