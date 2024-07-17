# CartPole Reinforcement Learning Project
## Overview
This project explores various reinforcement learning algorithms to solve the CartPole-v1 environment from OpenAI's gym. The algorithms implemented include Monte Carlo, Q-Learning, and SARSA. The goal is to balance the pole on the cart by applying forces to the left or right.

## Algorithms Implemented
1. Monte Carlo
Monte Carlo methods are used to estimate the value of each state-action pair by averaging the returns (rewards) following each visit to the state-action pair.

2. Q-Learning
Q-Learning is an off-policy algorithm that learns the value of the optimal policy independently of the agent's actions. It updates the Q-values using the Bellman equation.

3. SARSA
SARSA is an on-policy algorithm that updates the Q-values based on the action actually taken by the agent. It updates the Q-values using the state-action-reward-state-action tuple.

## Environment
The CartPole-v1 environment is a classic control problem where the agent must balance a pole on a cart by applying forces to the left or right. The observation space consists of the cart's position, velocity, pole angle, and pole's velocity at the tip.

## Code Description
Monte Carlo
The Monte Carlo method involves generating episodes, discretizing states, and updating the Q-values based on the returns from each episode.

Q-Learning
The Q-Learning algorithm updates the Q-values using the Bellman equation. It involves discretizing states, performing actions based on the epsilon-greedy policy, and updating the Q-values accordingly.

SARSA
The SARSA algorithm updates the Q-values using the state-action-reward-state-action tuple. It follows an on-policy approach where the agent's actions influence the updates.


## Results
Monte Carlo
The Monte Carlo agent achieved moderate performance, balancing the pole for an average reward of 195 over the last 100 episodes.

Q-Learning
The Q-Learning agent demonstrated effective learning, achieving an average reward that increased consistently over episodes.

SARSA
The SARSA agent also showed effective learning, with performance comparable to the Q-Learning agent.

## Conclusion
This project demonstrates the implementation and comparison of Monte Carlo, Q-Learning, and SARSA algorithms for the CartPole-v1 environment. Each algorithm has its strengths and weaknesses, and the results show the effectiveness of each in balancing the pole.
