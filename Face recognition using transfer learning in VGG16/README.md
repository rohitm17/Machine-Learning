![Face Recognition](https://github.com/rohitm17/Machine-Learning/blob/master/Face%20recognition%20using%20transfer%20learning%20in%20VGG16/fr.jpg)
<h1>Face Recognition using Transfer Learning on VGG16 </h1>

  What is transfer learning?

  According to Wikipedia, Transfer learning is a research problem in machine learning that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem. For example, the knowledge gained while learning to recognize cars could apply when trying to recognize trucks.
  
  Why use Transfer Learning?

  In today's digital world there is a huge amount of data, commonly known as Big Data.

  In the data science world, we face a lot of situation which require a lot of computational power or resources like RAM, CPU or GPU, etc. to train our models. To cope up with this situation one of the best ways is to use the pre-trained model as in Transfer Learning. This will also help to achieve more accuracy with less amount of data.
    
  ![transfer Learning](https://github.com/rohitm17/Machine-Learning/blob/master/Face%20recognition%20using%20transfer%20learning%20in%20VGG16/tl.png)  
  What is VGG16?
  
  VGG16 is a convolutional neural network model proposed by K. Simonyan and A. Zisserman from the University of Oxford in the paper “Very Deep Convolutional Networks for Large-Scale Image Recognition”. The model achieves 92.7% top-5 test accuracy in ImageNet, which is a dataset of over 14 million images belonging to 1000 classes. It was one of the famous models submitted to ILSVRC-2014. It makes the improvement over AlexNet by replacing large kernel-sized filters (11 and 5 in the first and second convolutional layer, respectively) with multiple 3×3 kernel-sized filters one after another. VGG16 was trained for weeks and was using NVIDIA Titan Black GPUs.
  
  Face Detection and Face Recognition

  Face Detection: It is an (AI) based computer technology used to find and identify human faces in digital images or videos. It now plays an important role as the first step in many key applications including face tracking, face analysis, and facial recognition.

  Face recognition: It is a method of identifying or verifying the identity of an individual using their face.

  Our Task: To create a Face Recognition model using a pre-trained Deep Learning model VGG16.

  Let's break our task into sub-tasks:

   1.Generation of data using Open CV for face extraction for the training part of the model.

  2. After Extraction of the faces divide our whole data generated in the form of images into two parts 1.) Training Part 2.) Testing Part

  3. In the next step, we will use a pre-trained Deep Learning Model called VGG16 to recognize the faces.
  
![vgg16](https://github.com/rohitm17/Machine-Learning/blob/master/Face%20recognition%20using%20transfer%20learning%20in%20VGG16/vgg16.png)  
  
