# Design-of-Pacman-using-Deep-Reinforcement-learning-and-OpenAI-Gym
Exploited the OpenAI Gym ‘MsPacman-v0’ environment of size (210,160,3) to collect the data from the simulation \
Estimated q-values using DQN, a deep CNN with three convolutional layers and two fully connected dense layers 
Built a ‘replay buffer’ called ‘prioritized Replay’ to store past experiences (s, a, s’, r) to use it to train Neural Net

Need to Install:
Numpy
Keras
Tensorflow as keras uses backend tensorflow
OpenAIgym[atari] 

To learn:
DQN
CNN
Bellman's Equation


An env object can be created with the env.make(<game-id-string>) function by passing the id string.
Each env object contains the following main functions:
The step() function takes an action object as an argument and returns four objects:
observation: An object implemented by the environment, representing the observation of the environment.
reward: A signed float value indicating the gain (or loss) from the previous action.
done: A Boolean value representing whether or not the scenario is finished.
info: A Python dictionary object representing the diagnostic information.
The render() function creates a visual representation of the environment.
The reset() function resets the environment to the original state.
Each env object comes with well-defined actions and observations, represented by action_space and observation_space.
