# Deep Reinforcement Learning
## Unity Environment - Practice 1 - Navigation

Udacity Deep Reinforcement Learning Nanodegree - Practice 1

## Project Details

This is a Deep Reinforcement Learning excercice. 
The environment is a 3D space. 
The agent has to move in 4 directions (actions) and get the yellow bananas (+1 score). 
If the agent get a blue banana it will score -1.
This is an episodic problem in a continuous space. 
The objective of the excercise is to use a DRL algorithm that can reach an average score of 15.0 in less than 1800 episodes.

## Getting Started

To install and use the environment you have to follow these steps:

 1 Install Anaconda Suite and create (and activate) a new python environment
   ```python
   conda create --name drlnd python=3.6
   ```
 2 Install OpenAi gym
   ```python
   pip install gym
   ```
   
 3 Install the Unity Environment App (not Unity SDK!)
   * Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
   * Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
   * Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
   * Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
 
 4 Clone this repository and install other dependencies:
   ```python
   pip install ./python
   ```
 5 Run [Navigation.ipynb](https://github.com/jbagnato/deep-rl-unity/blob/main/Navigation.ipynb) (Jupyter Notebook) with code and watch how it trains a new model and later use it to play alone.
   
## Instructions

To train a new agent, open [Navigation.ipynb](https://github.com/jbagnato/deep-rl-unity/blob/main/Navigation.ipynb) Jupyter Notebook file.

Follow the steps described on each cell. 

You will find a dqn function that will train until ```np.mean(scores_window)>=15.0```This means that the average score is greater than 15.

Then it will use saved agent in file 'checkpoint.pth' to run 3 episodes that you can enjoy in realtime :-)
