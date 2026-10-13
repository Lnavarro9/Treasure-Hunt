# Pirate Intelligent Agent: Deep Q-Learning Treasure Hunt

## Project Overview
This project features an intelligent agent designed to navigate a grid-world maze and find the treasure before the pirate runs out of moves or encounters a trap. Developed using **Deep Q-Learning (DQN)**, the agent leverages neural networks and reinforcement learning to map out optimal paths and maximize its cumulative rewards.

### Code Distribution
* **Provided Code (`TreasureMaze.py`, `GameExperience.py`, and base notebook skeleton):** 
  The course provided the foundational environment framework, including the maze grid representation, action definitions (left, right, up, down), observation states, and the experience replay buffer structure (`GameExperience`).
* **Created Code (`qtrain()` algorithm implementation):** 
  I engineered the core Deep Q-learning training algorithm (`qtrain`), implementing epsilon-greedy exploration/exploitation logic, experience tracking, minibatch data retrieval, and gradient descent optimization steps using TensorFlow and Keras to train the agent to a 100% completion win rate.

---

## Computer Science Connections

### What do computer scientists do and why does it matter?
Computer scientists analyze complex, real-world problems and engineer algorithmic systems that automate tasks, optimize efficiency, and enable machines to learn from their environments. This matters because intelligent systems—such as reinforcement learning agents—drive modern technological advancements in automation, robotics, logistics, and artificial intelligence, solving problems that are too intricate for static programming.

### How do I approach a problem as a computer scientist?
I approach technical challenges systematically by:
1. **Defining the Scope and Objectives:** Establishing clear success metrics (e.g., achieving a 100% win rate and passing rigorous maze-completion checks).
2. **Deconstructing the Problem:** Breaking the project down into manageable components, such as understanding state-action spaces, configuring the experience replay buffer, and structuring neural network layers.
3. **Iterative Development and Testing:** Writing modular code, monitoring real-time metrics (like loss reduction and win rates), and tuning hyperparameters (like epsilon decay and memory size) to optimize performance.

### What are my ethical responsibilities to the end user and the organization?
As a computer scientist, I hold a responsibility to design systems that are secure, reliable, transparent, and safe. In the context of automated or AI-driven systems, this means ensuring that models are rigorously tested to prevent unpredictable failures, safeguarding data privacy, avoiding algorithmic bias, and ensuring autonomous systems operate safely within predefined boundaries without causing unintended harm.

---

## Technologies Used
* **Python**
* **TensorFlow / Keras**
* **NumPy**
* **Matplotlib**
