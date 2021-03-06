Mean-Field Learning

We want to find the following latent binary variables that are used to generate a bunch of 4x4 images.

The Expectation-Maximization algorithm is intractable because the latent variables are binary.
Hence, we use the variational approximation of the model to derive a new algorithm called Mean-Field Learning.

This code is an extract of my answer to an assignment of the "Approximate Inference and Learning in Probabilistic Models" module of the Gatsby Computational Neuroscience Unit at UCL.

For more info, please contact me or take a look at :
http://papers.nips.cc/paper/895-factorial-learning-and-the-em-algorithm.pdf
