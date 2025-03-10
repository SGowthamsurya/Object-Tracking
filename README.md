# Object-Tracking
Object Tracking using YOLO
**Introduction:**

  This project implements an object tracking system using Raspberry Pi as the central processing unit and Arduino to control the servo motors. The Raspberry Pi processes the input from a camera module to detect and track objects, while the Arduino handles motor control for real-time movement.

  

**Features:**

  Object Detection & Tracking: Uses computer vision techniques to identify and follow objects.
  
  Servo Motor Control: Arduino controls servo motors to adjust the camera position based on tracking input.
  
  Raspberry Pi as Processing Unit: Handles image processing and decision-making.
  
  Arduino as Actuator Controller: Manages servo movements efficiently.

  

**Components Used:**

  Raspberry Pi (any model with camera support)
  
  Arduino (Uno/Nano)
    
  Servo Motors
  
  Camera Module/USB Webcam
  
  Power Supply and Jumper Wires

  

**How It Works:**

  The camera module/USB Webcam captures live video.

  Raspberry Pi processes the video stream and detects the object.
  
  Based on the object’s movement, Raspberry Pi sends commands to the Arduino.
  
  The Arduino adjusts the servo motors to follow the object's position.
  
  The system continuously updates to track the object's movement in real-time.

  

**Future Improvements:**

  Implementing AI-based tracking for enhanced accuracy.
  
  Adding multiple camera support.
  
  Wireless communication between Raspberry Pi and Arduino.
