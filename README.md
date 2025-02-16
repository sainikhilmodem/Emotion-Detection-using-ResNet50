The objective of the project is to determine the realtime emotion of a person by leveraging Deep Learning. AS it involves mainly two steps .
They are
1. The process upto training the model (upto saving the trained dataset with .h5 or .keras extension)
2. Checking the realtime (by webcam) using openCV.
   
Here in this project we took two CNN models.
1.Xception Model - Achived only 57% accuracy.
2.Resnet50 Model - Achieved 85% accuracy which is phenomenal.

Dateset : fer2013 (https://www.kaggle.com/datasets/msambare/fer2013 )
  The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is    more or less centred and occupies about the same amount of space in each image.
  The task is to categorize each face based on the emotion shown in the facial expression into one of seven categories       (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). The training set consists of 28,709 examples and the   public test set consists of 3,589 examples.
