# Markovian-stock-day-trading
This notebook contains RL and deep RL algorithms for simplified stock day-trading scenarios, in which N number of stocks stocks can alternate between a high (H) and a low (L) state, with a different reward at each state. The reward matrix and the state-transition probability matrix make up the markovian environment.
The aim is to compare tabular Q-learning and deep Q-Network algorithms (where the environment is unknown to the agent) to the ground truth of Policy Iteration (where the environment is known).
