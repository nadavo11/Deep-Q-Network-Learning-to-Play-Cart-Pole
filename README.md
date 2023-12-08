# Neural Network Using Reinforcement Learning to Play Cart-Pole
How to build a simple neural network that can play Cart Pole by Gym, using Reinforcement Q Learning.

To calculate the loss function we are going to use a copy **Target** NN and  **bootstrapping**.

$$ Q_{compare} = R + \gamma \cdot (1-done) \cdot max \{ Q_{t+1}  \}$$

$$ loss = (Q_{compare} - Q_{t})^2 $$

so we will use the MSE loss function:

$$ loss = nn.MSELoss(Q_{compare},Q_{t}) $$

#AI #RL #QLearning #NN #GYM #CartPole

