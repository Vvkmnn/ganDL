## ganDL
The fifth project for the [Deep Learning Foundations Nanodegree program](https://www.udacity.com/course/deep-learning-nanodegree-foundation--nd101), cofused on Generative Adversarial Networks!

![](https://image.slidesharecdn.com/generativeadversarialnetworks-161121164827/95/generative-adversarial-networks-11-638.jpg)

All of the fun stuff is available in `face_generation.ipynb`.

### Setup

This project requires Python 3 (Preferably as distributed by [Anaconda](https://www.continuum.io/downloads)) and [Tensorflow](https://www.tensorflow.org/).

```python
appnope==0.1.0
autopep8==1.3.2
backports.weakref==1.0rc1
bleach==1.5.0
decorator==4.1.2
html5lib==0.9999999
ipykernel==4.6.1
ipython==6.1.0
ipython-genutils==0.2.0
jedi==0.10.2
jupyter-client==5.1.0
jupyter-core==4.3.0
Markdown==2.6.8
numpy==1.13.1
pexpect==4.2.1
pickleshare==0.7.4
prompt-toolkit==1.0.15
protobuf==3.3.0
ptyprocess==0.5.2
pycodestyle==2.3.1
Pygments==2.2.0
python-dateutil==2.6.1
pyzmq==16.0.2
simplegeneric==0.8.1
six==1.10.0
tensorflow==1.0.0
tornado==4.5.1
traitlets==4.3.2
wcwidth==0.1.7
Werkzeug==0.12.2
```

### Results

In this project, we implemented the steps necessary to build a simple imagegeneration work, built on MINST, and then later applied to CelebA to generrate celebrity faces. We focused on the following topics: 
* **Generators**
* **Discriminators**
* **Convolutional Layers**
* **Flattening Layers**
* **Fully Connected Layers**

The final model could produce relatively indistinguishable versions of the MINST or CelebA image dataset, using randomly generated noise in the Generator fool the Discriminator. Here's an example of how that looks during generation:

![](https://d3ansictanv2wj.cloudfront.net/gan-images-final-d7bdb862726f6fd928a7c859a69c3248.gif)

