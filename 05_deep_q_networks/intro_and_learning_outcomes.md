
## INTRODUCTION TO THE MODULE

Q-learning is a very powerful offline algorithm, but its use of a table is limiting: when the state space is large, there is a difficulty in storing the Q-values. Deep Q Networks (DQNs) use deep neural networks as a function approximation. The network takes (state, action) combinations and outputs a Q-value. This will work for continuous state space and thus it serves as an interpolation method. The challenge is that convergence is no longer guaranteed, and several tricks need to be implemented for things to work. In this module, we will learn about DQN approaches and code them using a neural network framework.


## LEARNING OUTCOMES

At the conclusion of this module, you should be able to:

- Explain the novel ideas behind Q-Networks
- Explain the new challenges brought with Q-Networks
- Explain the purpose of experience replay and implement it in code
- Explain the purpose of a target network and implement it in code



