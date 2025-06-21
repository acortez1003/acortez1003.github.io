---
title: "Sudoku Solver Web App"
excerpt: "*Try live demo: [https://sudoku-solver-acortez.vercel.app/]*(https://sudoku-solver-acortez.vercel.app/)<br />Fully responsive and interactive Sudoku Solver web application built with React and Vite. It allows users to generate or input a puzzle to learn Sudoku through a built-in hint system. [*repo*](https://github.com/acortez1003/sudoku-solver)<br /><img src='/images/sudoku_solver.png' style='max-width: 100%; width: 150px; height: auto;'>"
collection: portfolio
---

## Project Overview
This is a fully responsive and interactive Sudoku Solver web application built with **React** and **Vite**. It allows users to solve and learn how to play Sudoku through a built-in hint system.

This project is designed for both casual players and learners. It includes custom puzzle generation, real-time validation, and a step-by-step hint system for solving.

## Key Features

### Solver
<img src='/images/sudoku_generate.gif' style="text-align: center; max-width: 100%; width: 100; height: auto;">
* Automatically solves user-inputted or generated puzzles using a recursive backtracking algorithm.
* Includes input validation and conflict highlighting as per Sudoku rules. (Unique value in each row, column, box)

### Pencil Marks & Editing
<img src='/images/sudoku_conflict.gif' style="text-align: center; max-width: 100%; width: 100px; height: auto;">
* Enables dynamic pencil markings when Hints are applied
* Changes pencil markings based on puzzle state as the game progresses.

### Hint System
<img src='/images/sudoku_hint.gif' style="text-align: center; max-width: 100%; width: 100px; height: auto;">
* Offers step-by-step hints that demonstrate real solving strategies such as:
    * Naked Singles / Pairs
    * Hidden Singles / Pairs
    * Candidate elimination

### User Interaction
<div style="text-align: center; max-width: 100%; width: 100px; height: auto;">
    <img src='/images/sudoku_match.gif'>
    <img src='/images/sudoku_erase.gif'>
</div>
* Responsive UI with number pad, eraser, reset, and undo functionality.
* Highlights matching numbers and selected cells to improve clarity.

### Fully Responsive
* Optimized for both desktop and mobile screens with flexible layouts.

## Tech Used
* React with Vite
* JavaScript, CSS
* Deployed via Vercel