## Reading

1. Q-Learning  
- https://en.wikipedia.org/wiki/Q-learning

2. Convergence of Q-Learning: A Simple Proof  
http://users.isr.ist.utl.pt/~mtjspaan/readingGroup/ProofQlearning.pdf

It will be a good exercise to work through this proof.  
This should give a good understanding of the mathematics and justification for Q-Learning.  

Some important concepts that should be reviewed:  
- A *fixed point* is a point that does not change upon application of a map
- A *contraction* maps points closer together  
  One potential reference: https://www.math.ucdavis.edu/~hunter/book/ch3.pdf

The fixed point in this case is the optimal policy. Repeated application of the contraction map brings  
the policy to optimality.

There are two typos in the paper:  
1. page 2. To see this we write $||Hq_1 - Hq_2 || = ...$ Final term should have negative sign: $-\gamma \text{ max } q2(y,b)$

2. Proof of Theorem 1: yields $\Delta_t$ should be $\Delta_{t+1}$
