# CMPS458 — Assignment 2

## Policy Iteration on a Custom Grid Maze

This project implements Policy Iteration in a custom 5×5 Grid Maze using Python and Gymnasium.

The agent learns a policy to reach the goal while avoiding two obstacles.

## Requirements

- Python
- Gymnasium
- NumPy
- Pygame
- Matplotlib
- imageio-ffmpeg
- MoviePy

## How to Run

1. Install the required Python packages.
2. Open the Jupyter Notebook.
3. Run all cells in order.
4. Review the policy map, evaluation results, and recorded videos.

## Results

For the maze generated with seed 38:

- Discount factor: 0.95
- Convergence threshold: 1e-10
- Policy iterations: 4
- Evaluation sweeps: 495
- Success rate: 100% (22/22 valid starting states)
- Average steps: 2.73

These results correspond to the recorded maze layout and configuration.
