Project 1: Navigation
Introduction
For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

0 - move forward.

1 - move backward.

2 - turn left.

3 - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

Getting Started
1.Download the environment from one of the links below. You need only select the environment that matches your operating system:

Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip

Mac OSX: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip

Windows (32-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip

Windows (64-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip

2.Place the file in the DRLND GitHub repository, in the p1_navigation/ folder, and unzip (or decompress) the file.

Description
- dqn_agent.py: code for the agent used in the environment
- model.py: code containing the Q-Network used as the function approximator by the agent
- checkpoint.pt: saved model weights for the DQN model
- Navigation_solution.ipynb: notebook containing the solution

Instructions
Follow the instructions in Navigation_solution.ipynb to get started with training your own agent!


(Optional) Challenge: Learning from Pixels
After you have successfully completed the project, if you're looking for an additional challenge, you have come to the right place! 
In the project, your agent learned from information such as its velocity, along with ray-based perception of objects around its forward direction.
A more challenging task would be to learn directly from pixels!

To solve this harder task, you'll need to download a new Unity environment. This environment is almost identical to the project environment, 
where the only difference is that the state is an 84 x 84 RGB image, corresponding to the agent's first-person view. (Note: Udacity students should not submit a project with this new environment.)
