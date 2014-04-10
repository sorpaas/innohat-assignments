# Innohat Interview Assignment: All RGB in One Image
*10th April, 2014*

## Introduction
In this assignment, your task is to *build a website of your favourite all-RGB-colours-in-one-image in Haskell*. 

## Requirements
Here are some requirements for this task. In brief, you will first design the algorithm, and then show the generated images in a website with some simple functions.

### The Algorithm
The algorithm problem description of this assignment is similar to [the question on StackExchange](http://codegolf.stackexchange.com/questions/22144/images-with-all-colors) and [this website](http://allrgb.com). A short description is as follows:

> Make images where each pixel is a unique color (no color is used twice and no color is missing).
> 
> Give a program that generates such an image, along with a screenshot or file of the output (upload as PNG).
> 
> * Create the image purely algorithmically.
> * Image must be 256×128 (or grid that can be screenshot and saved at 256×128)
> * Use all 15-bit colors*
> * No external input allowed (also no web queries, URLs or databases)
> * No embedded images allowed (source code which is an image is fine, e.g. Piet)
> * Dithering is allowed

However, the parts shown as follows are different:

1. The algorithm should be written **in [Haskell](http://en.wikipedia.org/wiki/Haskell)**.
2. The algorithm should be able to generate different images **randomly (or by random input)**.
3. The algorithm should be able to generate **beautiful** images.
4. You can take others algorithm as references, but please don't copy them.

### The Generating Script
After you have compiled the Haskell program, write a script that calls the program to continuously generate images. If you use Unix, you may simply use shell script to do it.

### The Web Application
Build a simple web application **in Haskell** with 2 functions:

1. Show 2 generated images at a time, and let people vote for their favourite.
2. Show the result for people's voting.

## Logistics
1. The assignment will last for 4 hours, testing your learning ability of programming. You are welcome to leave early if you feel confident about the assignment.
2. Please use source version control tools (such as **git**) during the whole process and make regular commit for us to track your process.
3. You can use Internet and any other things during the whole process, but please don't copy others' work.
4. You can approach the interviewers for help if you meet any problem during the assignment.
5. We will do regular check in during the whole interview process.
6. All assignment code should be open sourced after the interview under [MIT License](http://opensource.org/licenses/MIT) for review.

*Innohat, Inc.*
