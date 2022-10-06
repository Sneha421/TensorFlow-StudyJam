## Basic Details
* The MNIST Dataset is imported from Keras
```
from tensorflow.keras.datasets import mnist
(x_train,y_train),(x_test,y_test) = mnist.load_data()
```
* It has 60000 train images and 10000 train images
* Each image is of the size 28x28 pixels
* The images are handwritten digits represented as 2D Matrices

## Model Architecture Details
* Input - A 2D Array represented a handwritten digit
* Output - A 1x10 array as there are 10 classes (digits from 0 to 9)
* The highest probability in the output array is taken as the output label<br />

![image](https://user-images.githubusercontent.com/57147597/194360095-4463cb1f-ac89-4f93-a78d-8edf661c76ed.png)<br />
_This is the representation of the created model_

## Results
This model runs with a maximum accuracy of **92.5%**

## Steps to run the Gradio GUI
1. Open the ***Tensorflow_Study_Jam_1.ipynb*** file and run all the cells
2. The final cell will continue running forver and the following interface will be displayed

![image](https://user-images.githubusercontent.com/57147597/194361215-5e71f79a-f819-498e-b21f-651705149fb8.png)<br />

3. Draw any digit in the box and hit submit. The label will be displayed beside it
![image](https://user-images.githubusercontent.com/57147597/194362344-68866d45-4084-4f12-9bf0-6eee7ea9b97a.png)<br />


**NOTE**: There may be errors in labelling as this is an image processing problem that has been solved using MLP instead of CNN

