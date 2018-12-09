# Advanced Car Nano Degree - Content

Below is the content of the Udacity Car Nano Degree that I have expanded in order to allow students to build a real miniature self driving car.

The aim is to use the Udacity course as a starting point and complement the course with new sections focusing especially on the construction of the miniature self driving car using Arduinos and Raspberry Pis.

## Term 1 - Computer Vision and Deep Learning

| Section  | Content | Details |
| :---: | :---: | ------------- |
| 1 | Welcome | This lesson will introduce you to the program, help you discover the services we provide, and show you all the incredible projects you'll build! |
| 2 | Workspaces | Udacity’s new in-browser programming editor moves you straight to programming, and past any challenges related to installing and configuring dependencies. |
| 3 | Computer Vision Fundamentals | Here, you’ll use OpenCV image analysis techniques to identify lines, including Hough transforms and Canny edge detection.|
| 4 | Project: Detect Lane Lines | You’ll detect highway lane lines from a video stream in your very first week in the program! |
| 5 | Gradients and Color Spaces | Learn how to use gradient thresholds and different color spaces to more easily identify lane markings on the road. Learn also how to use color spaces to detect traffic lights. |
| 6 | Project: Traffic Light Detection | xx |
| 7 | Camera Calibration | Learn how to calibrate your camera to remove inherent distortions that can affect its perception of the world. |
| 8 | Advanced techniques for lane findings | Discover more advanced computer vision techniques to improve upon your lane lines algorithm! |
| 9 | Project: Advanced Lane Detection | In this project, you’ll detect lane lines in a variety of conditions, including changing road surfaces, curved roads, and variable lighting. You’ll use OpenCV to implement camera calibration and image transforms, as well as apply filters, polynomial fits, and splines. |
| 10 | Introduction to Neural Networks | Here, you’ll survey the basics of neural networks, including regression, classification, perceptrons, and backpropagation.
| 11 | MiniFlow | xx |
| 12 | Introduction TensorFlow | Next up, you’ll train a logistic classifier using TensorFlow. And, you’ll implement related techniques, such as softmax probabilities and regularization. |
| 13 | Deep Neural Networks | This is where you’ll combine activation functions, backpropagation, and regularization, all using TensorFlow.
| 14 | Convolutional Neural Networks | Next, you’ll study the building blocks of convolutional neural networks, which are especially well-suited to extracting data from camera images. In particular, you’ll learn about filters, stride, and pooling. |
| 15 | LeNet for Traffic Signs | xx |
| 16 | Project: Traffic Sign Classifier | For this project, you’ll implement and train a convolutional neural network to classify traffic signs. You’ll use validation sets, pooling, and dropout to design a network architecture and improve performance. |
| 17 | Keras | This will be your opportunity to build a multi-layer convolutional network in Keras. And, you’ll compare the simplicity of Keras to the flexibility of TensorFlow. |
| 18 | Transfer Learning | Here, you’ll fine tune pre-trained networks to apply them to your own problems. You’ll study cannonical networks such as AlexNet, VGG, GoogLeNet, and ResNet. |
| 19 | Project: Behavioral Cloning | For this project, you’ll architect and train a deep neural network to drive a car in a simulator. You’ll collect your own training data, and use it to clone your own driving behavior on a test track. |
| 20 | Machine learning and Stanley | xx |
| 21 | Support Vector Machines | xx |
| 22 | Decisions Trees | xx |
| 23 | Object Detection | xx |
| 24 | Project: Vehicle Detection and Tracking | xx |

&nbsp;
## Term 2 - Sensor Fusion, Localization and Control

| Section  | Content | Details |
| :---: | :---: | ------------- |
| 1 | Introduction to Sensors | The first lesson of the Sensor Fusion Module covers the physics of two of the most import sensors on an autonomous vehicle — radar and lidar.
| 2 | Kalman Filters | Kalman filters are a key mathematical tool for fusing together data. You’ll implement these filters in Python to combine measurements from a single sensor over time.
| 3 | C++ Checkpoint | This is a chance to test your knowledge of C++ to evaluate your readiness for the upcoming projects.
| 4 | Lidar and Radar Fusion with Kalman Filters C++ | Extended Kalman Filters (EKFs) are used by autonomous vehicle engineers to combine measurements from multiple sensors into a non-linear model. First, you’ll learn the physics and mathematics behind vehicular motion. Then, you’ll combine that knowledge with an extended Kalman filter to estimate the positions of other vehicles on the road. |
| 5 | Project: Extended Kalman Filter | For this project, you’ll use data from multiple sensors to track a vehicle’s motion, and estimate its location with precision. Building an EKF is an impressive skill to show an employer. |
| 6 | Unscented Kalman Filters | xx |
| 7 | Project: Unscented Kalman Filter | xx |
| 8 | Introduction to Localization | In this intro, you’ll study how motion and probability affect your understanding of where you are in the world.
| 9 | Localization Overview | xx |
| 10 | Markov Localization | Here, you’ll use a Bayesian filter to localize the vehicle in a simplified environment. |
| 11 | Motion Models | Next, you’ll learn basic models for vehicle movements, including the bicycle model. You’ll estimate the position of the car over time given different sensor data. |
| 12 | Particle Filters | Next, you’ll use a probabilistic sampling technique known as a particle filter to localize the vehicle in a complex environment. |
| 13 | Implementation of a Particle Filter | To prepare for your project, you’ll implement a particle filter in C++. |
| 14 | Project: Kidnapped Vehicle | For your actual project, you’ll implement a particle filter to take real-world data and localize a lost vehicle. |
| 15 | PID Control | You’ll begin by build control systems to actuate a vehicle to move it on a path.|
| 16 | Project: PID Control | Then, you’ll implement the classic closed-loop controller — a proportional-integral-derivative control system. |
| 17 | Vehicle Models | xx |
| 18 | Project: Model Predictive Control | xx |
| 19 |  Geometry and Trigonometry | Before advancing further, you’ll get a refresh on your knowledge of the fundamental geometric and trigonometric functions that are necessary to model vehicular motion. |

&nbsp;
## Term 3 - Path Planning, Concentrations, and

| Section  | Content | Details |
| :---: | :---: | ------------- |
| 1 | Search | First, you’ll learn to search the environment for paths to navigate the vehicle to its goal. |
| 2 | Prediction | Then, you’ll estimate where other vehicles on the road will be in the future, utilizing both models and data.|
| 3 | Behavior Planning | Next, you’ll model your vehicles behavior choices using a finite state machine. You’ll construct a cost function to determine which state to move to next. |
| 4 | Trajectory Generation |Here, you’ll sample the motion space, and optimize a trajectory for the vehicle to execute its behavior. |
| 5 | Project: Path Planning | For your project, you’ll program a planner to navigate your vehicle through traffic on a highway. Pro tip: Make sure you adhere to the speed, acceleration, and jerk constraints!|
| 6 | Autonomous Vehicle Architecture | Get ready! It’s time to earn the system architecture of Carla, Udacity’s own self-driving car! |
| 7 | Introduction to ROS | Here, you’ll navigate Robot Operating System (ROS) to send and receive messages, and perform basic commands. |
| 8 | Packages & Catkin Workspaces | Next, you’ll create and prepare an ROS package so that you are ready to deploy code on Carla. |
| 9 | Writing ROS Nodes | The, you’ll develop ROS nodes to perform specific vehicle functions, like image classification or motion control.|
| 10 | Project: System Integration | Finally, for your last project, you’ll deploy your teams’ code to Carla, a real self-driving car, and see how well it drives around the test track! |


## Author

**Massimo Passamonti**: [email me](mailto:mpweb2.0@gmail.com)

## License

This project and its source code are licensed under the MIT License. [See MIT License](https://github.com/github/choosealicense.com/blob/gh-pages/LICENSE.md) file for details.
