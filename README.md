Face Mask Detection System

Our Face Mask Detection system built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision.


INTRODUCTION 

The world is struggling with Covid-19 pandemic and are so many essential equipment’s needed to combat against Corona virus. One of such most essential is Face Mask and mask was not mandatory for everyone but as the day surpasses scientist and Doctors have recommended everyone to wear the mask. 
Therefore, to detect whether a person is wearing Face Mask or not, there are detection technique. Face Mask Detection Platform utilizes Artificial Network to identify if a person does/doesn’t wear a mask. The application can be associated with any current or new IP cameras to identify individuals with/without a mask. 


WORKING PRINCIPLE 

Our Face Mask Detection system built with OpenCV, Keras/TensorFlow using Deep Learning 
and Computer Vision concepts. We can detect face masks in Static Images as well as in Real-time 
Video streams. 
A data set is a collection of data. In Deep Learning projects, we need a training data set. It is the 
actual data set used to train the model for performing various actions. A collection of instances is a 
dataset and when working with machine learning methods we typically need two datasets for different 
purposes. 
- Training Dataset: A dataset that we feed into our Deep learning algorithm to train our model. 
- Testing Dataset: A dataset that we use to validate the accuracy of our model but is not used to 
                    train the model. It may be called the validation dataset. 

Our dataset consists of 3835 images belonging to two classes:
- with_mask: 1916 images 
- without_mask: 1919 images 


INSTALLATION

1. Clone the repo

      $ git clone https://github.com/chandrikadeb7/Face-Mask-Detection.git

2. Now, run the following command in your Terminal/Command Prompt to install the
libraries required

      $ pip3 install -r requirements.txt


WORKING

1. Open terminal. Go into the cloned project directory folder and type the following
command:

    $ python3 train_mask_detector.py --dataset dataset

2. Now detect the face masks in images

    $ python3 detect_mask_image.py --image images/pic1.jpeg

3. Detection in real-time video streams

    $ python3 detect_mask_video.py


CREDIT

https://www.pyimagesearch.com/                                        
