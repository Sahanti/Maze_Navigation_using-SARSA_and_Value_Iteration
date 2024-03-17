**Maze Navigation using SARSA and Value Iteration**

This project implements the SARSA and Value Iteration algorithms to navigate a maze from a start position to a goal state. The maze consists of walls represented by gray lines, and the goal state is at position (6,6). The project provides functions to visualize the maze, define actions (up, down, left, right, stay), and calculate rewards for each state transition.

**Setup**
Make sure you have numpy, matplotlib, and random installed. If not, install them using pip:

bash
Copy code
pip install numpy matplotlib
Usage
Open the maze_navigation.ipynb Jupyter Notebook and run the cells to see the maze navigation using SARSA and Value Iteration algorithms.

**Algorithms**
1. **SARSA** (State-Action-Reward-State-Action): This algorithm learns the optimal policy by updating Q-values based on state-action pairs and epsilon-greedy exploration.
2. **Value Iteration**: This algorithm calculates the optimal policy by iteratively updating the value function until it converges.
   
**Visualization**
The project provides functions to visualize the maze grid, rewards, and optimal actions. The optimal actions are displayed as arrows indicating the direction to move from each state to reach the goal state.

**Note**
The goal state is represented as (6,6).
Walls are represented by gray lines.
