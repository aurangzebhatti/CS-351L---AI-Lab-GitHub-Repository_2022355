University Exam Scheduling Using Graph Coloring and Backtracking

Overview

This project implements a university exam scheduling system using a graph coloring algorithm combined with backtracking. The goal is to assign time slots to exams such that no two exams that share common students are scheduled at the same time. The scheduling process is optimized using two heuristic approaches: Minimum Remaining Values (MRV) and Degree Heuristic.

Features

Graph Representation: Exams are represented as nodes, and edges represent conflicts (exams that share common students).
Backtracking Algorithm: A recursive algorithm is used to assign time slots to exams, ensuring no conflicts.
Heuristics:
Minimum Remaining Values (MRV): Prioritizes exams with fewer available time slots.
Degree Heuristic: Prioritizes exams with the highest number of conflicts.
Visualization: The scheduling process is visualized step by step, showing the current exam assignments to time slots.
Requirements

Python 3.x
Libraries:
networkx for graph representation
matplotlib for visualization
