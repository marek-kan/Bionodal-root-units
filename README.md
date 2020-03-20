# Bionodal root unis
In this repository I compare different ANN models in terms of their performance, namely ReLU, ELU, Leaky ReLU and BRU. I use TensorFlow 2 to build and train models. I wrote an article about this repository, you can read it [here](https://github.com/user/repo/blob/branch/other_file.md).

All of this is inspired by Deep learning improved by biological activation Functions (Bhumbra, 2018)
[https://www.researchgate.net/publication/324860573_Deep_learning_improved_by_biological_activation_functions]

### Description
At the start of every notebook BRU functions are defined whith custom gradients. It was necessary because automatic differentiation by TF was unstable in some parts of functions.

 * BRU_flatten: looks at performace on MNIST with usage of very basic ANN (flatten input)
 * BRU_regresion: looks at performance on Boston Housing dataset
 * BRU_ConV: looks at performance on CIFAR-10 dataset, CNN mimics ConvPool structure to simulate more complex deep learning model
 
Notebooks only contain technical comments, if you want to learn more about this topic please refer to my article and research paper by Bhumbra. 
