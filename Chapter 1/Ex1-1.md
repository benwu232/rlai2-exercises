# Exercise 1.1: 

## Question:

Self-Play Suppose, instead of playing against a random opponent, the reinforcement learning algorithm described above played against itself, with both sides learning. What do you think would happen in this case? Would it learn a different policy for selecting moves?

## Answer:
Because the randomness of exploration and exploitation, the two sides are slightly different in each game, which probabliy lead to winning and losing and different values. If we choose winner to continue self-play, it should finally reach an optimal policy. 
I think an optimal policy is a local maximum value in a policy space. If there are more than one such local maximum values in the policy space, it may learn some different policies.
