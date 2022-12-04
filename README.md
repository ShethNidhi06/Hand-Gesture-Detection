# Hand-Gesture-Detection
A CNN model used to guess hand gestures 

## Aim: 
Detect the right gesture made my a person


## Dataset: Indian Sign Language (ISL)
ISL contains 128x128 pixel pictures of gestures belonging to characters A-Z and numbers 0-9.
## Model Used : CNN
Convolutional Nueral Network(CNN) works best for image classification. Its built-in convolutional layer reduces the high dimensionality of images without losing its information. CNN also contains a pooling layer that not only reduces the dimensionality but also helps overcome transitional invariance. This is one of the reasons why we choose CNN over ANN.
We make use of 2 Convolutional layers and a Dropout layer at the end

## Training 
```bash
python Hand_gesture.py
```

## Result 
Precision_score:  0.999766446405847  
F1 score: 0.9997652236010504  
Recall score: 0.9997652214744092

## Team
* Kiran SM
* Meghana Nekar
* Nidhi S Sheth
* Naresh Srinivas 
