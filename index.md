## Welcome!

Please click the numbered headings below to view some of my CompSci projects in your browser. 

Each project is written in P5.js, although some were originally written in Python.

All projects are entirely my own work.


### Completed Projects:


#### [1. Solid 3D Engine: real-time object animation](https://tobiasloader.github.io/Solid-3D-Engine/Scenes/Space/index.html)

In March 2020, the UK went into lockdown in response to the Covid-19 pandemic with all A-level examinations being subsequently cancelled. With now having a lot more time on my hands I decided to focus on a new programming project; one that would build upon what I'd learned from developing my original [Wireframe 3D Engine](https://tobiasloader.github.io/Wireframe-3D-Engine) in 2018. Using linear algebra knowledge from my A-level further maths studies, my aim would be to design a more advanced engine that would be capable of rendering solid objects in real-time. In the same way that I developed the earlier engine I wanted to see how much I would be able to achieve through my own insight and ideas; without reference to external resources, libraries, etc.

My first example scene is space themed and can be viewed [here](https://tobiasloader.github.io/Solid-3D-Engine/Scenes/Space/index.html).
 
---

#### [2. Graphical Stock Exchange](https://tobiasloader.github.io/Graphical-Stock-Exchange/)

The aim of this project was to create a graphical interface in the form of a web app for an open-source financial exchange simulation called [BSE](https://github.com/davecliff/BristolStockExchange) – a programme developed in 2012 by Prof D Cliff of Bristol University Computer Science Department. 

Over a thousand lines of original Python were manually translated into P5.js to enable integration with a purpose built GUI featuring customisable input options and interactive animated graphs to display data output.
 
---

#### [3. Supervised Deep Neural Network](https://tobiasloader.github.io/Supervised-Deep-Neural-Network)

This was my first neural network algorithm, which I initially wrote in Python during Christmas of 2018. A few months later I converted it to P5.js in order to include a GUI – enabling the user to easily choose certain properties of the network, such as the number of hidden layers and the number of nodes per layer. The relatively trivial task I set the network was to learn to recognise the highest number from a list of random numbers between -1 and 1. In use, it is important that the number of numerical inputs into the nodes in the input layer is the same as the number of nodes in the output layer, i.e. a 1:1 mapping.

NB: I referred to a continuation of this project in my personal statement, namely the [reinforcement learning neural network](#1-training-a-reinforcement-neural-network) described below under the 'Projects In Progress’ section. 

---

#### [4. Wireframe 3D Engine](https://tobiasloader.github.io/Wireframe-3D-Engine)

This was my first major project, written during the summer of 2018. At this stage in my education I'd only covered GCSE and FSMQ level mathematics, so I didn't realise that much of what I'd been working on during those weeks could have been done far more efficiently with a few simple matrix equations... Nevertheless I had a lot of fun writing it and am quite proud of the end result.

---

#### [5. Basic Ray Tracer 1](https://tobiasloader.github.io/Basic-Ray-Tracer-1)

Soon after finishing my 3D-Engine in autumn 2018, and still being interested in the representation of the 3D world on a 2D screen, I began another large project. I had heard about the ray tracing technique, which enabled realistic 3D images to be drawn using virtual light rays, so I set out to write my own basic implementation.

---

#### [6. Particle Physics Simulator](https://tobiasloader.github.io/Particle-Physics-Simulator)

Inspired by a lesson on particle physics in spring 2019, I decided to simulate how sub-atomic particles might interact with each other. My programme includes a real-time graphical display showing the force felt by each particle during motion.

---

#### [7. Hawk-Dove Game Simulation](https://tobiasloader.github.io/Hawk-Dove-Game-Simulation)

Having watched a YouTube video about the concept of the Hawk-Dove model of game theory during the summer of 2019 I was inspired to create my own simulator to help me explore the idea. This tied in nicely with previous work I'd done on modelling predator-prey interactions with differential equations on the graphing calculator Desmos.com.

This is a simulation of population changes over time across two competing species – Hawks and Doves. Each has different traits; Hawks are often aggressive, whilst Doves have a tendency to share. All Hawks and Doves search for food during each time step. There is a maximum of 500 pieces of food available for consumption by the populations during each time step. If a Hawk or Dove is the only one to find a piece of food, it gets to keep all of it. If however, another Hawk or Dove finds the same piece of food, they must share that piece according to specific rules (see gameTheory variable below). The total quantity  of food eaten by a given species determines the number of individuals of that species spawning in the subsequent time step.

A common finding from running my Hawk-Dove simulation is that when there are few of one species and many of the other, the few rapidly catch up to the trend line; there is very little variation about the trend line. This holds true irrespective of the majority species – Hawk or Dove. It therefore appears to be advantageous to be a member of the minority species. By inspection it also appears evident that a general anticlockwise bias exists, particularly noticeable when dealing with extreme (Dove,Hawk) coordinate points, i.e. points far from the trend line. I have noticed this trend before when modelling predator-prey interactions with differential equations.

---

#### [8. Fourier Transform Simulator](https://tobiasloader.github.io/Fourier-Transform-Simulator)

In the autumn term of 2019, study of Euler's Formula and Roots of Unity broadened my understanding of complex numbers and led me to the story of the Fourier Transform. I found it fascinating how a seemingly chaotic function could be elegantly separated to reveal its constituent frequencies. I built this graphical simulator (with inspiration from a 3Blue1Brown video), to help me better understand the transform process.

---

#### [9. GraFx Graphing Calculator](https://tobiasloader.github.io/GraFx-Graphing-Calculator)

Although I frequently use the online graphing calculator [Desmos](https://www.desmos.com), and think it is an amazing resource, I have sometimes wanted the ability to plot various graphs for which Desmos offers limited functionality; such as arithmetic and geometric progressions. So, in autumn 2018 I wrote my own graphing calculator, GraFx, to solve this issue. Whilst GraFx is able to plot basic polynomials through its online interface, it was designed to respond to directly inputted source code and is therefore most suitable for local use. Its user can write their own functions, exactly as required – providing more freedom than Desmos allows, e.g. if I wished to plot complex numbers on an Argand diagram I could adapt the GraFx's source code to achieve this.


### Projects In Progress 


#### [1. Training A Reinforcement Neural Network](https://tobiasloader.github.io/Training-A-Reinforcement-Neural-Network)

This project is a continuation of the above [supervised neural network](#1-supervised-deep-neural-network). 

In May 2019 I attended a lecture on machine learning by Prof V Kanade and was inspired to adapt my supervised neural network algorithm to the reinforcement learning model. I decided to utilise a simple arcade game that I had designed some time ago, called 'Flag Run', in order to train the network and develop its intelligence. An important stage in this process involved re-writing the reward function of my supervised learning algorithm, such that data feeding into the back propagation would be dependant upon the immediate surroundings of the game player.

Currently the AI performs well initially but then deteriorates: once it has learned to travel in a particular direction, it tends to travel that way more frequently - reinforcing its knowledge of moving in that direction and creating a further bias for that direction...  My next major goal for this project is to solve this issue so that it continues to learn positively, without any single direction being overwhelmingly reinforced.

---

#### [2. Basic Ray Tracer 2](https://tobiasloader.github.io/Basic-Ray-Tracer-2)

After some reading in early autumn 2019, I revisited my [Basic Ray Tracer](#3-basic-ray-tracer-1) and ended up completely rewriting it. It incorporates a new algorithm for rapidly zeroing in on the edge of an object – approximately halving the edge position uncertainty during each iteration. And additionally includes a new GUI feature consisting of a selectable birds-eye view of the scene prior to rendering. This enables the user to decide exactly where to place the camera, including its angle of horizontal rotation, so that their eventual scene render will be completely customised.

There remain some display issues to solve, such as black lines that can appear on the rendered image, which I am considering solving temporarily by writing a clean up function that will fill these artificially. 

Additionally, whilst I intend to incorporate directional light sources, currently the project only makes use of ambient light. This means that the scene renders are quite dark, requiring that the GUI camera be placed very near the scene objects in order to clearly view them in these low light conditions once rendered. I also intend to add the ability for light to be reflected off the 3D spheres, and am currently working on the associated maths and how best to implement this.
