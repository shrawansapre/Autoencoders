# Autoencoders
[Autoencoders](https://en.wikipedia.org/wiki/Autoencoder) are used for a variety of applicatons that focus on generating an output that is similar to the input. The main use of autoencoders is for addressing the **curse of dimensionality**. By projecting the original high-dimensional input onto a **latent space** (lower-dimensional) space, we are able to greatly reduce the number of dimensions used to identify the data. This latent space is further used to generate an output that is similar (not exactly same) to the input. 

The other application is denoising data. We notice that noise does not affect the functionality of deep autoencoders and that they can map noisy images to the clean original images with high accuracy.

## Usage
* Run the cells in [Autoencoders.ipnyb](https://github.com/shrawansapre/Autoencoders/blob/master/Autoencoders.ipynb) file.

## Requirements
*Python version: [3.6.6](https://www.python.org/downloads/release/python-366/)

*Python Libraries: numpy (1.15.1), matplotlib (2.2.3), keras, tensorflow

P.S. Code still under construction. 
