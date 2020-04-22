# A Tutorial on Adversarial Robustness

This repo contains a short tutorial on Adversarial Robustness in `PyTorch` that I wrote to teach a class on the topic in Spring, 2020. 

## Dependencies

To run this notebook, you will need:
1. Numpy
2. PyTorch
3. Matplotlib
4. PIL

To install them, run the following command from within your environment:

`pip install numpy torch torch-vision matlplotlib Pillow`

## File Organization

In this repo you will find a test image of a cat - `cat.jpg`, the notebook itself, and four model checkpoint objects, included in case you are unable to train the models in the notebook locally. 

## Running on Google Colab
The notebook is can be readily run in Google Colab, but you will need to upload the `json` file (for class labels) and the test image in the sidepane. You can also upload the checkpoint files to avoid training. Bear in mind that these will be cleared if your session expires, and you will have to upload them again. 

## Acknowledgement

This tutorial is a watered down version of the excellent chapter-wise explanations by Zico Kolter and Aleksander Madry at this [link](https://adversarial-ml-tutorial.org/). I've taken the liberty to pick and choose code snippets to form a more concise and quick tutorial. Therefore, this tutorial serves as a quick introduction to adversarial examples and training to those familiar with optimization theory. For a comprehensive dive into the topic, their chapters provide greater detail and mathematical rigor. 
