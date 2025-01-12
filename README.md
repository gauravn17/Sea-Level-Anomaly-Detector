# Sea-Level-Anomaly-Detector

My submission for UCSD's SMASH & NSF HDR ML Challenge Hackathon.

I chose the climate event identification dataset in the challenge, where the project was to apply advanced machine learning methodologies in a real-world context, focusing on the intricacies of sea-level dynamics and anomaly detection.
This challenge leveraged a comprehensive training dataset spanning 20 years, consisting of daily sea level measurements from 12 coastal stations along the US East Coast and sea-level elevation values in the North Atlantic. 
The goal was to develop a model that can accurately predict sea level anomalies at coastal stations for the next 10 years not included in the training dataset, predicting the sea-level anomalies across the 12 stations for each day.

I built a Dense Neural Network(DNN) using TensorFlow, with a binary crossentropy loss function to measure the accuracy with which the model predicted binary labels of data points, achieving an accuracy rate of 94.55%. 
