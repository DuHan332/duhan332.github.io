---
title: "Optical Character Recognition"
collection: projects
type: "C Project"
permalink: /projects/project3
---

A projects that use neural network to train a model for optical character recognition (OCR).

Description
------
This project trains a multi-layer neural network that converts hand-written text to electronic format, which is known as optical character recognition (OCR). In this project, I assume that training characters have already been cut and shrunk to a uniform size(28x28 pixels), and each of them is associated with a label that indicats which character it is.

Features
------
* Different network layouts and activation functions could be applied to compare how different neural networks perform.

* Produce false-negative and false-positive images of result that could be used to visually evaluate and debug model.

  ![ocr_data](/images/ocr_data.png)

* Produce image of trained model by showing weight on each pixel that could be used to visually evaluate and debug model.

  ![ocr_weights](/images/ocr_weights.png)

(Example for number characters 1-9 is shown)

[Github](https://github.com/DuHan332/Optical-Character-Recognition)
