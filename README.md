# peexle

# Introduction

This is an application based on android platform, to get the flavour of artificial intelligence in the world of art. There is lot of research going on this area & lots of 
Paper published. This is basically the implementation of “A neural algorithm of artistic style” which uses “Generative Adversarial Neural Network” to generate the images with 
Mixed style of given input. check my [blog](https://medium.com/@kaleajit27/ive-been-waiting-to-do-this-for-very-long-time-6813ee5e091) on this for further understanding.

# Goals achieved
Goals of this attempt was to create the application for real-time video & image style 
Transfer.

  But, we only manage to apply it on images, which is not real-time but gives smooth
Processed images
# Demo
 https://www.youtube.com/watch?v=qtmmXNjGEYI
 
# Installation
 1. Provided .apk file to directly install in android phone(pass: monademry, if ask any)
 2. To build & run the code import android folder in android studio & then run it

# Compatibility
 1. Supports Android 5.0 and above (better performance in nougat & above)
 2. Google api 25 & above
 
# Techniques Applied
 1. Renderscript framework developed by android to run computationally intensive task.
 2. Convolutional Neural Network to implement the artistic style transfer method using renderscript & its java api
 3. Android studio interface to integrate this all with gui
 
 # References
 1. https://github.com/mtmd/Mobile_ConvNet 
 2. Google android developer renderscript documentation
           https://developer.android.com/guide/topics/renderscript/compute.html
 3. https://github.com/hwalsuklee/tensorflow-style-transfer
 4. https://arxiv.org/abs/1508.06576
