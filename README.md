# Methodology
We will be simulating a robot that can move around in an unknown environment, and have it discover its own location using only a terrain map and an elevation sensor. We will encounter some of the classic challenges that make robotics difficult: noisy sensor data, and imprecise movement.
We will tackle these challenges with an artificial intelligence technique called a particle filter.

# Procedure
* Load a map from file, and initialize robot position.
* Make the robot respond to keyboard commands.
* Initialize a particle filter, and move the particles according to keyboard commands.
* Simulate the robot’s sensor, and assign weights to particles.
* Resample the particles in the filter to improve the state estimation.
