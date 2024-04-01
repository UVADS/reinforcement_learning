## DS 7540 Machine Learning IV - Reinforcement Learning: Agenda 28


### Admin Items
  
---

### Upcoming Deliverables

- Lab 5: Cart Pole 2 with Policy Gradients. Due Apr 1.
- Quiz 5: Policy Gradients and Extensions. Due Apr 8.


---

### Content

- In class [lab](https://github.com/Lucasc-99/Actor-Critic/tree/master)

  - clone into Colab:
  - ! git clone https://github.com/Lucasc-99/Actor-Critic.git

  - Review the code for understanding
  - Run the script `/scripts/cart-pole-a2c.py`
    - Does it work?
    - Does it solve the task?

  - Look at the function `compute_loss()` in the file `/src/a2c.py`  
    It takes parameter `critic_loss=nn.SmoothL1Loss()`
    - If you modify this to use `nn.MSELoss()` does it seem to make a difference?     
 

