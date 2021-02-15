# Image Recognition of Cats & Dogs
![alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQKtaZT__QsYeAjQprIzzDMZAPgNb4YZOoXpA&usqp=CAU)


## Overview
This project was originally used as a CAPTCHA (or Completely Automated Public Turing test to tell Computers and Humans Apart), that is, a task that it is believed a human finds trivial, but cannot be solved by a machine, used on websites to distinguish between human users and bots. Specifically, the task was referred to as “Asirra” or Animal Species Image Recognition for Restricting Access, a type of CAPTCHA. The task was described in the 2007 paper titled “Asirra: A CAPTCHA that Exploits Interest-Aligned Manual Image Categorization“.

## The dataset
The dogs vs cats dataset refers to a dataset used for a Kaggle machine learning competition held in 2013.

The dataset is comprised of photos of dogs and cats provided as a subset of photos from a much larger dataset of 3 million manually annotated photos. The dataset was developed as a partnership between Petfinder.com and Microsoft.

## Project Detail
The ultimate goal of this project is to create a system that can detect cats and dogs. While our goal is very specific (cats vs dogs), ImageClassifier can detect anything that is tangible with an adequate dataset. For this project, I have used Convolutional Neural Networks(CNNs). CNNs are deep learning models suited for analyzing visual imagery. They are heavily influenced by how we - humans, see the surrounding world.

## Convolutional Neural Networks
For a computer, an image is just an array of values. Typically it’s a 3-dimensional (RGB) matrix of pixel values.
For example, a 6x6 RGB abstract image representation would look like this.

![alt text](https://miro.medium.com/max/231/1*9TbWVXICJaXxUsCzg1wrDQ.png)

Where each pixel has a specific value of red, green and blue that represents the color of a given pixel.
But this is just an input to the visual recognition system.
How can a computer make any sense out of it in a similar fashion that we are able to do it?
CNN processes images using matrixes of weights called filters (features) that detect specific attributes such as vertical edges, horizontal edges, etc. Moreover, as the image progresses through each layer, the filters are able to recognize more complex attributes. Ultimate goal of the CNN is to detect what is going on in the scene.

## Technologies Used
![](https://twilio-cms-prod.s3.amazonaws.com/original_images/jupyter_python_numpy.png)
![](https://i.redd.it/c6h7rok9c2v31.jpg)
![](https://lh3.googleusercontent.com/proxy/mbo775as_XCQggBwnQo-gTzxkM7LhSG3e2xVgUkvJdsUCG0f56soMA84xWAlW2OlmbIWVENloF6fpUem3Ijh-hip0LhO1XElZIgrVygUanVrhVg4FFLl117k3X8dlYU2ZTXr6kAyrVKoVw3prrej02Ki6JoblEEF0J3HyqiKoD1LhN-eeVwUg5myV-W5x6xYHhvlsPKKVuZuvHmegKPItmJB_t7o0ZdUgJS-siKQ15eCNSn57oUx03M-C73uLXNob80LzpfvQxFsoHSdJH47kiKNi6wwOm4nSiZRrH0g_Hb44iSJYZvjTyyX9uyQk3orV2WapeIk1CvWCZuBaRyFkwUp)

