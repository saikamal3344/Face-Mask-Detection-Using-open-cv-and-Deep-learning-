# Face-Mask-Detection-Using-open-cv-and-Deep-learning-



The novel COVID-19 virus has forced us all to rethink how we live our everyday lives while keeping ourselves and others safe. Face masks have emerged as a simple and effective strategy for reducing the virus’s threat and also, there is no efficient face mask detection applications which are now in high demand for transportation means, densely populated areas, residential districts, large-scale manufacturers and other enterprises to ensure safety. Therefore, the goal of the project is to develop face mask detector using deep learning.



Dependencies :


Deep Learning based Face-Mask-Detector architecture uses OpenCV (opencv==4.2.0) and Python (python==3.7). The model Convolution Neural Network(CNN) uses Keras (keras==2.3.1) on Tensorflow (tensorflow>=1.15.2). For face detection in images it uses caffe based model. Also, imutils==0.5.3, numpy==1.18.2, matplotlib==3.2.1, argparse==1.1 are also used.

How to execute code:

You will first have to download the repository and then extract the contents into a folder.
Make sure you have the correct version of Python installed on your machine. This code runs on Python 3.6 above.
Now, run the following command in your Terminal/Command Prompt to install the libraries required
pip install requirements.txt

Now, you can download the dataset from here and put it in the current folder. The images used in the dataset are real images of people wearing mask i.e. tha dataset doesn't contains morphed masked images. The model is accurately trained and, also the system can therefore be used in real-time applications which require face-mask detection.
You also need caffe based face detector model for face detection and it is inside face_detection folder.
Training of CNN Model : Open terminal. Go into the project directory folder and type the following command:
python train.py --dataset dataset

Testing of CNN Model : You can download the pretrained model from here for inference.
For detecting face mask in images, run the following command :

python Mask_Detection_in_Image.py --image data/image1.jpg

For detecting face mask in real-time video stream, run the following command :

python Mask_Detection_in_Video.py




