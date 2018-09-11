# Policy Gradient Methods in Reinforcement Learning

This is a report on the use of policy gradient methods in Reinforcement Learning. The focus of this report is on the experimental comparison between 3 types of Actor-Critic methods. This investigation mainly revolves around the effect of the eligibility traces on Actor-Critic methods. These methods are the followings:

1.   Actor-Critic with Eligibility Traces
2.   Actor-Critic with Eligibility Traces only on the Critic but not the Actor
3.   Actor-Critic Without any Eligibility Traces using one-step returns  

The experiments are carried on the [FrozenLake](https://gym.openai.com/envs/FrozenLake-v0/) environment.

* This entire report was done using Google Colaboratory and you can view the ipython notebook [here](https://drive.google.com/file/d/1QxCC7fd5SI6nIjHU87nHTJGHHxP8PBzv/view?usp=sharing).
