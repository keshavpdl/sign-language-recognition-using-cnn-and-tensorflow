# sign-language-recognition-using-cnn-and-tensorflow

Software Specification
Here are the basic software you need to know about:

Tensorflow

Opencv

Numpy

Process Explanation:

The first thing I did was, I created 28 gesture samples using OpenCV. For each gesture I captured 1000 images which were 50x50 pixels. All theses images were in grayscale which is stored in the gestures/ folder. The pictures were flipped using flip_images.py.
Before running this project you should have basic knowlede about OpenCV, Tensorflow, and Numpy is and how it works.
Created a CNN which look a lot similar to this MNIST classifying model using Tensorflow. If you want to add more gestures you might need to add your own layers and also tweak some parameters, that you have to do on your own.
Then used the model which was trained using Tesorflow on a video stream.
As of today, I have stored the 28 gestures for which are 26 alphabets of American Sign language and 1 for hello and 1 for namastey. And trained the model on these images.

How To Run:

After downloading the repository, first run img_cap.py to add/capture gesture.
Then make changes in the dataset.py file in the clasess line, and run dataset.py to create train_data.npy.
Now run the train.py, which will train the data with the use of cnn_sgn.py in your PC.
After training the data, finally run the output.py, which will open the window for gesture recognition.
Thank You
