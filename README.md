# Fashion-class-classification-Python
How to Develop a Deep CNN for Fashion-MNIST Clothing Classification by Jason Brownlee on May 10, 2019 in Deep Learning for Computer Vision Tweet  Share Last Updated on October 3, 2019  The Fashion-MNIST clothing classification problem is a new standard dataset used in computer vision and deep learning.  Although the dataset is relatively simple, it can be used as the basis for learning and practicing how to develop, evaluate, and use deep convolutional neural networks for image classification from scratch. This includes how to develop a robust test harness for estimating the performance of the model, how to explore improvements to the model, and how to save the model and later load it to make predictions on new data.  In this tutorial, you will discover how to develop a convolutional neural network for clothing classification from scratch.  After completing this tutorial, you will know:  How to develop a test harness to develop a robust evaluation of a model and establish a baseline of performance for a classification task. How to explore extensions to a baseline model to improve learning and model capacity. How to develop a finalized model, evaluate the performance of the final model, and use it to make predictions on new images. Discover how to build models for photo classification, object detection, face recognition, and more in my new computer vision book, with 30 step-by-step tutorials and full source code.  Let’s get started.  Update Jun/2019: Fixed minor bug where the model was defined outside of the CV loop. Updated results (thanks Aditya). Updated Oct/2019: Updated for Keras 2.3 and TensorFlow 2.0. How to Develop a Deep Convolutional Neural Network From Scratch for Fashion MNIST Clothing Classification How to Develop a Deep Convolutional Neural Network From Scratch for Fashion MNIST Clothing Classification Photo by Zdrovit Skurcz, some rights reserved.  Tutorial Overview This tutorial is divided into five parts; they are:  Fashion MNIST Clothing Classification Model Evaluation Methodology How to Develop a Baseline Model How to Develop an Improved Model How to Finalize the Model and Make Predictions Want Results with Deep Learning for Computer Vision? Take my free 7-day email crash course now (with sample code).  Click to sign-up and also get a free PDF Ebook version of the course.  Download Your FREE Mini-Course Fashion MNIST Clothing Classification The Fashion-MNIST dataset is proposed as a more challenging replacement dataset for the MNIST dataset.  It is a dataset comprised of 60,000 small square 28×28 pixel grayscale images of items of 10 types of clothing, such as shoes, t-shirts, dresses, and more. The mapping of all 0-9 integers to class labels is listed below.  0: T-shirt/top 1: Trouser 2: Pullover 3: Dress 4: Coat 5: Sandal 6: Shirt 7: Sneaker 8: Bag 9: Ankle boot It is a more challenging classification problem than MNIST and top results are achieved by deep learning convolutional neural networks with a classification accuracy of about 90% to 95% on the hold out test dataset.
http://yann.lecun.com/exdb/mnist/ - Dataset