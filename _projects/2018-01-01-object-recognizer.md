---
layout: project
title: "E-Commerce Object Recognizer"
date: 2018-01-01
---

E-Commerce Object Recognizer

[Jekyll](https://github.com/s-bhatt/upload)

A web service which helps people find the name of the products by just taking a photo with their cell phone.

The tools used were:
YOLO - Real Time Object Detection
TensorFlow For Poets
Flask and Python Libs
Web Driver

The object with highest accuracy is detected and extracted and cropped from the image.
This cropped image is now a input to the classifier that we trained.
The classifier then predicts the brand of the image.
We used a pre-trained model from image-net and we retrained the classification layer of our model to predict and classify a few brands that we had to train.
We used the Python Flask framework as a web server.

Future work
Improve training using a bigger dataset and.
Do real time video object detection and predictiction on the camera.
That would definitely require better resources (GPUs) , or better system.
If the prediction is super accurate the the web crawling could be automated and price
comparison could be integrated to our system.

We used google photos to download photos of our products.
We also captured videos of our products and used ffmpeg tool
Ffmpeg tool converts videos to jpg images