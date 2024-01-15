---
layout: page
title: Algorithms Course Projects
permalink: /projects/algorithms/
---

For my Algorithms course at the University of San Diego, I worked with a partner on four primary projects:

<h3><a href = "https://github.com/christiangideon/comp480-algorithms/blob/main/comp480-sp23-pa1-group5/pa1.py" target = "_blank"><u>Modified Gale-Shapley Problem</u></a></h3>

In this project, I created code to find a solution to the stable matching problem - between two sets of elements that have "matching preferences", no two elements will prefer each other over the match they were currently assigned. In this scenario, I made hospitals match with new nurses in terms of preferences. There were three additions to the <a href = "https://en.wikipedia.org/wiki/Gale%E2%80%93Shapley_algorithm" target = "_blank"><u>base Gale-Shapley algorithm</u></a>:

1. Each hospital can have any number of positions available, not necessarily all the same.
2. A hospital can find some students unacceptable, and a student can find some hospitals unacceptable (rather than simply having a low preference ranking).
3. There can be an unequal number of available positions and students.

You can check out my solution to this problem <a href = "https://github.com/christiangideon/comp480-algorithms/blob/main/comp480-sp23-pa1-group5/pa1.py" target = "_blank"><u>here</u></a>.


<h3><a href = "https://github.com/christiangideon/comp480-algorithms/blob/main/comp480-sp23-pa2-group5/pa2.py" target = "_blank"><u>Red-Black Tree Problem</u></a></h3>

The code for this project uses a Red-Black Tree (RBTree) to solve a problem which involves two lists of paired numbers (tuples) which need to be reordered:

- For both lists of pairs, the first number in each pair must tie in order or increase chronologically (for instance: [<u>1</u>, 2], [<u>1</u>, 1], [<u>2</u>, 3])
- When comparing the two lists, the second number in a pair from the first list must be greater than the second number in a pair from the second list

Below is a proper listing of pairs which are ordered correctly by the two rules above. Above and below the middle horizontal line are where pairings are found, while the line signifies the divide between the two lists (so [10, 11] from the first list matches up accordingly with [40, 10] from the second list - and so on).

|10|10|10|10|
|11|12|13|8|

-----

|40|40|40|50|
|10|11|12|7|

The ultimate goal of this program was to reorder the lists according to these rules using an RBTree. <a href = "https://github.com/christiangideon/comp480-algorithms/blob/main/comp480-sp23-pa2-group5/pa2.py" target = "_blank"><u>My solution can be found here</u></a>.

<a href = "https://github.com/christiangideon/comp480-algorithms/blob/main/comp480-sp23-pa2-group5/pa2.py" target = "_blank"><img src="/docs/assets/pa2_walkthrough.jpg" alt="A picture walking through the steps for the algorithm to solve the RBTree problem described above."/></a>


<h3><a href = "https://github.com/christiangideon/comp480-algorithms/blob/main/comp480-sp23-pa3-group5/pa3.py" target = "_blank"><u>Stone-Grid Optimization Problem</u></a></h3>

The problem to solve here was about finding an efficient way to calculate the most optimal spot to gather stones on a grid. Imagine yourself in the situation here:

You find yourself looking at a square grid with stones placed on it. If you were to stand on the grid somewhere, you want to find the best spot for you to be able to pick up as many stones as you can reach. Your arms are only so long, so you have to choose a spot that you know is best for your arm length to reach as many stones as you can within a certain distance.

<a href = "https://github.com/christiangideon/comp480-algorithms/blob/main/comp480-sp23-pa3-group5/pa3.py" target = "_blank"><u>Here is my solution to that problem</u></a> which creates a matrix based on grids with stones given as input to the code.



<h3><a href = "https://github.com/christiangideon/comp480-algorithms/blob/main/comp480-sp23-pa4-group5/pa4.py" target = "_blank"><u>Sudoku Solver Problem</u></a></h3>

For the final project, I was tasked with creating efficient code that would solve <a href = "https://en.wikipedia.org/wiki/Sudoku" target = "_blank"><u>Sudoku puzzles</u></a>. To do this, I utilized <a href = "https://www.geeksforgeeks.org/backtracking-algorithms/" target = "_blank"><u>backtracking</u></a> to successfully solve sudoku problems that were of size 9x9 or 16x16 grids. <a href = "https://github.com/christiangideon/comp480-algorithms/blob/main/comp480-sp23-pa4-group5/pa4.py" target = "_blank"><u>Click here for my solution</u></a>.


<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
</style>
</head>
<body>

<a href = "https://github.com/christiangideon/comp480-algorithms/blob/main/comp480-sp23-pa4-group5/pa4.py" target = "_blank"><img src="/docs/assets/sudokusmall.png" alt="A picture of a handwritten sudoku problem, unsolved."/></a>

</body>
</html>