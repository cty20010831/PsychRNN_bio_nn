# PsychRNN
[![tests](https://github.com/murraylab/PsychRNN/workflows/tests/badge.svg)](https://github.com/murraylab/PsychRNN/actions?query=workflow%3Atests)
[![codecov](https://codecov.io/gh/murraylab/PsychRNN/branch/master/graph/badge.svg)](https://codecov.io/gh/murraylab/PsychRNN)
[![Documentation Status](https://readthedocs.org/projects/psychrnn/badge/?version=latest)](https://psychrnn.readthedocs.io/en/latest/?badge=latest)

## Overview

Full documentation is available at [psychrnn.readthedocs.io](https://psychrnn.readthedocs.io/).

This package is intended to help cognitive scientists easily translate task designs from human or primate behavioral experiments into a form capable of being used as training data for a recurrent neural network.

We have isolated the front-end task design, in which users can intuitively describe the conditional logic of their task from the backend where gradient descent based optimization occurs. This is intended to facilitate researchers who might otherwise not have an easy implementation available to design and test hypothesis regarding the behavior of recurrent neural networks in different task environements.

Release announcments are posted on the [psychrnn mailing list](https://www.freelists.org/list/psychrnn) and on [GitHub](https://github.com/murraylab/PsychRNN)

Code is written and upkept by: [Daniel B. Ehrlich](https://github.com/dbehrlich>), [Jasmine T. Stone](https://github.com/syncrostone/), [David Brandfonbrener](https://github.com/davidbrandfonbrener), and [Alex Atanasov](https://github.com/ABAtanasov).

Contact: psychrnn@gmail.com 

## Getting Started

Start with [Hello World](https://psychrnn.readthedocs.io/en/latest/notebooks/Minimal_Example.html) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/murraylab/PsychRNN/blob/master/docs/notebooks/Minimal_Example.ipynb) to get a quick sense of what PsychRNN does. Then go through the [Simple Example](https://psychrnn.readthedocs.io/en/latest/notebooks/PerceptualDiscrimination.html) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/murraylab/PsychRNN/blob/master/docs/notebooks/PerceptualDiscrimination.ipynb) to get a feel for how to customize PsychRNN. The rest of [Getting Started](https://psychrnn.readthedocs.io/en/quickstart.html) will help guide you through using available features, defining your own task, and even defining your own model.

## Install

### Create a clean virtual environment
```
# Create a virtual environment
python -m venv venv

# Activate the environment
source venv/bin/activate

# Deactivate base conda environment
conda deactivate
```

### Dependencies

- python = 2.7 or python >= 3.4
- [numpy](http://www.numpy.org/)
- [tensorflow](https://www.tensorflow.org/) >= 1.13.1

- For notebook demos, [jupyter](https://jupyter.org/)
- For notebook demos, [ipython](https://ipython.org/)
- For plotting features, [matplotlib](https://matplotlib.org/)

PsychRNN was developed to work with both Python 2.7 and 3.4+ using TensorFlow 1.13.1+. It is currently being tested on Python 2.7 and 3.4-3.8 with TensorFlow 1.13.1-2.2.

**Note:** TensorFlow 2.2 does not support Python < 3.5. Only TensorFlow 1.13.1-1.14 are compatible with Python 3.4. Python 3.8 is only supported by TensorFlow 2.2.

### Installation

Normally, you can install with:

	pip install psychrnn

Alternatively, you can download and extract the source files from the [GitHub release](https://github.com/murraylab/psychrnn/releases/). Within the downloaded PsychRNN folder, run:

        python setup.py install

[THIS OPTION IS NOT RECOMMENDED FOR MOST USERS] To get the most recent (not necessarily stable) version from the github repo, clone the repository and install:

        git clone https://github.com/murraylab/PsychRNN.git
        cd PsychRNN
        python setup.py install

