# RL-Tennis-Unity
Reinforcement Learning solution to the Unity Tennis environment.
	
This project is an implementation of a Reinforcement Learning solution to the Unity Tennis environment. The environment consists of two agents controlling rackets to bounce a ball over a net. The goal is for the agents to learn to controll the rackets in such a way that the ball does not fall on their side and pases over the net. The state space contains 8 dimensions (describing the position and velocity of the ball and racket). Each agent receives its own, local observation. The action space consists of 2 continuous actions which represent movement of the rackets back and forth, and jumping. If the ball goes over the net, the agent gets a reward of +0.1, and if the ball hits the ground or goes out of bounds, it receives a reward of -0.01. The task is episodic, and the environmnet is considered solved when the average reward over 100 episodes is higher than 0.5. 

## Getting Started

The solution (including installing necessary packages, initialising the environment, and training the agents) can be executed by running the Tennis.ipynb file.

## Project files

The project consists of the model.py and agent.py files, as well as the Tennis.ipynb notebook. They are organized as follows:

* model.py containes the code for the neural network.
* agent.py represents the agent itself. Here the DDPG logic is implemented.
* Tennis.ipynb contains the code for installing the necessary libraries, importing them, initialising the environment, agent and model, and training and saving the model weights.
* The trained model's saved weights:
	* checkpoint_actor_djokovic.pth
	* checkpoint_critic_djokovic.pth


These files, as well as the solution and explanation are based on the instructions and sample codes provided in the Udacity Deep RL Nanodegree.