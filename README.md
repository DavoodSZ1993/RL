## Implementation of various RL algorithms only for mastering these concepts.

Some of these algorithms are exact copy of other sources (books, Medium, Towardsdatascience, ...)

#### 01. Optimal Policy Search: 
This code is from the Medium article titled: "[Reinforcement Learning, Part 4: Optimal Policy Search with MDP](https://medium.com/ai%C2%B3-theory-practice-business/reinforcement-learning-part-4-optimal-policy-search-with-mdp-7fc96158ea8a)" written by [Dan Lee](https://medium.com/@Adline125)

#### 02. Temporal-Difference Predicition:
This code is the exact implementation of the Medium article titled: "[Reinforcement Learning in Python, Temporal-Difference Predicition](https://medium.com/reinforcement-learning-in-python-temporal/reinforcement-learning-in-python-temporal-difference-prediction-5b3b4e46f22f)" by [James Mukuya](https://medium.com/@james.mukuya).

#### 03. A Python Realization of Q-Learning:
This realization is derived from the Medium Article: "[Reinforcement Learning, Part 6: TD(λ) & Q-learning](https://medium.com/ai%C2%B3-theory-practice-business/reinforcement-learning-part-6-td-%CE%BB-q-learning-99cdfdf4e76a)" by "[Dan Lee](https://medium.com/@Adline125)"


#### 04. Monte Carlo Predicition: 
The Monte Carlo method is used for policy evaluation for OpenAI Gyms Blackjack environment.

#### 05. Monte Carlo Control:
The Monte Carlo Control method is implemented for achieving optimal policy in OpenAI Gyms Blackjack environment.

#### 06. SARSA - On Policy TD Control
Core Mathematical Equation:

$$
Q(S_t, A_t) \leftarrow Q(S_t, A_t) + \alpha[R_{t+1} + \gamma Q(S_{t+1}, A_{t+1}) - Q(S_t, A_t)]
$$

#### 07. Q-Learning: Off Policy Control
Core update equation:

$$
q(s_t, a_t) \leftarrow q(s_t, a_t) + \alpha[R_{t+1} + \gamma . argmax_{a\prime}q(s\prime_{t+1}, a\prime) - q(s_t, a_t)]
$$

#### 08. Deep Q-Network:
I planned to have an exact implementation of the official PyTorch tutorial titled: [Reinfrocement Learning (DQN) Tutorial](https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html). However I ran into issues while trying to implement the code. 

