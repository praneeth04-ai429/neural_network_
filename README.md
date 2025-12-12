# Visualizing What Convolutional Neural Networks Learn: Feature Maps & Filters

**Author:** Praneeth Kumar Chapalabandla


## Overview
This repository contains the complete tutorial, code, and accompanying materials for the project:
**"Visualizing What Convolutional Neural Networks Learn: Feature Maps & Filters."**

The objective of this tutorial is to teach how Convolutional Neural Networks (CNNs) learn hierarchical visual representations.  
Using a simple CNN trained on the Fashion-MNIST dataset, we visualize:
- Convolutional filters
- Intermediate feature maps
- How deeper layers extract increasingly abstract structures

---

## Contents
├── CNN_tutorial.pdf
├── neural_network.ipynb
├── requirements.txt
├── LICENSE
├── README.md
└── figs/
├── training_loss.png
├── training_accuracy.png
├── filters_conv1.png
├── featuremaps_conv1.png
├── featuremaps_conv2.png


---

## Tutorial Document
The tutorial includes:
- Title & author information  
- Abstract  
- Learning objectives  
- Introduction to CNN feature learning  
- Dataset description  
- Model architecture  
- Training behaviour  
- Placeholders for all figures  
- Interpretation of filters and feature maps  
- Accessibility & ethical considerations  
- References  

All images referenced in the tutorial are produced by `neural_network.ipynb` and saved under the `figs/` directory.

---

## How to Run the Notebook

### 1. Install dependencies
pip install -r requirements.txt

### 2. Run the notebook
neural_network.ipynb

This will train the CNN and generate all required figures automatically.


### Figures Generated

The notebook produces:
	•	training_loss.png — Loss curve
	•	training_accuracy.png — Accuracy curve
	•	filters_conv1.png — Visualized filters of first convolutional layer
	•	featuremaps_conv1.png — 1st-layer activation feature maps
	•	featuremaps_conv2.png — 2nd-layer activation feature maps


### Ethical Considerations

Although Fashion-MNIST is a benign dataset, this tutorial addresses interpretability in CNNs, which helps identify model bias and behaviour in real-world applications.
Transparency and ethical AI practices are emphasized in the tutorial.


### References
	1.	LeCun, Y., Bottou, L., Bengio, Y., & Haffner, P. (1998). Gradient-based learning applied to document recognition.
	2.	Goodfellow, I., Bengio, Y., & Courville, A. Deep Learning. MIT Press.
	3.	Dumoulin, V., & Visin, F. A guide to convolution arithmetic for deep learning.
	4.	PyTorch Documentation: https://pytorch.org/docs/stable/
	5.	Fashion-MNIST Dataset: https://github.com/zalandoresearch/fashion-mnist


### License

This project is licensed under the MIT License (see LICENSE file).


