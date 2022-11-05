# IBM-Project-16160-1659608634
Real-Time Communication System Powered by AI for Specially Abled
Problem Statement:
  To model a system for aiding deaf and dumb people and help them to communicate in real-time
  
 Idea / Solution description
  We start by collecting key points from mediapipe holistic and collect a bunch of data from keypoints We then build a LSTM model and train with our stored data which helps us to detect action with a number of frames. Once training is done, we can use this model for real time hand gesture detection and simultaneously convert the gesture to speech using OpenCV
