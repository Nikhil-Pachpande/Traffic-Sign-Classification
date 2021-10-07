# Traffic-Sign-Classification
This is a small project of multi-class image classification.<br><br>
The dataset used here is the "German Traffic Sign Recognition Benchmark" Dataset from Kaggle and can be found at https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign.<br>
The dataset contains more than 50000 images of various traffic signs which are classified into 43 classes.<br><br>
The packages used to develop this project are tensorflow, keras, sklearn, matplotlib, pandas, PIL and tkinter.<br><br>
The CNN model is used for the classification of the images. The architecture of the model and its layers can be found in "traffic-sign-classifier.ipynb" file.<br><br>
The accuracy achieved after training 15 epochs with batch_size of 64 on the training data is 97%.<br><br>
The trained model can be found as the "traffic-sign-classifier.h5" file.<br><br>

The Training Result:<br>
![training result](training.JPG)<br><br>
Training_Accuracy vs Validation_Accuracy & Training_Loss vs Validation_Loss is plotted and can be visualized as:<br>
![result](plot.JPG)<br><br>
GUI Screenshots:<br>
The GUI before uploading the image:<br>
![gui-1](gui-1.JPG)<br><br>
The GUI after uploading the image:<br>
![gui-2](gui-2.JPG)<br><br>
Classification:<br>
![gui-1](gui-1.JPG)<br><br>
