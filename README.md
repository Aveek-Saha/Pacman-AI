# Pacman-AI
A repository for the Solutions for the PacMan assignment from Berkley.

The original assignment: https://inst.eecs.berkeley.edu/~cs188/sp22/projects/

# Projects

## Project 1: Search
Implemented depth-first, breadth-first, uniform cost, and A* search algorithms.

## Project 2: Multiagent
Implemented minimax, expectimax and alpha-beta pruning

# Usage

To run the repo for yourself, clone it and follow the steps below:

Create a new conda env with python 3.6

```
conda create --name pacman python=3.6
conda activate pacman
```

Go to the section you want to run (search/multiagent/etc.)
```
cd search
```

To run the questions:
```
python autograder.py -q q1
python autograder.py -q q2 --no-graphics
```

To run the autograder:
```
python autograder.py
```