---
layout: post
title: Smart Segmentation of Microstructural Features using Deep Learning
date: 2019-12-30 13:32:20 +0300
# Add post description (optional)
img: 1990seg.png # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: 
---

### Skills Learnt

* Neural network design.
* Training the CNN for image classification, and implementing the classifier on a test dataset
* Python

### Libraries 

* Keras
* Scikit-Learn
* OpenCV



### Summary of the Results: 

* Design of the pipeline:

<img src = "{{site.url}}/assets/images/pipeline2.png" hspace="80" height="450" width="550" />

* Best accuracy achieved during classification: 94.07%

* Image processing to extract morphological data:

<img src = "{{site.url}}/assets/images/1990seg.png" hspace="50" align="middle" height="300" width="300" />
<img src = "{{site.url}}/assets/images/433seg.png" align="middle" height="280" width="280" />


### Detailed description: 

* One of the goals of Materials Informatics (generally) and Image Driven Machine Learning (specifically) is extraction of quantitative data from micrographs towards an efficient characterization of microstructural features. A two stage pipeline consisting of a classification step and a segmentation step is used to process titanium microstructures containing a wide range of morphological features and output quantitative measurements relevant to the particular class of microstructure identified.


* For the classification step, a Convolutional Neural Network is trained using TensorFlow, with the architecture consisting of three convolutional layers and one fully connected layer. The microstructures are classified into three labels: “lamellar”, “duplex”, and “acicular”.

* A material microstructure dataset of 1225 images is established, comprised of Ti-6Al-4V alloy micrographs acquired from seven different thermal processing conditions. The CNN was trained on a dataset of 1000 images and subsequently tested on a dataset of 225 images. It reported an accuracy of 93.00 ± 1.16 %, averaged over 5 trials incorporating a random division of the total dataset into training and test sets.  

* For the second stage of the pipeline, image processing techniques were selected specific to the classification label of
the micrograph. The area fraction of equiaxed grains is extracted from bi-modal microstructures using a marker-based watershed technique, and the area fraction of the dominant α-variant is extracted from basket-weave structures using a Histogram of Oriented Gradients (HOG) method. Computational tools similar to the proof of concept pipeline demonstrated in this work can be used by engineers to better identify microstructural features that arise due to process or material variations.






