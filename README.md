The work I developed in this project was to train a neural network so that when it receives an x-ray of a lung, 
it can determine whether the person in question has COVID-19, with a 90% accuracy rate. For this, 4 different 
categories of images were used with 133 photos each, the categories were photos of people with COVID-19, 
normal people, with Viral Pneumonia and with Bacterial Pneumonia. After training the neural network with 
25 epochs (it took more than two hours), a trained database was established that, when it wants to predict 
which category a new x-ray image is in, it will be able to do so. In this context, a convolutional neural 
network architecture called ResNet was used to improve image analysis and transfer learning to add data 
for this project problem.

When thinking about the applications of Artificial Intelligence in the area of Medicine, the use of neural 
networks can contribute to this objective. Neural Networks is a field of knowledge that seeks to understand 
how human beings think, trying to analyze at a data level how the brain system works; When considering how 
neurons work and how they transmit information, the area of computing tries to modulate this way of 
processing information through the structure of neural networks. In this case, as images needed to 
be processed, a convolutional neural network architecture called ResNet was used. It is already a database 
trained by images from ImageNet with 11 million images. Basically, it already has layers of neurons 
(kernels/feature detectors) grouped into sets (convolutional layer) with 175 layers in this architecture used.

Regarding the process, it was necessary to receive x-ray images of the lung as data input, which, when 
processed by the neural network, could classify the person analyzed as having COVID-19, without illnesses 
such as Viral Pneumonia or Bacterial Pneumonia. . After training, it was verified through a confusion 
matrix that the neural network was showing good results only when treating images of COVID-19 and those 
of normal people, so this learning deals with the presentation of these two sets. It is taken into 
account that this project was an exercise in Neural Networks, but the accuracy of the results can be 
significantly higher if efforts are directed to increasing the training database, increasing the 
learning times, increasing the number of neurons(kernels).
