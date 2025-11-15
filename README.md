# Sustainbility-Waste-Classification

# LEARNING OBJECTIVE
In this project, I developed a Smart Waste Classification system using deep learning models VGG16 and ResNet50. The models were trained on an augmented dataset to classify different types of waste efficiently, promoting smarter recycling solutions. 
# Problem Statement
The problem is preety much stright forward, we all are famelier with Garbage and waste material which is very harmful for our society.If we talk about amount of waste then the world almost generates at least 5 million tons of waste per day and this number is still increasing day by day that's why we need to aware about waste. This model which help us to classify waste with 7 different waste materials and it will show you the details of that particular waste materials. This will help to raise awareness for people to reduce and recycle waste.
# Overview

*There are 'cardboard', 'compost', 'glass', 'metal', 'paper', 'plastic', 'trash' total 7 different types of waste materials which are use for recycling.

*Here i have 2187 images belonging 7 classes.

*Here i have trained dataset using VGG16,RESNET50 model via using Transfer Learning technique of CNN for classification.

*Here i have trained this model till 5 epochs and i got 41.31% accuracy on training data and 43% on testing data. Since my computer can not aford more epochs at this time due unavailbility of GPU. if you have good ammount of gpu you can train more than 50 epochs if you want to improve ac curacy.

# Introduction of Tranfer Learning and Fine Tuning
![67788](https://github.com/user-attachments/assets/b15bf00f-e2a1-44c9-b5ca-3cbac080687e)
![8098](https://github.com/user-attachments/assets/2200ab39-9046-4910-80d3-efa276207a52)

# VGG16 Architeture using Tranfer Learning

# Loss Plot of VGG16
<img width="372" height="248" alt="LossVal_loss" src="https://github.com/user-attachments/assets/f2199f1a-1a37-4027-bdbe-c0b35b699c5c" />

# Accuracies Plot of VGG16
<img width="378" height="248" alt="AccVal_acc" src="https://github.com/user-attachments/assets/03957b9a-d847-47ed-a679-16357ad6db50" />

# ResNet50 Architeture using Tranfer Learning

# Loss Plot of ResNet50
<img width="372" height="248" alt="ResNet_Loss" src="https://github.com/user-attachments/assets/5c5fe06d-438a-41c6-b8b7-0c477108c32d" />

# Accuracies Plot of ResNet50

<img width="378" height="248" alt="ResNet50_Accuracy" src="https://github.com/user-attachments/assets/f929fc23-bc47-4d62-8f6c-c1694d48d19a" />

# Improve VGG-16 using Tranfer Learning

# Loss and Acuuracy Plot of VGG-16 with TF

<img width="1153" height="482" alt="train_TF" src="https://github.com/user-attachments/assets/2abb2d6d-42f6-4cf2-adab-cd8c7a9c0b9b" />

# Improve VGG-16 using Fine Tuning

# Loss and Acuuracy Plot of VGG-16 with FT

<img width="1155" height="482" alt="FT" src="https://github.com/user-attachments/assets/473ec00f-9804-49a8-ad64-8e7151fef2c9" />

# Evaluation Matrix of VGG16 and ResNet50 Model
<table>
  <thead>
    <tr>
      <th>Model Name</th>
      <th>Test Accuracy</th>
      <th>Epochs</th>
      <th>For improve accuracy</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>VGG-16 with TL</td>
      <td>43.03%</td>
      <td>5</td>
      <td>Set 100 Epochs</td>
    </tr>
    <tr>
      <td>ResNet-50 with TL</td>
      <td>29.78%</td>
      <td>5</td>
      <td>Set 100 Epochs</td>
    </tr>
    <tr>
      <td>Improvement of VGG-16 with TL</td>
      <td>72.5%</td>
      <td>20</td>
      <td>Tune more HT</td>
    </tr>
    <tr>
      <td>Improvement of VGG-16 with TL+FT</td>
      <td>80.8%</td>
      <td>25</td>
      <td>Tune more HT</td>
    </tr>
  </tbody>
</table>



