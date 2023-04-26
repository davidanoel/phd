# PhD Dissertation

Repository to support PhD dissertation for improving spatial invariance in convolutional neural networks.

# Requirements

To run all experiments, first install the following libraries if not already done so:

- Python 3.9 or above
- TensorFlow version 2.10.1 or later: https://www.tensorflow.org
- Keras 2.10.0: https://github.com/keras-team/keras
- Pandas version 1.5.3 or later: http://pandas.pydata.org
- Scikit-learn version 1.2.1 or later: http://scikit-learn.org
- Numpy 1.24.1 or later: https://numpy.org/install/
- Matplotlib version 3.6.3 or later: http://matplotlib.org/
- SciPy version 1.9.2 or later: http://www.scipy.org/

The easiest way to get (most) of the above is to use an all-in-one installer such as Anaconda: https://docs.anaconda.com/free/anaconda/install/index.html

# Installation

1. Clone the repository to a folder on the local machine.
2. Open the notebook of interest and run using Python.
   * To replicate the experiments, execute the **spatial_invariance.ipynb** notebook.
   * To generate and train the cDCGAN, execute **Conditional DCGAN.ipynb**.
   * To perform analytics on the results, execute **analysis.ipynb**.

> It should be noted that running the experiments or training the cDCGAN could take several hours depending on the speed of the computer being used.
