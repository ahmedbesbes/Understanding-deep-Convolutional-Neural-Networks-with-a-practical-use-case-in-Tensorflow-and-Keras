## Understanding deep Convolutional Neural Networks with a practical use-case in Tensorflow and Keras




This jupyter notebook reassembles the code of this <a href="https://ahmedbesbes.com/understanding-deep-convolutional-neural-networks-with-a-practical-use-case-in-tensorflow-and-keras.html">
article </a>

It also contains a trained CNN model, so that you can use it yourself and test it. 


### Summary of this article

This post a 4-part tutorial where I:

1. Present an image dataset from the Cat vs. Dog Kaggle competition and explain the complexity of the image classification task
2. Go over the details about Convolutional Neural Nets, explaining their inner meachanisms and the reason why they perform better than fully connected networks.
3. Set up a deep learning dedicated environment on a powerful GPU-based EC2 instance from Amazon Web Services (AWS)
4. Train two deep learning models: one from scratch in an end-to-end pipeline using Keras and Tensorflow, and another one by using a pre-trained network on a large dataset.

These 4 parts are independent.

###  Environment setup: 

1. Use Python 3.6: No hassle, intall the Conda distribution that encapsulates the PyData stack (SciPy, Pandas, Matplotlib, etc.). Here's the <a href="https://www.anaconda.com/download/#download">installation link<a> 
2. Install the lastest version of Tensorflow: https://www.tensorflow.org/install/install_windows
  I used a windows machine, same applies for Linux or Mac OS X

3. Install the following python dependencies:

```bash
pip install keras
pip install tqdm
pip install keras-tqdm
conda install -c conda-forge opencv 
```

4. [Optional] Dependencies to obtain GraphViz plots of the CNN architectures: 

    1. Install Graphiz: http://www.graphviz.org/Download..php
    2. Add the Graphiz binaries to you  PATH
    3. Install Graphiz Python bindings
    ```bash
    pip install graphviz  
    pip install pydot  
    ```
  
<p align="center">
<img src="https://ahmedbesbes.com/images/model.png" width="25%"></img
</p>
