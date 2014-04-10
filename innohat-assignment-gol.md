# Innohat Interview Assignment: Gist for "Game of Life"
*10th April, 2014*

## Introduction
In this assignment, your task is to *make a modern implementation for [Conway's Game of Life](http://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)* using Clojure and ClojureScript.

## Requirements
Here are some requirements for this task. In brief, you will first implement Conway's Game of Life rules in HTML/ClojureScript, and then store and process the "world data" by implementing a web application in Clojure.

### The Conway's Game of Life Rules
The basic Conway's Game of Life (short for GOL) rules are as follows. *(From [Wikipedia](http://en.wikipedia.org/wiki/Conway%27s_Game_of_Life))*

> The universe of the Game of Life is an infinite two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, alive or dead. Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:
> 
> 1. Any live cell with fewer than two live neighbours dies, as if caused by under-population.
> 2. Any live cell with two or three live neighbours lives on to the next generation.
> 3. Any live cell with more than three live neighbours dies, as if by overcrowding.
> 4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.
> 
> The initial pattern constitutes the seed of the system. The first generation is created by applying the above rules simultaneously to every cell in the seed—births and deaths occur simultaneously, and the discrete moment at which this happens is sometimes called a tick (in other words, each generation is a pure function of the preceding one). The rules continue to be applied repeatedly to create further generations.

When accessing your implementation from a web browser, we should expect things as follows:

1. The GOL world should be a rectangle with fixed number of cells.
2. The GOL world should be able to be "started" and generate next round of cells automatically.
3. The GOL world should be able to be paused.

You should **use [Hoplon](http://hoplon.io/)** to implement this part. Check out [Hoplon Demos](https://github.com/tailrecursion/hoplon-demos) to get a sense for it.

### Gist for the Game of Life
You should **continue to use Hoplon** or **use other Clojure tools** to create a simple web application. We should expect functions as follows:

1. The data of the GOL world should be stored in a database.
2. You should be able to pause a GOL world and edit the cell states.
3. When editing the cell states, you should be able to change the size of the world.
4. You should be able to fork (i.e. copy and create new) world.
5. Editing a world should create a new commit (i.e. old world before editing should still be able to be accessed).

## Logistics
1. The assignment will last for 4 hours, testing your learning ability of programming. You are welcome to leave early if you feel confident about the assignment.
2. Please use source version control tools (such as **git**) during the whole process and make regular commit for us to track your process.
3. You can use Internet and any other things during the whole process, but please don't copy others' work.
4. You can approach the interviewers for help if you meet any problem during the assignment.
5. We will do regular check in during the whole interview process.
6. All assignment code should be open sourced after the interview under [MIT License](http://opensource.org/licenses/MIT) for review.

*Innohat, Inc.*

