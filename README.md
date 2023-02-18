# 8-puzzle-node
I implemented a Python program that rearranges numbers in a 3 by 3 block in their correct order using the A* search algorithm and using the manhattan displacement and misplaced tiles heuristics.
# Project Description
The 8 puzzle game is a classic sliding puzzle game that is played on a 3x3 grid with 8 numbered tiles and one empty space. The objective of the game is to rearrange the tiles by sliding them into the empty space until they are in numerical order.

In this version of the game, I have created an agent in Python that uses the A* search algorithm with misplaced tiles and Manhattan displacement heuristics to solve the puzzle. A* search is a widely used algorithm for finding the shortest path between two points in a graph. It is an informed search algorithm that uses both the cost to reach a particular node and an estimate of the remaining cost to reach the goal.

The misplaced tiles heuristic estimates the number of tiles that are not in their correct position and uses that as a measure of how far away the agent is from the goal state. The Manhattan displacement heuristic estimates the total Manhattan distance of each tile from its correct position and uses that as a measure of how far away the agent is from the goal state. These heuristics help the agent to prioritize its search for the most promising paths and avoid getting stuck in dead-ends.

My agent is able to use these heuristics to solve the 8 puzzle game efficiently and effectively. It analyzes the current state of the puzzle and calculates the potential costs of each move, selects the move with the lowest cost, and repeats this process until the puzzle is solved. The agent is able to solve even the most complex puzzles by navigating the search space in a smart and optimized manner.

Overall, this version of the 8 puzzle game provides a fun and challenging experience for players of all levels, and the A* search algorithm with misplaced tiles and Manhattan displacement heuristics provides a powerful way to solve this classic puzzle game.
