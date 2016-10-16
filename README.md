# Particle-Collision-Simulator
A Java project for visualizing large amount of particles' physical collisions

This project is done based on the instructions provided in the Coursera's Algorithms Part 2 course.

## How to use
1. Go to **out\production\Particle Collision Simulator** folder
2. Open **CMD** or **Bash** here then type **java Main TOTAL_PARTICLES** to run the visualization, if you neglect the TOTAL_PARTICLES then you will need to do the 3rd step.
3. The program will wait for you to paste the test data, go into the folder **collider/testset/** then open any file as a text and copy all the text then paste into your program instance. Press Enter.
4. You will see a visualization based on the test data you chose on both the GUI and the console.


## Efficiency
The collision detection algorithm is efficient because we use Binary Heap to store events and pop the earliest event to be done at each instant in time instead of doing time-driven discrete detection. We are doing event-driven continuous detection for perfect collision detection and fast computation when dealing with a lot of particles.


## Example Visualization GIF
These images look laggy because the video recorder was not good. 

But if you run it on your machine, it will look very smooth.
![billiards5.gif](/img/billiards5.gif?raw=true "billiards5.gif")

![diffusion2.gif](/img/diffusion2.gif?raw=true "diffusion2.gif")

There are lots of visualization scenario for you to play with! This is just a handful of them.
