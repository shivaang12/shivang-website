---
layout: page
title: "Resume"
permalink: /resume/resume.html
---

Shivang Patel
=============

Education
---------

2020 - Present
:   **PhD, Computer Science**; West Virginia University (Morgantown, WV)
<br/><br/>
2017 - 2019
:   **MEng, Robotics**; University of Maryland (College Park, MD)
<br/><br/>
2013 - 2017
:   **BEng, Mechatronics**; G. H. Patel College of Engineering (Vallabh Vidhyanagar, India)

Technical Skills
----------------

Proficient in C++, Python, ROS, ROS 2, Gazebo, Ignition, openCV, Tensorflow, Keras, PyTorch, GIT, Docker and Linux.

Experience (Academic)
----------

**Graduate Research Assistant, Aerospace Department, UMD**

* Involved in the development of the DARPA’s Offensive Swarm Enabled Tactics (OFFSET) project (sprint 1) which utilizes more than 100 small Un-manned Aircraft Systems (UASs) to accomplish diverse missions in a complex urban environment.
* Researched two global planners which can optimize the area coverage in any complex urban environment and developed a compatible obstacle avoidance method for one of them which was lacking previously.
* Global Planners were developed in C++ as ROS packages and maintained using GIT with Doxygen style documentation.

**Graduate Research Assistant, Mechanical Department, UMD**

* Designed and developed an acoustic sensor using Metamaterials which amplifies wave pressure, makes detection of low wavelength possible.
* Variation of designs were prepared using CAD software SOLIDWORKS; Performed various levels of testing on the sensor designs for validation.
* Used LAUNCHXL-F28379D prototyping board for the sensor system integration with the functional mobile robot for obstacle avoidance.

Experience (Open Source)
----------

**Navigation 2**
* Actively contributing to Navigation2 ROS2 package on Github and participating in Navigation2 Work Group weekly meetings.
* My contribution includes improving documentation, Porting changes from ROS 1 libraries, Bug improvements and code review.

Projects
--------

**Self Driving Toy Car using Reinforcement Learning Technique**

* Trained an RC Toy car using Deep Q Learning with python 3 and tensorflow library, to make it learn to drive itself in a lane.
* Project contains two systems: toy car - modified to be controlled by Raspberry pi with a front camera; and a mainframe computer for training.
* Used ROS for system integration; Raspberry Pi to send camera feed to mainframe PC which trains the Deep Q Learning network and in return would send the control commands to the toy car; Reward and Penalty were given manually in each training iteration.

**Smart AGV**

* Leveraged ROS Navigation stack to augment the Relaxed Astar algorithm as a global planner plugin for the autonomous traversal of an AGV.
* Followed Software Development Techniques like Solo Iterative Process, maintaining product backlog, iteration backlog and work log and generated Doxygen style documentation.
* Used Git as a version control system, designed Unit tests, employed Continuous Integration through travis.ci, and used tools like cpplint (check styling errors), cppcheck (static code checking) and valgrind to check memory leaks.

**Evaluation of Adversarial Attacks and Defenses for DNN**

* Selected popular adversarial attacks, such as FGSM, JSMA, DeepFool, NewtonFool, Carlini and Wagner attack and Basic Iterative Method, and defenses, such as GDA, Label Smoothing, Feature Squeezing and Spatial Smoothing, and evaluated their performance on various networks, such as two-layer, four-layer, seven-layer, ten-layer, two-layer convolutional net and four-layer convolutional net.
* Tested two hypotheses - no defense method will allow classifiers to be robust against all attacks, and adversarial efficiency will decrease as the network gets deeper.
* Used MNIST dataset to test these hypotheses. Synthesize results into conference paper and presented to mock conference.

**Traffic sign detection using feature detection methods and Machine learning routines**

* First stage includes detection, which was achieved using image processing techniques such as RGB to HSV conversion, morphing, masking, contour detection and so forth.
* Second stage is recognition which consists of pre-processing, training a Support Vector Machines (SVM) classifier after feature extraction using Histogram of Oriented Gradients (HOG).

**Simulating the Lane Departure Warnings through Lane Detection in a Self Driving car.**
* Finding vertical lines using canny edge detection and then extrapolated longest Hough lines of lane pixels.

**Trajectory estimation through Visual Odometry.**
* Computed camera translation and rotation based on a video feed from car’s dashboard camera.
* Feature points were detected using Speed Up Robust Features (SURF), Camera pose is calculated by estimating Fundamental matrix using Random Sampling Consensus (RANSAC) algorithm.