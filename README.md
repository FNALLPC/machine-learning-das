# CMS Machine Learning Data Analsyis School (DAS) Short Exercise

## Introduction

This is a set of tutorials for the CMS Machine Learning Data Analysis School (DAS) Short Exercise. They are intended to show you how to build machine learning models in python (`Keras`/`TensorFlow`) and use them in your `ROOT`-based analyses. We will build event-level classifiers for differentiating VBF Higgs and standard model background 4 muon events and jet-level classifiers for differentiating boosted W boson jets from QCD jets.

## Main notebooks in this tutorial

 0. [`0-setup-libraries.ipynb`](0-setup-libraries.ipynb): setting up libraries using `CMSSW`
 1. [`1.1-datasets-uproot.ipynb`](1-datasets.ipynb): reading/writing datasets from `ROOT` files with `uproot`
 2. [`2-plotting.ipynb`](2-plotting.ipynb): plotting with `pyROOT` and `matplotlib`
 3. [`3-dense.ipynb`](3-dense.ipynb): building, training, and evaluating a fully connected (dense) neural network in `Keras`
 4. [`4-preprocessing.ipynb`](4-preprocessing.ipynb): preprocessing CMS open data to build jet-images (optional)
 5. [`5-conv2d.ipynb`](5-conv2d.ipynb): building, training, and evaluating a 2D convolutional neural network in `Keras`

## Setup

We will be using the Vanderbilt JupyterHub. Point your browser to:

[https://jupyter.accre.vanderbilt.edu/](https://jupyter.accre.vanderbilt.edu/)

If this is the first time using this JupyterHub, you should see:

<p align="center">
  <img src="vanderbilt.png" width="500"/>
</p>

Click the "Sign in with Jupyter ACCRE" button. On the following page, select CERN as your identity provider and click the "Log On" button. Then, enter your CERN credentials or use your CERN grid certificate to autheticate. Select a "Default ACCRE Image v5" image and then select either 1 core/2 GB or memory or 8 cores/8GB memory. Unless you are unable to spawn a server, we recommend using the 8 core/8GB memory servers as notebooks *4* and *5* require a lot of memory. Once you've selected the appropriate options, click "Spawn".

Now you should see the JupyterHub home directory. Click on "New" then "Terminal" in the top right to launch a new terminal. 

<p align="center">
  <img src="new_terminal.png" width="200"/>
</p>

To download the tutorials, type

```
git clone https://github.com/FNALLPC/machine-learning-das
```

Now, in your directory tab, there should be a new directory called `machine-learning-das`. All of the tutorials and exercises are in there. Start by clicking on [`0-setup-libraries.ipynb`](0-setup-libraries.ipynb) and running it.

## Links

The indico page is: [https://indico.cern.ch/e/cmsdas2021](https://indico.cern.ch/e/cmsdas2021)

The Mattermost for live support is: [https://mattermost.web.cern.ch/cmsdaslpc2021/channels/shortexercisemachinelearning](https://mattermost.web.cern.ch/cmsdaslpc2021/channels/shortexercisemachinelearning)

The twiki is: [https://twiki.cern.ch/twiki/bin/view/CMS/SWGuideCMSDataAnalysisSchoolLPC2021MachineLearningShortExercise](https://twiki.cern.ch/twiki/bin/view/CMS/SWGuideCMSDataAnalysisSchoolLPC2021MachineLearningShortExercise)
