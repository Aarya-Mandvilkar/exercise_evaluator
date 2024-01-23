# exercise_evaluator

This model takes in exercise video as user input and determines how good the user's exercise form is. Pose detection is used to detect the user's exercise form by using MediaPipe pose landmark model for 3D coordinates which are used to compute angles and distances made by various parts of the body. A multi-class classification model is written to evaluate the exercise form by classifying what type of exercise is being performed (jumping jacks, push-ups, squats, pull-ups, sit-ups). The classifcation model is trained on exercise forms that are considered accurate or correct so the probability of being a particular exercise determined by the classification model is used to describe how accurate the user's exercise form is.

To use:

Create and save a classification model using Exercise_Classification_Model
Input the video and classification model in Exercise_Model to get evaluation of exercise form
