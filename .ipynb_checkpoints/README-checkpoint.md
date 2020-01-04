[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif "Trained Agent"
[image2]: https://user-images.githubusercontent.com/10624937/43851646-d899bf20-9b00-11e8-858c-29b5c2c94ccc.png "Crawler"


# Project 2: Continuous Control
In this project we solve the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment. using a DDPG Agent. The agent moves a double-jointed arm to target locations.

![Trained Agent][image1]



## Getting Started

To get started you will need to clone this project into a directory of your choice and install a the preequsits

### Prerequisites

In order to run this code you wil need to install the dependancies within the requirments.txt file.

`pip install -r requirements.txt`


## Enviroment

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

Within this implementation we will be using 20 identical but independant arms for training. This envormnet is considered completed when the agents recive an average score of +30 (over 100 consecutive episodes, and over all agents).


## Instructions
To train the agent, run all the cells within [Continuous_Control.ipynb](Continuous_Control.ipynb)


## Results 
![Trained Agent](./results.png)


## Acknowledgments

* Udacity
