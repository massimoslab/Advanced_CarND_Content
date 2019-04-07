# Advanced Car Nano Degree - Content

Below is the content of the Udacity Car Nano Degree that I have expanded in order to allow students to build a real miniature self driving car.

The aim is to use the Udacity course as a starting point and complement the course with new sections focusing especially on the construction of the miniature self driving car using Arduinos and Raspberry Pis.

As an engineer, you should have a broad understand of both software and also hardware. The aim of this extended course is to give the opportunity to students to learn the software principles from the Udacity course but to complement this knowledge by applying all the theory learnt on a real miniature self-driving car that will be built from scratch. This approach will also allow students to understand the limitations that real-world system bring as a challenge and how to best tackle them.

The sections in <span style="color:red"> **red** </span> are the projects or lessons that differ from the standard Udacity course. These projects and/or courses have been adapted to be used for a miniature self driving car.

## Term 1 - Computer Vision and Deep Learning
I have reorganised Term 1 (compared to the original Udacity course) so that the computer vision is completed early on in the course and is directly applied in the construction of a traffic light detector and classifier. Please notice that no machine learning is used in the initial part of the term.

<table>
  <tr>
      <th>Section</th>
      <th>Content</th>
      <th>Details</th>
  </tr>
  <tr>
      <td align="center"> 1 </td>
      <td align="center"> Welcome </td>
      <td align="left"> This lesson will introduce you to the program, help you discover the services we provide, and show you all the incredible projects you'll build! </td>
  </tr>
  <tr>
      <td align="center"> 2 </td>
      <td align="center"> Workspaces </td>
      <td align="left">  Udacity’s new in-browser programming editor moves you straight to programming, and past any challenges related to installing and configuring dependencies. </td>
  </tr>
  <tr>
      <td align="center" style="color:red"> <b> 3 <b> </td>
      <td align="center" style="color:red"> <b> Project: Arduino Traffic Light <b> </td>
      <td align="left"> <b> In this project you will build a real traffic light using Arduino <b> </td>
  </tr>
  <tr>
      <td colspan="3" align="center"> <b> Computer Vision <b> </td>
  </tr>
  <tr>
      <td align="center" > 4 </td>
      <td align="center"> Computer Vision Fundamentals </td>
      <td align="left"> Here, you’ll use OpenCV image analysis techniques to identify lines, including Hough transforms and Canny edge detection. </td>
  </tr>
  <tr>
      <td align="center" style="color:red"> <b> 5 <b></td>
      <td align="center" style="color:red"> <b> Project: Detect Lane Lines <b> </td>
      <td align="left"> <b> You’ll detect highway lane lines from a video stream in your very first week in the program! <b> </td>
  </tr>
  <tr>
      <td align="center"> 6 </td>
      <td align="center"> Gradients and Color Spaces </td>
      <td align="left"> Learn how to use gradient thresholds and different color spaces to more easily identify lane markings on the road. Learn also how to use color spaces to detect traffic lights. </td>
  </tr>
  <tr>
      <td align="center" style="color:red"> <b> 7 <b> </td>
      <td align="center" style="color:red"> <b> Project: Traffic Light Detection <b> </td>
      <td align="left"> <b> xxx <b> </td>
  </tr>
  <tr>
      <td align="center"> 8 </td>
      <td align="center"> Camera Calibration </td>
      <td align="left"> Learn how to calibrate your camera to remove inherent distortions that can affect its perception of the world. </td>
  </tr>
  <tr>
      <td align="center"> 9 </td>
      <td align="center"> Advanced techniques for lane findings </td>
      <td align="left"> Discover more advanced computer vision techniques to improve upon your lane lines algorithm! </td>
  </tr>
  <tr>
      <td align="center" style="color:red"> <b> 10 <b> </td>
      <td align="center" style="color:red"> <b> Project: Advanced Lane Detection <b> </td>
      <td align="left"> <b> In this project, you’ll detect lane lines in a variety of conditions, including changing road surfaces, curved roads, and variable lighting. You’ll use OpenCV to implement camera calibration and image transforms, as well as apply filters, polynomial fits, and splines. <b> </td>
  </tr>
  <tr>
      <td colspan="3" align="center"> <b> Machine Learning <b> </td>
  </tr>
  <tr>
      <td align="center"> 11 </td>
      <td align="center"> Introduction to Neural Networks </td>
      <td align="left"> Here, you’ll survey the basics of neural networks, including regression, classification, perceptrons, and backpropagation. </td>
  </tr>
  <tr>
      <td align="center"> 12 </td>
      <td align="center"> MiniFlow </td>
      <td align="left"> xxx </td>
  </tr>
  <tr>
      <td align="center"> 13 </td>
      <td align="center"> Introduction TensorFlow </td>
      <td align="left"> Next up, you’ll train a logistic classifier using TensorFlow. And, you’ll implement related techniques, such as softmax probabilities and regularization. </td>
  </tr>
  <tr>
      <td align="center"> 14 </td>
      <td align="center"> Deep Neural Networks </td>
      <td align="left"> This is where you’ll combine activation functions, backpropagation, and regularization, all using TensorFlow. </td>
  </tr>
  <tr>
      <td align="center"> 15 </td>
      <td align="center"> Convolutional Neural Networks </td>
      <td align="left"> Next, you’ll study the building blocks of convolutional neural networks, which are especially well-suited to extracting data from camera images. In particular, you’ll learn about filters, stride, and pooling. </td>
  </tr>
  <tr>
      <td align="center"> 16 </td>
      <td align="center"> LeNet for Traffic Signs </td>
      <td align="left"> xxx </td>
  </tr>
  <tr>
      <td align="center" style="color:red"> <b> 17 <b> </td>
      <td align="center" style="color:red"> <b> Project: Traffic Sign Detection <b> </td>
      <td align="left"> <b> xxx <b> </td>
  </tr>
  <tr>
      <td align="center" style="color:red"> <b> 18 <b> </td>
      <td align="center" style="color:red"> <b> Project: Traffic Sign Classifier <b> </td>
      <td align="left"> <b> For this project, you’ll implement and train a convolutional neural network to classify traffic signs. You’ll use validation sets, pooling, and dropout to design a network architecture and improve performance. <b> </td>
  </tr>
  <tr>
      <td align="center"> 19 </td>
      <td align="center"> Keras </td>
      <td align="left"> This will be your opportunity to build a multi-layer convolutional network in Keras. And, you’ll compare the simplicity of Keras to the flexibility of TensorFlow. </td>
  </tr>
  <tr>
      <td align="center"> 20 </td>
      <td align="center"> Transfer Learning </td>
      <td align="left"> Here, you’ll fine tune pre-trained networks to apply them to your own problems. You’ll study cannonical networks such as AlexNet, VGG, GoogLeNet, and ResNet. </td>
  </tr>
  <tr>
      <td align="center" style="color:red"> <b> 21 <b> </td>
      <td align="center" style="color:red"> <b> Project: Remote Controlled Vehicle <b> </td>
      <td align="left"> <b> xxx <b> </td>
  </tr>
  <tr>
      <td align="center" style="color:red"> <b> 22 <b> </td>
      <td align="center" style="color:red"> <b> Project: Behavioral Cloning <b> </td>
      <td align="left"> <b> For this project, you’ll architect and train a deep neural network to drive a car in a simulator. You’ll collect your own training data, and use it to clone your own driving behavior on a test track. <b> </td>
  </tr>
  <tr>
      <td align="center"> 23 </td>
      <td align="center"> Machine learning and Stanley </td>
      <td align="left"> xxx </td>
  </tr>
  <tr>
      <td align="center"> 24 </td>
      <td align="center">  Support Vector Machines </td>
      <td align="left"> xxx </td>
  </tr>
  <tr>
      <td align="center"> 25 </td>
      <td align="center">  Decisions Trees </td>
      <td align="left"> xxx </td>
  </tr>
  <tr>
      <td align="center"> 26 </td>
      <td align="center">  Object Detection </td>
      <td align="left"> xxx </td>
  </tr>
  <tr>
      <td align="center" style="color:red"> <b> 27 <b> </td>
      <td align="center" style="color:red"> <b> Project: Vehicle Detection and Tracking <b> </td>
      <td align="left"> <b> xxx <b> </td>
  </tr>
  </tr>
</table>

&nbsp;

## Term 2 - Sensor Fusion, Localization and Control
&nbsp;


<table>
  <tr>
      <th>Section</th>
      <th>Content</th>
      <th>Details</th>
  </tr>
  <tr>
      <td align="center"> 1 </td>
      <td align="center"> C++ Checkpoint </td>
      <td align="left"> This is a chance to test your knowledge of C++ to evaluate your readiness for the upcoming projects. </td>
  </tr>
  <tr>
      <td align="center"> 2 </td>
      <td align="center"> Introduction to Sensors </td>
      <td align="left"> The first lesson of the Sensor Fusion Module covers the physics of two of the most import sensors on an autonomous vehicle — radar and lidar. </td>
  </tr>
  <tr>
      <td colspan="3" align="center"> <b> Kalman Filters <b> </td>
  </tr>
  <tr>
      <td align="center" > 3 </td>
      <td align="center"> Kalman Filters </td>
      <td align="left"> Kalman filters are a key mathematical tool for fusing together data. You’ll implement these filters in Python to combine measurements from a single sensor over time. </td>
  </tr>
  <tr>
      <td align="center"> 4 </td>
      <td align="center"> Lidar and Radar Fusion with Kalman Filters C++ </td>
      <td align="left"> Extended Kalman Filters (EKFs) are used by autonomous vehicle engineers to combine measurements from multiple sensors into a non-linear model. First, you’ll learn the physics and mathematics behind vehicular motion. Then, you’ll combine that knowledge with an extended Kalman filter to estimate the positions of other vehicles on the road. </td>
  </tr>
  <tr>
      <td align="center" style="color:red"> <b> 5 <b> </td>
      <td align="center" style="color:red"> <b> Project: Extended Kalman Filter <b> </td>
      <td align="left"> <b> For this project, you’ll use data from multiple sensors to track a vehicle’s motion, and estimate its location with precision. Building an EKF is an impressive skill to show an employer. <b> </td>
  </tr>
  <tr>
      <td align="center"> 6 </td>
      <td align="center"> Unscented Kalman Filters </td>
      <td align="left"> xxx </td>
  </tr>
  <tr>
      <td align="center" style="color:red"> <b> 7 <b> </td>
      <td align="center" style="color:red"> <b> Project: Unscented Kalman Filter <b> </td>
      <td align="left"> <b> xxx <b> </td>
  </tr>
  <tr>
      <td colspan="3" align="center"> <b> Localization <b> </td>
  </tr>
  <tr>
      <td align="center"> 8 </td>
      <td align="center"> Introduction to Localization </td>
      <td align="left"> In this intro, you’ll study how motion and probability affect your understanding of where you are in the world. </td>
  </tr>
  <tr>
      <td align="center"> 9 </td>
      <td align="center"> Localization Overview </td>
      <td align="left"> xxx </td>
  </tr>
  <tr>
      <td align="center"> 10 </td>
      <td align="center"> Markov Localization </td>
      <td align="left"> Here, you’ll use a Bayesian filter to localize the vehicle in a simplified environment. </td>
  </tr>
  <tr>
      <td align="center"> 11 </td>
      <td align="center"> Motion Models </td>
      <td align="left"> Next, you’ll learn basic models for vehicle movements, including the bicycle model. You’ll estimate the position of the car over time given different sensor data. </td>
  </tr>
  <tr>
      <td align="center"> 12 </td>
      <td align="center"> Particle Filters </td>
      <td align="left"> Next, you’ll use a probabilistic sampling technique known as a particle filter to localize the vehicle in a complex environment. </td>
  </tr>
  <tr>
      <td align="center"> 13 </td>
      <td align="center"> Implementation of a Particle Filter </td>
      <td align="left"> Next, you’ll use a probabilistic sampling technique known as a particle filter to localize the vehicle in a complex environment. </td>
  </tr>
  <tr>
      <td align="center"> <b> 14 <b> </td>
      <td align="center"> <b> Project: Kidnapped Vehicle <b> </td>
      <td align="left"> <b> For your actual project, you’ll implement a particle filter to take real-world data and localize a lost vehicle. <b> </td>
  </tr>
  <tr>
      <td colspan="3" align="center"> <b> Controller Systems <b> </td>
  </tr>
  <tr>
      <td align="center"> 15 </td>
      <td align="center"> PID Control </td>
      <td align="left"> You’ll begin by build control systems to actuate a vehicle to move it on a path. </td>
  </tr>
  <tr>
      <td align="center"> <b> 16 <b> </td>
      <td align="center"> <b> Project: PID Control <b> </td>
      <td align="left"> <b> Then, you’ll implement the classic closed-loop controller — a proportional-integral-derivative control system. <b> </td>
  </tr>
  <tr>
      <td align="center"> 17 </td>
      <td align="center"> Vehicle Models </td>
      <td align="left"> xxx </td>
  </tr>
  <tr>
      <td align="center"> <b> 18 <b> </td>
      <td align="center"> <b> Project: Model Predictive Control <b> </td>
      <td align="left"> <b> xxx <b> </td>
  </tr>
  <tr>
      <td align="center"> 19 </td>
      <td align="center"> Geometry and Trigonometry </td>
      <td align="left"> Before advancing further, you’ll get a refresh on your knowledge of the fundamental geometric and trigonometric functions that are necessary to model vehicular motion. </td>
  </tr>
  </tr>
</table>


&nbsp;
## Term 3 - Path Planning, Concentrations, and
&nbsp;



<table>
  <tr>
      <th>Section</th>
      <th>Content</th>
      <th>Details</th>
  </tr>
  <tr>
      <td align="center"> 1 </td>
      <td align="center"> Search </td>
      <td align="left"> First, you’ll learn to search the environment for paths to navigate the vehicle to its goal. </td>
  </tr>
  <tr>
      <td align="center"> 2 </td>
      <td align="center"> Prediction </td>
      <td align="left"> Then, you’ll estimate where other vehicles on the road will be in the future, utilizing both models and data. </td>
  </tr>
  <tr>
      <td align="center" > 3 </td>
      <td align="center"> Behavior Planning </td>
      <td align="left"> Next, you’ll model your vehicles behavior choices using a finite state machine. You’ll construct a cost function to determine which state to move to next. </td>
  </tr>
  <tr>
      <td align="center"> 4 </td>
      <td align="center"> Trajectory Generation </td>
      <td align="left"> Here, you’ll sample the motion space, and optimize a trajectory for the vehicle to execute its behavior. </td>
  </tr>
  <tr>
      <td align="center"> <b> 5 <b> </td>
      <td align="center"> <b>Project: Path Planning <b> </td>
      <td align="left"> <b> For your project, you’ll program a planner to navigate your vehicle through traffic on a highway. Pro tip: Make sure you adhere to the speed, acceleration, and jerk constraints! <b> </td>
  </tr>
  <tr>
      <td align="center"> 6 </td>
      <td align="center"> Autonomous Vehicle Architecture </td>
      <td align="left"> Get ready! It’s time to earn the system architecture of Carla, Udacity’s own self-driving car! </td>
  </tr>
  <tr>
      <td align="center"> 7 </td>
      <td align="center"> Introduction to ROS </td>
      <td align="left"> Here, you’ll navigate Robot Operating System (ROS) to send and receive messages, and perform basic commands. </td>
  </tr>
  <tr>
      <td align="center"> 8 </td>
      <td align="center"> Packages & Catkin Workspaces </td>
      <td align="left"> Next, you’ll create and prepare an ROS package so that you are ready to deploy code on Carla. </td>
  </tr>
  <tr>
      <td align="center"> 9 </td>
      <td align="center"> Writing ROS Nodes </td>
      <td align="left"> The, you’ll develop ROS nodes to perform specific vehicle functions, like image classification or motion control. </td>
  </tr>
  <tr>
      <td align="center"> <b> 10 <b> </td>
      <td align="center"> <b> Project: System Integration <b> </td>
      <td align="left"> <b> Finally, for your last project, you’ll deploy your teams’ code to Carla, a real self-driving car, and see how well it drives around the test track! <b> </td>
  </tr>
  </tr>
</table>

&nbsp;


## Annexes
The annexes contain valuable material that will allows students to familiarise themselves with topics that they might have never seen before such as Arduino and Raspberry Pi programming.

<table>
  <tr>
      <th>Annex</th>
      <th>Content</th>
      <th>Details</th>
  </tr>
  <tr>
      <td align="center"> 1 </td>
      <td align="center"> Arduino Basics </td>
      <td align="left"> The Arduino is a single-board microcontroller able to perform simple tasks at high speed. The Arduino can be connected with several external devices such as motors, sensors, etc. which can in turn send and receive signals to and from the Arduino. In this Annex, students will familiarise themselves with the basics of Arduino. </td>
  </tr>
  <tr>
      <td align="center"> 2 </td>
      <td align="center"> Raspberry Pi Basics </td>
      <td align="left"> The Raspberry Pi is effectively a mini-computer able to perform complex computations at a smaller speed compared to the Arduino. Similary, the Raspberry Pi can be connected to various external devices and also to the Arduino itself so that the two devices can communicate.  </td>
  </tr>
  <tr>
      <td align="center" > 3 </td>
      <td align="center"> Car Chassis </td>
      <td align="left"> For this project students will use a four-wheel car chassis with rear wheel propulsion and front wheel steering mechanism. In this annex we will explain how to assemble the car chassis. </td>
  </tr>
  <tr>
      <td align="center" > 4 </td>
      <td align="center"> Motor Controller </td>
      <td align="left"> Since the motors that we will be using for the car chassis require higher voltage, the use of a so-called motor controller becomes necessary. n this annex students will familiarise themselves with an L298N Motor Controller. </td>
  </tr>
  <tr>
      <td align="center" > 5 </td>
      <td align="center"> I2C Controller </td>
      <td align="left"> Amongst the many ways to connect an Arduino to a Raspberry Pi, the I2C connection represents the most flexible solution. In this annex students will learn how to implement an I2C connection which allows an Arduinos to communicate with one or more Raspberry Pis. </td>
  </tr>
  <tr>
      <td align="center" > 6 </td>
      <td align="center"> Pi Camera </td>
      <td align="left"> As we will be working a lot with computer vision tools, the use of a camera becomes essential. The Pi Camera is a camera device that can be connected to the Raspberry Pi. The captured images can be directly processed in python. </td>
  </tr>
  </tr>
</table>

&nbsp;

## Author

**Massimo Passamonti**: [email me](mailto:mpweb2.0@gmail.com)

## License

This project and its source code are licensed under the MIT License. [See MIT License](https://github.com/github/choosealicense.com/blob/gh-pages/LICENSE.md) file for details.
