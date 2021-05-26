# Self_Driving_Car_Environment_Modelling_and_Motion_Planning
- First, we model the environment dynamics of an F1/10 self-driving car using a meural network.
  - This is learned using sample trajectories generated from the simulator.
  - The objective function calculates far the car is from the centerline of the track.
  - Thus learned model predicts the latent state and the reward for the action taken at the current state.
  - While real physics model is availble, it does not address the noise and idiosyncracies present in the environment. A neural network, on the other hand, can    learn the idiosyncracies of the environment not factored in by an ideal physics model.
- Then, we learn motion plans using deep cross entropy (CEM). For this, we make use of the simulator instead of the learned state space model.<br>

# Simulation
Following is a demo of the car using the policy generated using CEM to run on the racetrack.


<p align="left">
  <img src="https://github.com/being-aerys/Self_Driving_Car_Environment_Modelling_and_Motion_Planning/blob/master/car_demo.gif" alt="animated" />
</p>


This is a collborative work by Aashish Adhikari, Niraj Basnet, and Ashwin Vinoo.
