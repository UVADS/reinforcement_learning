## DS 7540 Machine Learning IV - Reinforcement Learning: Agenda 21


### Upcoming Deliverables

- Lab 5: Cart Pole 2 with Policy Gradients. Due Apr 4.
- Quiz 5: Policy Gradients and Extensions. Due Apr 4.


---

### Content


- Finish Actor Critic [lab](https://github.com/Lucasc-99/Actor-Critic/tree/master).

  - Look at the function `compute_loss()` in the file `/src/a2c.py`  
    It takes parameter `critic_loss=nn.SmoothL1Loss()`
    - If you modify this to use `nn.MSELoss()` does it seem to make a difference?   

- Review Extensions of [Policy Gradient](https://github.com/UVADS/reinforcement_learning/blob/main/08_policy_gradients_extensions/policy_gradients_extensions.ppt)
  - TRPO overview
  - PPO overview

- [Time permitting] Keras Cart Pole with [PPO](https://keras.io/examples/rl/ppo_cartpole/)
  - Review and run the code
  - Discuss and answer these [questions](https://github.com/UVADS/reinforcement_learning/blob/main/08_policy_gradients_extensions/keras_ppo_discussion_questions.txt)
