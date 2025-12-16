
# A Reinforcemnt Learning FX Trading AGent
---------------------------------------------

A Reinforcement Learning FX Trading Agent with a Dueling Double Deep Q-Network Architecture.
The Agent also used a Prioritized Experience Replay mechanism to update its policies during training.

The Agent is trained on 900 rows of EURUSD data, and later backtested on 362 rows of unseen trading days.

In the render link below, the Agent has been packed into a flask webapp:
https://rl-agent-eat0.onrender.com/
simulating the Agent's actions on the 362 unseen trading days.
