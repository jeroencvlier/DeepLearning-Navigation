# <u>Training a Neural Network to Navigate</u>

![GIF of Trained Network](Images/BananaAnimation1.gif)

### <u>Introduction:</u> 

The goal of this project is to train a Neural Network to navigate through an environment set up by [Unity](https://unity.com/) to collect yellow bananas and avoid collecting blue bananas. 


### <u>Environment</u>
Once the Unity environment has been set up, the agent will navigate around collecting yellow bananas for a reward of +1 and blue bananas for a reward of -1. The state-space consists of an array of 37 elements describing the environment in front of the agent, including the objects, and velocity of the agent. 

There are 4 possible actions in this environment:

- **`0`** - Forward.
- **`1`** - Backward.
- **`2`** - Left.
- **`3`** - Right.

After the input of each action, the environment returns the next state and the reward received for that action. This next state is then fed back into the Neural Network to predict the next state.


### <u>Solving the environment</u>
For the environment to be considered resolved, the agent must collect a total of 13 points within 1800 episodes. An episode is considered single gameplay. Once the agent achieves an average of the given target over the last 100 episodes, the environment is considered solved. 

For a more challenging task, a target of 15 reward points in under 500 episodes would be an achievement.

### <u>Getting Started</u>

To run this project yourself, you will need to follow the installation instructions as listed below:

1. Follow this [Udacity Github link](https://github.com/udacity/deep-reinforcement-learning#dependencies) for instructions to install all the dependencies.

2. To set up the game, follow [this link](https://github.com/udacity/deep-reinforcement-learning/blob/master/p1_navigation/README.md#getting-started) for instructions to download the environment.

3. Download this repository to your local computer.

4. Install additional requirements. To easily install the requirements, navigate to the location of the requirements folder in the terminal and run the following command:
```
pip -r install requirements.txt
```