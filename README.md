🕹️ Tic-Tac-Toe with Reinforcement Learning
This project implements a self-learning Tic-Tac-Toe agent using Reinforcement Learning (specifically, a value-based approach with Temporal Difference learning). The AI learns optimal strategies by playing thousands of games against itself before facing a human player.

🚀 Features
Pure Python implementation using NumPy (no external libraries needed)

Agent vs. Agent self-play training

Human vs. Trained AI interaction

Intelligent move selection using exploration/exploitation trade-off

Policy saving and loading for persistent learning

💡 How It Works
The AI learns by assigning value scores to board states. These values are updated using rewards from wins, losses, or draws. Over time, the agent converges to an optimal strategy through self-play.

🧠 Learning Mechanism
State-Value Estimation: Assigns and updates values to board configurations.

Exploration vs. Exploitation: Controls randomness during learning.

Reward Propagation: Backpropagates rewards after each game to refine policy.
