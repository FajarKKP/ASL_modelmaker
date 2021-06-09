# ASL_modelmaker

# Overview
Speech impairment is a disability which affects an individuals ability to communicate using speech and hearing. Although sign language is ubiquitous in recent times, there remains a challenge for non-sign language speakers to communicate with sign language speakers or signers. With recent advances in deep learning and computer vision there has been promising progress in the fields of motion and gesture recognition using deep learning and computer vision based techniques. The focus of this work is to create a vision-based application that offers sign language translation to text thus aiding communication between signers and non-signers.

# Model
In this project we use efficientNet for transfer learning, after the efficientNet layer we add the dropout layer to lessen the effect of overfitting. Finally, we add output layer to 29 nodes so the model has appropriate classification.The models is saved to tflite format.

# Android App
Android repository can be seen here: https://github.com/fariqkr/SignForYou
