### Understanding deep Convolutional Neural Networks with a practical use-case in Tensorflow and Keras

This jupyter notebook reassembles the code of this <a href="https://ahmedbesbes.com/understanding-deep-convolutional-neural-networks-with-a-practical-use-case-in-tensorflow-and-keras.html">
article </a>

####  Environment setup: 

1. Use Python 3.6: No hassle, intall everything via Cond. Here's the <a href="https://www.anaconda.com/download/#download">installation link<a> 
2. Install the lastest version of Tensorflow: https://www.tensorflow.org/install/install_windows
  I used a windows machine, same applies of Linux and Mac OS X

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
  3. ```bash
  pip install graphviz  
  pip install pydot  

Example 
<p align="center">
<img src="https://ahmedbesbes.com/images/model.png" width="25%"></img>
</p>
