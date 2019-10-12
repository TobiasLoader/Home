## Welcome!

Please click the numbered headings below to view and interact with my CompSci projects in your browser. 

All work is entirely my own.


### Completed Projects:


#### [1. Supervised-Deep-Neural-Network](https://tobiasloader.github.io/Supervised-Deep-Neural-Network)

<ins>Personal statement note:</ins> the reinforcement learning neural network referenced in my personal statement is a continuation of the supervised version described here. To view the reinforcement version please scroll down to the ’Flag-It-AI-Game’, listed under 'Projects In Progress’.

I originally wrote a python supervised learning neural network over Winter 2018, and converted *[the network to P5](https://tobiasloader.github.io/Neural-Network-P5)* in Spring 2019, as I wanted to be able to include a UI. The user can now determine certain properties of the network, such as the number of hidden layers and the number of nodes per layer.

---

#### [2. 3D-Engine](https://tobiasloader.github.io/3D-Engine)

This *[3D Engine](https://tobiasloader.github.io/3D-Engine)* was my main summer 2018 project. At this stage of my education I'd only covered GCSE/FSMQ mathematics, and so didn't realise that much of what I'd been working on for the past few weeks and months could be done in a few simple matrice equations. Nevertheless I had a lot of fun writing the engine and I consider it my first major project, a piece of work of which I'm proud.

---

#### [3. Ray-Tracer](https://tobiasloader.github.io/Ray-Tracer)

Soon after finishing my 3D-Engine in Autumn 2018 – and being still interested in representing a 3D world on a 2D screen – I launched into yet another large project. I'd heard of these *[Ray Tracer's](https://tobiasloader.github.io/Ray-Tracer)* which drew more realistic images of a 3D scene using virtual light rays. So I set out to write my own!

---

#### [4. Particle-Physics-Simulator](https://tobiasloader.github.io/Particle-Physics-Simulator)

Inspired in a Particle Physics lesson in Spring 2019, I decided to *[simulate how (sub-atomic) particles](https://tobiasloader.github.io/Particle-Physics-Simulator)* interact with each other, making sure to keep track of the forces felt by each one. 

---

#### [5. Dove-Hawk-Marketplace](https://tobiasloader.github.io/Dove-Hawk-Marketplace)

After having watched a Youtube video on the topic by Primer in Summer 2019, I wanted to simulate my own *[marketplace](https://tobiasloader.github.io/Dove-Hawk-Marketplace)* and have the freedom to play around for myself. This tied in nicely with previous work I'd done on modelling predators with differential equations on Desmos.

---

#### [6. Fourier-Transforms](https://tobiasloader.github.io/Fourier-Transforms)

As I started Y13 in Summer/Autumn 2019, we began revisiting complex numbers and Eulers form in further maths. This lead me to rediscover Fourier Transforms, something I'd been interseted in before but didn't previously have the knowledge to fully understand. I decided to try to simulate what was going on behind the scenes, and came up with this *[Fourier-Transforms](https://tobiasloader.github.io/Fourier-Transforms)*.

---

#### [7. GraFx](https://tobiasloader.github.io/GraFx)

In Autumn 2018, I realised that although Desmos was great and I used it all the time, I sometimes would want greater freedom to graph specific functions and arithmetic/geometric series etc... So I came up with my own graphing calculator: *[GraFx](https://tobiasloader.github.io/GraFx)*.


### Projects In Progress 


#### [1. Flag-It-AI-Game](https://tobiasloader.github.io/Flag-It-AI-Game)

Having written a supervised learning algorithm (see Neural-Network-P5 above), I wanted to also try out the reinforcement model. So during the summer I adapted a game I'd written a year or so prior (Flag It) to be played by an AI as it learns and improves. To write the reinforcement algorithm, I copied over what I'd produced for the supervised model and adjusted it such that the feedback into the back propagation was dependant upon the immediate surroundings of the player. Currently the AI preforms quite poorly despite starting out well. Once it learns to travel in a certain direction, it tends to travel that way more frequently - thus reinforcing its knowledge of moving in that direction, and creating a further bias for that direction. My next large goal for this project is to solve this issue such that it continues learning positively, without any one direction becoming overwhelming.

---

#### [2. New-Ray-Marcher](https://tobiasloader.github.io/New-Ray-Marcher)

In early Autumn, as I was reviewing some of my previous projects, my interest was once again peaked by Ray Tracers and Ray Marchers. I devised a new algorithm for rapidly zeroing in on the edge of on object (approximately halfing the uncertainty each iteration). This lead me to write a new version of my previous ray tracer, implementing this algorithm and this time also making use of a birdseye view before hand of the scene as a GUI. This user can then decide where to place the camera, and the angle of horizontal rotation the camera is at. However, I still have some displaying issues, such as black lines through the produced image (I need to write a new clean up function to artificially fill the gaps) and I haven't yet written in 'light sources'. So currently the scene is very dark (making use of only 'ambient' light), so the camera needs to be placed very need the objects to be able to clearly see the objects in very low light conditions.
