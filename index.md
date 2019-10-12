## Welcome!

Please click the numbered headings below to view and interact with my CompSci projects in your browser. 

All work is entirely my own and written in P5.js – either directly, or after conversion from Python.


### Completed Projects:


#### [1. Supervised-Deep-Neural-Network](https://tobiasloader.github.io/Supervised-Deep-Neural-Network)

<ins>A note regarding my personal statement:</ins> the reinforcement learning neural network referenced in my personal statement is a continuation of the supervised version described here. To view the reinforcement version please scroll down to the ’Flag-It-AI-Game’, listed under 'Projects In Progress’.

I produced my first neural network (supervised, deep) in Python during Christmas 2018. A few months later I converted it to P5.js in order to include a GUI, enabling the user to choose certain properties of the network, such as the number of hidden layers and the number of nodes per layer.

---

#### [2. 3D-Engine](https://tobiasloader.github.io/3D-Engine)

This was my first major project, written during the summer of 2018. At this stage in my education I'd only covered GCSE and FSMQ level mathematics, so I didn't realise that much of what I'd been working on during those weeks could have been done far more efficiently with a few simple matrix equations... Nevertheless I had a lot of fun writing it and am quite proud of the end result.

---

#### [3. Ray-Tracer](https://tobiasloader.github.io/Ray-Tracer)

Soon after finishing my 3D-Engine in autumn 2018, and being still interested in representing a 3D world on a 2D screen, I began another large project. I'd heard about Ray Tracer's, which could draw realistic 3D images using virtual light rays, so set out to write my own.

---

#### [4. Particle-Physics-Simulator](https://tobiasloader.github.io/Particle-Physics-Simulator)

Inspired by a lesson on particle physics in spring 2019, I decided to simulate how sub-atomic particles might interact with each other. My programme includes a real-time graphical display showing the force felt by each particle during motion.

---

#### [5. Dove-Hawk-Marketplace](https://tobiasloader.github.io/Dove-Hawk-Marketplace)

Having watched a YouTube video about the concept of the Dove-Hawk marketplace during the summer of 2019 I was inspired to create my own simulator to help me explore the idea.  This tied in nicely with previous work I'd done on modelling predator-prey interactions with differential equations on the graphing calculator Desmos.com.

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
