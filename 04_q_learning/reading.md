## Reading

Q-Learning  
- https://en.wikipedia.org/wiki/Q-learning

Convergence of Q-Learning: A Simple Proof  
http://users.isr.ist.utl.pt/~mtjspaan/readingGroup/ProofQlearning.pdf

It will be a good exercise to work through this proof.  
This should give a good understanding of the mathematics and justification for Q-Learning.  

Some important concepts that should be reviewed:  
- A *fixed point* is a point that does not change upon application of a map
- A *contraction* maps points closer together  
  One potential reference: https://www.math.ucdavis.edu/~hunter/book/ch3.pdf

The fixed point in this case is the optimal policy. Repeated application of the contraction maps brings  
the policy to optimality.

There are two typos in the paper:  
1. page 2. To see this we write $||Hq_1 - Hq_2 || = ...$ Final term should have negative sign: $-\gamma q2(y,b)$

2. Proof of Thm 1: yields $\delta_t$ should be $\delta_t+{1+1}$