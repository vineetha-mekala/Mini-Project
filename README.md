# Mini-Project
# Vehicle Detection, Classification and Counting using OpenCV and Python


# Abstract

This project aims to develop a system for counting, detecting, and classifying vehicles in real-time using OpenCV and Python. Effective vehicle management is crucial for urban planning, traffic control, and improving safety on roads. Our approach combines computer vision techniques to enhance the accuracy and efficiency of vehicle monitoring compared to traditional methods. By utilizing video feeds, our system can provide valuable data to city planners and traffic management systems.

# Introduction

Understanding vehicle traffic is essential for managing urban environments. Accurate vehicle counting and classification help in:
1. Traffic Management:
By analyzing vehicle flow, authorities can optimize traffic signals and reduce congestion.
2. Urban Planning:
Data on vehicle types can inform infrastructure improvements and public transportation planning.
3. Safety Improvements:  
Monitoring traffic patterns helps identify dangerous areas and implement safety measures.

Current methods, like manual counting and physical sensors, often fall short due to high costs and limitations in accuracy. With advancements in computer vision, we can automate these tasks more effectively.

# Existing System

Many existing systems rely on:
1. Physical Sensors: 
These devices can be expensive to install and maintain. They may also have blind spots where vehicles are not detected.
2. Manual Counting:
This method is labor-intensive and prone to human error, leading to inaccurate data collection.
3. Basic Camera Systems: 
These systems often struggle with varying lighting conditions and may misidentify vehicles, affecting overall data quality.
These limitations highlight the need for a more robust solution that utilizes modern technology.

# Proposed System

Our proposed system leverages the power of OpenCV and Python to:
Automatically detect vehicles in video feeds.
Classify them into categories such as cars, trucks, and buses.
Provide real-time counting to support traffic analysis.
This solution will offer higher accuracy, reduce the need for manual intervention, and operate in various environmental conditions.

# System Architecture

The architecture of our system consists of:
#Input:
A video stream from a surveillance camera positioned at a traffic intersection.
#Processing Unit: 
Using OpenCV libraries to:(YOLO)
Preprocess the video (resize, convert to grayscale).
Apply vehicle detection algorithms (like Haar cascades or deep learning models).
Classify detected vehicles based on their features.
#Output: 
A user-friendly interface displaying:
Real-time vehicle counts.
Types of vehicles detected (e.g., car, truck, bus).
Visualization of traffic patterns over time.

# System Requirements

1. Python – 3.x (We used python 3.8.8 in this project) , 
2. OpenCV – 4.4.0 , 
It is strongly recommended to run DNN models on GPU.
You can install OpenCV via “pip install opencv-python opencv_contrib-python”.
3. Numpy – 1.20.3 , 
4. YOLOv3 Pre-trained model weights and Config Files.

# Methodology Overview

Data Collection: Obtain video footage from a busy intersection to ensure diverse vehicle types and traffic conditions.
Preprocessing: Use techniques such as image resizing and noise reduction to improve the quality of video frames for better detection.
Vehicle Detection: Implement OpenCV algorithms that identify vehicles within the frames. This may involve training a model on annotated images for better accuracy.
Classification: Use feature extraction techniques to differentiate between vehicle types based on size, shape, and other visual characteristics.
Counting Logic: Develop a system to track vehicles as they enter and exit the camera’s field of view, ensuring accurate counts even in high-traffic situations.

# Conclusion

The project on vehicle detection, classification, and counting using OpenCV and the YOLOv3 model demonstrates the effectiveness of combining deep learning algorithms with computer vision techniques for real-time traffic analysis. By leveraging OpenCV's DNN module and the YOLOv3 architecture, the system successfully identifies and categorizes vehicles such as cars, heavy motor vehicles (HMVs), and light motor vehicles (LMVs) on the road. The implementation of a Euclidean distance-based tracker ensures accurate counting and monitoring of each detected vehicle.

# Future Scope

Real-Time Traffic Monitoring, 
Counting Vehicles at Toll Booths, 
Improving Traffic Light Timing, 
Parking Lot Management, 
Enhancing Road Safety, 
Data Collection for Urban Planning.

