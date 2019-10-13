## Welcome!

Please click the numbered headings below to view some of my CompSci projects in your browser. 

Each project is written in P5.js, although some were originally written in Python.

All projects are entirely my own work.


### Completed Projects:


#### [1. Supervised Deep Neural Network](https://tobiasloader.github.io/Supervised-Deep-Neural-Network)

<ins>A note regarding my personal statement:</ins> the reinforcement learning neural network referred to in my personal statement (and listed [below](#1-training-a-reinforcement-neural-network) under the 'Projects In Progress’ section), is a continuation of the supervised deep neural network described here:
 
This was my first neural network algorithm, which I initially wrote in Python during Christmas of 2018. A few months later I converted it to P5.js in order to include a GUI – enabling the user to easily choose certain properties of the network, such as the number of hidden layers and the number of nodes per layer.

---

#### [2. 3D Engine](https://tobiasloader.github.io/3D-Engine)

This was my first major project, written during the summer of 2018. At this stage in my education I'd only covered GCSE and FSMQ level mathematics, so I didn't realise that much of what I'd been working on during those weeks could have been done far more efficiently with a few simple matrix equations... Nevertheless I had a lot of fun writing it and am quite proud of the end result.

---

#### [3. Ray Tracer](https://tobiasloader.github.io/Ray-Tracer)

Soon after finishing my 3D-Engine in autumn 2018, and still being interested in the representation of the 3D world on a 2D screen, I began another large project. I had heard about the ray tracing technique, which enabled realistic 3D images to be drawn using virtual light rays, so I set out to write my own basic implementation.

---

#### [4. Particle Physics Simulator](https://tobiasloader.github.io/Particle-Physics-Simulator)

Inspired by a lesson on particle physics in spring 2019, I decided to simulate how sub-atomic particles might interact with each other. My programme includes a real-time graphical display showing the force felt by each particle during motion.

---

#### [5. Hawk-Dove Game Simulation](https://tobiasloader.github.io/Hawk-Dove-GameTheory-Simulation)

Having watched a YouTube video about the concept of the Hawk-Dove model of game theory during the summer of 2019 I was inspired to create my own simulator to help me explore the idea.  This tied in nicely with previous work I'd done on modelling predator-prey interactions with differential equations on the graphing calculator Desmos.com.

---

#### [6. Fourier Transform Simulator](https://tobiasloader.github.io/Fourier-Transform-Simulator)

In the autumn term of 2019, study of Euler's Formula and Roots of Unity broadened my understanding of complex numbers and led me to the story of the Fourier Transform. I found it fascinating how a seemingly chaotic function could be elegantly separated to reveal its constituent frequencies. I built this graphical simulator to help me better understand the transform process.

---

#### [7. GraFx Graphing Calculator](https://tobiasloader.github.io/GraFx-Graphing-Calculator)

Although I frequently use the online graphing calculator [Desmos](https://www.desmos.com), and think it is an amazing resource, I have sometimes wanted the ability to plot various graphs for which Desmos offers limited functionality; such as arithmetic and geometric progressions. So, in autumn 2018 I wrote my own personal graphing calculator, GraFx, to solve this issue. Whilst GraFx is able to plot basic polynomials through its online interface, it was designed to respond to directly inputted source code and is therefore most suitable for local use. Its user can write their own functions, exactly as required – providing more freedom than Desmos allows, e.g. if I wished to plot complex numbers on an Argand diagram I could adapt the GraFx's source code to achieve this.


### Projects In Progress 


#### [1. Training A Reinforcement Neural Network](https://tobiasloader.github.io/Training-A-Reinforcement-Neural-Network)

This project is a continuation of the above [supervised neural network](#1-supervised-deep-neural-network). 

In May 2019 I attended a lecture on machine learning by Prof V Kanade and was inspired to adapt the algorithm to the reinforcement learning model. I decided to utilise a simple arcade game that I had designed previously, called 'Flag It', in order to train the network and thus develop its intelligence. An important stage in this process involved re-writing the reward function of my supervised learning algorithm, such that data feeding into the back propagation would be dependant upon the immediate surroundings of the game player.

Currently the AI performs well initially but then its performance deteriorates. Once it has learned to travel in a particular direction, it tends to travel that way more frequently - reinforcing its knowledge of moving in that direction and creating a further bias for that direction... 

My next major goal for this project is to solve this issue so that it continues to learn positively, without any single direction being overwhelmingly reinforced.

---

#### [2. New Ray Marcher](https://tobiasloader.github.io/New-Ray-Marcher)

In early Autumn, as I was reviewing some of my previous projects, my interest was once again peaked by Ray Tracers and Ray Marchers. I devised a new algorithm for rapidly zeroing in on the edge of on object (approximately halving the uncertainty each iteration). This lead me to write a new version of my previous ray tracer, implementing this algorithm and this time also making use of a birds-eye view before hand of the scene as a GUI. This user can then decide where to place the camera, and the angle of horizontal rotation the camera is at. However, I still have some displaying issues, such as black lines through the produced image (I need to write a new clean up function to artificially fill the gaps) and I haven't yet written in 'light sources'. So currently the scene is very dark (making use of only 'ambient' light), so the camera needs to be placed very need the objects to be able to clearly see the objects in very low light conditions.
