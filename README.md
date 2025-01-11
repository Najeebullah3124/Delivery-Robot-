# Autonomous Delivery Robot

This project focuses on the development of an autonomous delivery robot capable of navigating through a city environment, delivering online grocery orders to designated locations. The robot must plan its path in a dynamic environment with obstacles and changing conditions.

## Problem Description

The task is to guide the robot through an environment represented as a grid or graph, with obstacles such as buildings, houses, and vehicles. The robot's goal is to safely deliver packages to customers while adapting to dynamic changes in the environment.

### Key Components:
- **Environment Representation**: Represent the city area as a grid (15x15), including information about obstacles and delivery points.
- **Algorithm Implementation**: Implement informed search algorithms like Best-First and A* to navigate the robot.
- **Heuristic Function**: Use Euclidean distance to calculate the distance to the goal, considering obstacles.
- **Dynamic Environment Handling**: Adapt path planning in real-time to handle changing start locations, goal locations, and vehicle positions.
- **Path Execution**: Ensure the robot avoids collisions and follows the planned path.
- **User Interface & Visualization**: Create a GUI to interact with the simulation environment and visualize the robot's movement and obstacles.

## Features

- **Informed Search Algorithms**: Best-First Search and A* Algorithm for motion planning.
- **Heuristic Function**: Euclidean distance considering obstacles.
- **Dynamic Updates**: Real-time changes in the environment (e.g., changing start/goal locations, moving vehicles).
- **Multiple Deliveries**: Robot will deliver to 5 different delivery points sequentially.
- **User Interface**: Interface to interact with the robot and visualize its path and obstacles.
- **Multiple Robot Coordination (Bonus)**: Extend the project to handle multiple robots navigating the environment without collisions.

## Libraries Used

- **matplotlib**: For visualizing the city environment and animating the robot's movement.
- **Pygame**: For game-like animations and interactive simulations.
- **Tkinter**: For creating a simple graphical user interface (GUI).
- **PyQt/PySide**: For more advanced GUI capabilities if required.

## Project Deliverables

- **Source Code**: Python code implementing the motion planning algorithm, dynamic environment handling, path execution, and simulation.
- **User Interface**: Interactive interface for controlling and visualizing the robot's movements.
- **Simulation**: A working simulation with the robot navigating through obstacles and delivering packages to the designated locations.

## Implementation Steps

1. **Environment Representation**:
   - Design the city area as a 15x15 grid with obstacles, houses, vehicles, and delivery points.
   - Visualize this environment using matplotlib.

2. **Algorithm Implementation**:
   - Implement Best-First Search and A* algorithms for motion planning.
   - Develop a heuristic function that considers Euclidean distance and obstacles.

3. **Dynamic Environment Handling**:
   - Simulate dynamic changes such as relocating the start or goal, or moving vehicles.

4. **Path Execution**:
   - Create a module to allow the robot to follow its path, avoiding collisions with obstacles.

5. **User Interface and Visualization**:
   - Develop a user interface to visualize the robot's movement and the environment.
   - Include controls to change start/goal locations and initiate deliveries.

6. **Performance Evaluation**:
   - Evaluate the performance of the motion planning algorithms in terms of optimality, execution time, and adaptability to dynamic changes.

## Bonus Task: Multi-Robot Coordination

Extend the project to handle multiple autonomous robots navigating the same environment. Implement strategies to avoid collisions and coordinate deliveries between robots.

## Usage

1. **Install Dependencies**: 
   - Install required libraries using `pip`:
     ```bash
     pip install matplotlib pygame tkinter
     ```

2. **Run the Simulation**:
   - Clone the repository and run the Python script or Jupyter notebook:
     ```bash
     python autonomous_delivery_robot.py
     ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Python libraries: **matplotlib**, **pygame**, **tkinter**.
- The development of search algorithms for motion planning.
