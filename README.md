# Snakes and Ladders Markov Decision Processes

This repository contains an implementation of Markov Decision Processes (MDP) applied to the Snakes and Ladders game. The project focuses on determining the optimal strategy for choosing the dice using the "value iteration" method.

## Introduction

Markov Decision Processes are a powerful framework for modeling and solving decision-making problems under uncertainty. In this project, we use MDP to model the Snakes and Ladders game, where the outcome of each move is partly random and partly under the control of the player.

## Theoretical Explanation

We delve into the theory behind MDP, discussing key concepts such as states, actions, reward functions, state transition functions, and the Markov property. We outline how these concepts apply to the Snakes and Ladders game and explain our objective of finding the optimal policy to minimize the expected number of turns to reach the final state.

## Implementation

We describe the implementation details of the MDP and value iteration algorithm. The `markovDecision` function serves as the main entry point, orchestrating the computation of transition matrices, rewards, and applying the Bellman equation to find the optimal policy. Auxiliary functions handle tasks such as creating the game board layout and computing transition probabilities.

## Results and Analysis

We present the results of testing our implementation with different strategies and game scenarios. Visualizations show the expected number of turns to reach the final state under various conditions, demonstrating the effectiveness of our approach.

## Conclusion

In conclusion, this project showcases the application of MDP to solve the Snakes and Ladders game, providing insights into optimal decision-making strategies. While randomness plays a role, our implementation demonstrates the power of MDP in finding near-optimal solutions in uncertain environments.

## Contact

Despite all the work done we can not ensure that our development is the best one to solve this problem, so if you would like to colaborate or to contact with us, please send an email to [jvgueca@gmail.com](mailto:jvgueca@gmail.com).
