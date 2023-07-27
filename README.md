# Anomaly-Detection-using-Resnet-34-
**Anomaly detection and anomaly type classification using customized pre-trained Resnet-34 Deep Learning Model**

Detecting the Anomaly(Defected part) in a dataset of 15 different classes using the concept of transfer learning  with a pre-trained Resnet-34 model along with an additional classification head to get the bounding boxes of the defected area of each anomaly class object image. I have used the individual subclass datasets of each object to train and validate the customized model and then got predictions using the unseen test dataset. Further details are given in the self-explanatory notebook.  

**Dataset**

The Dataset contains images of 15 different subclasses of objects with 'good' and 'Anomaly' types of images. these images are classified into good and anomaly class labels and the predicted anomaly class labeled image is used to predict the defective part of that image highlighted with a bounding box. The dataset can be retrieved using the link given below:

https://www.mvtec.com/company/research/datasets/mvtec-ad

Feel free to suggest any improvements:)
