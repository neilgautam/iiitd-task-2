# iiitd-tasks
This repository contains solutions to task 2 provided by IIIT Delhi 

## FrameWork Used
**Tensorflow 2.4.0**

### Experimentations And Analysis

**Part 1** 

*Trained NeilClassifierModel on 62 classes on provided dataset and achieved 83-87% validation accuracy on 10% validation split*

*NeilClassifierModel consists of almost 90,000 parameters, and has been designed using after performing several experiments.*

*This model may achieve better accuracy if the dataset size is increased.*

*While deciding the model parameters, we observed that BatchNormalisation helps in the training time and helps to converge faster, along with that dropout came out to be really necessary because when training without dropout the difference between validation and training accuracy was greater than 10% after 70% training accurcay.*

**Part 2** 

*In this Part of Task 2 we perform several analysis and observe the difference in training time between pretrained network and network with random weights.*

*The Pretrained models which has been used for experimentations are MobileNet, ResNet and VGG16 and also NeilClassifierModel (Trained on CustomDataset with 0-9 Classes)*

**Part 3**

*In this part while plotting the data before training the model on it **, we observe that each folder of certain class contains data from other classes also which hinders the training of model***

*The accuracy achieved during training on this dataset does not yield accuracy more than 10%.*
