# Final Project : Sampling Based Navigation
## Submitted by : Ashit Mohanty (C13582787), Huzefa Kagalwala, Rahil Modi, Rakshitaa Mohan

### 1) Problem Statement
The project deals with implementing RRT (Rapidly-exploring Random Tree) algorithm for planning the path of a non-holonomic car (Dubin’s car model) to move from initial state to goal state.

### 2) Phases
In the build phase, the initial state is first added to the tree. The  random nodes are generated and connected to the tree.

In the extend phase, the nearest node (from RRT) to the random node generated is found. The new node is generated by propagating the neighbour node along the direction of random node by a set distance.
The new node is added to the tree after checking for collision. If the new node added is the goal node, then the RRT stops building.

### 3)Instruction
The following command needs to be executed to run the program,
`python CPSC8810_Final_Project_Code_RRT_Dubins.py`

 
