# LandmineDetection_SignalProccesing
Binary classification model to detect landmines underground

We are proud to share our graduation project! In our project, we developed a remote-controlled mobile robot capable of detecting underground ceramic mines by sending signals into the ground and analyzing the returning signals using a pulse radar. However, due to radar costs, we carried out the project using radar simulation.

🔍 Project Details:

#Simulation: We used GPRsim.net to simulate the signals that the radar would obtain by representing ceramic mines and other objects (such as stones) placed underground with dielectric constants.

#Data Extraction: We converted the simulated signals into sequences using Webplotdigitizer and stored these sequences in CSV format.

#Labeling: In Excel, we labeled the signals from mines with 1 and the echo signals without mines with 0.

#Machine Learning: We trained a binary classification model using TensorFlow and Scikit-learn.
