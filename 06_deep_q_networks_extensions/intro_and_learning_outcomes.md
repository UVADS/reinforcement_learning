
## INTRODUCTION TO THE MODULE

DQN is a powerful technique for functional approximation when the state space is continuous. In this module, we learn effective refinements to the DQN approach. Experience replay allows RL agents to remember and reuse experiences from the past. We will study prioritized experience replay (PER), which identifies and replays important transitions more frequently.

A limitation to DQN is that the max() operation tends to overstimate the Q-function. We will review the Double Q-learning approach which can be helpful in mitigating the bias. Lastly, we review Dueling Networks, which is a new architecture designed specifically for model-free RL. The dueling architecture separates state values and action advantages.


## LEARNING OUTCOMES

At the conclusion of this module, you should be able to:

- Explain how Prioritized Experience Replay works and implement it with code
- Explain the benefits of Double Q-learning and explain how it works
- Explain the benefits of Dueling networks and explain how it works
- Implement a Dueling Deep Q-learning network



