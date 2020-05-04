# BSCS17001_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.

Task1
using pretrained model but changed FC layer

Vgg16  
1. Lr=0.00001, momentum=0.5
 
Test Data analysis

Test accuracy 92%
 
Accuracy of validation data after fine tuning of FC layers: 88%

Accuracy of training data after fine tuning of FC layers: 85%

2. lr=0.000001, momentum=0.9

Test Data analysis

Test accuracy=92%
 
Accuracy of validation data after fine tuning of FC layers: 86%

Accuracy of training data after fine tuning of FC layers: 83%


3. lr=0.0001, momentum=0.9 (Best model)

Test Data analysis 

Test Accuracy=94%

Accuracy of validation data after fine tuning of FC layers: 96%

Accuracy of Training data after fine tuning of FC layers: 89%
...
...

Resnet18

lr=0.00001, momentum=0.9

Test Accuracy = 83%

Accuracy of validation data after fine tuning of FC layers: 81%

Accuracy of Training data after fine tuning of FC layers: 78%
 

Task2 

Vgg16
 lr=0.0001, momentum=0.9
test accuracy: 94%

 
ResNet18
1. lr=0.000001, momentum=0.7

Test accuracy=62%

Accuracy of validation data after fine tuning of FC layers: 62%
 

2. Lr=0.00001, momentum=0.9

Test Accuracy after fine tuning of FC layers: 91%

Accuracy of training data after fine tuning of FC layers: 88%

Accuracy of training data after fine tuning of FC layers: 86%


Final comments
Task2 is better because the task 1 model had been trained for image net but in task 2 we allow the model to train for our dataset. Results get better as we unfreeze our layers because the layers at start are more responsible for edges and corners which are more important in our case.

