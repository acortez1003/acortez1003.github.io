---
title: "Sudoku Solver Web App"
excerpt: "**Try live demo: [https://sudoku-solver-acortez.vercel.app/](https://sudoku-solver-acortez.vercel.app/)**<br />
Fully responsive and interactive Sudoku Solver web application built with React and Vite. It allows users to generate or input a puzzle to learn Sudoku through a built-in hint system. [*repo*](https://github.com/acortez1003/sudoku-solver)<br />
<div style='text-align: center;'><img src='/images/sudoku_solver.png' style='max-width: 100%; width: 275px; height: auto;'></div>"
collection: portfolio
---

## Project Overview
This is a fully responsive and interactive Sudoku Solver web application built with **React** and **Vite**. It allows users to solve and learn how to play Sudoku through a built-in hint system.

This project is designed for both casual players and learners. It includes custom puzzle generation, real-time validation, and a step-by-step hint system for solving.

## Key Features

### Solver
<div style="text-align: center;">
  <img src='/images/sudoku_generate.gif' style="width: 150px; height: auto;" />
</div>
* Automatically solves user-inputted or generated puzzles using a recursive backtracking algorithm.
* Includes input validation and conflict highlighting as per Sudoku rules. (Unique value in each row, column, box)

### Pencil Marks & Editing
<div style="text-align: center;">
  <img src='/images/sudoku_conflict.gif' style="width: 250px; height: auto;" />
</div>
* Enables dynamic pencil markings when Hints are applied  
* Changes pencil markings based on puzzle state as the game progresses.

### Hint System
<div style="text-align: center;">
  <img src='/images/sudoku_hint.gif' style="width: 200px; height: auto;" />
</div>
* Offers step-by-step hints that demonstrate real solving strategies such as:
    * Naked Singles / Pairs
    * Hidden Singles / Pairs
    * Candidate elimination

### User Interaction
<div style="display: flex; justify-content: center; gap: 10px; flex-wrap: wrap;">
  <img src='/images/sudoku_match.gif' style="width: 150px; height: auto;" />
  <img src='/images/sudoku_erase.gif' style="width: 150px; height: auto;" />
</div>
* Responsive UI with number pad, eraser, reset, and undo functionality.  
* Highlights matching numbers and selected cells to improve clarity.

### Fully Responsive
* Optimized for both desktop and mobile screens with flexible layouts.

## Tech Used
* React with Vite
* JavaScript, CSS
* Deployed via Vercel