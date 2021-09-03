# Face-Mask-Detection-COVID-Deep-Learning-Project

	In the current covid crisis, we all know how important it is to have a mask on, especially in the public places. We have seen in most of public places there is always human resource used to check if the people are wearing a mask or not.
It’s not ideal for a person to work round the clock, humans can get tired or over a period of time there efficiency can be down.

#Our Approach
	In order to overcome this very situation, we have come up with a face mask detection, ML model which detects weather a person has worn a mask or not

	The model is trained using tensorflow, with a dataset of over 1900 images of people with and without mask.
	While training each of image is augmented to different angle of rotation, different view points, hence increasing the accuracy of the model when tested.
	Collected the dataset from various open source websites like Kaggle.
	Facial landmarks allow us to automatically infer the location of facial structures, including:Eyes, Eyebrows, Nose, Mouth, Jawline. To use facial landmarks to build a dataset of faces wearing face masks, we need to first start with an image of a person not wearing a face mask.

#Machine Learning Libraries we Used 

>TensorFlow – For training and forming Convolutional Neural Net Structure 
>Keras – Deep Learning Python Library integrated into TensorFlow
>Imultis –  Working With Images
>Numpy – Scientific Computing in Python , For working with Pixel Matrices as 			      in Images
>OpenCV – For detecting Facial Structures like Eyes, Nose , Eyebrows , Lips, 				Smile etc.
>MatPlot – Plotting Graph for Loss and Accuracy Percentages in the given 					detection for Mask and No Mask Conditions 
>Scipy – Data Preprocessing from Convolutional Neural Network Layers

##Ultimately we were able to get an accuracy of about 86% using 10 epoches and
98% using 20 epoches/itterations over masked and non-masked Dataset !

###Thank You .
