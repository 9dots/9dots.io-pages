---
author: danleavitt0
views: 0
published: false
type: lesson
blurb: "Students learn to create their own Javascript functions by generating a function to turn right in the spaceman challenges. Once they learn how to create functions, students continue by creating their own function to help solve the mazes with fewer lines of code."
org: 9dots
objective: 
  - Explain that a function is a reusable algorithm
  - Use proper syntax to define a Javascript function
  - Create original Javascript functions
image: "http://uploads.9dots.io/Ol3wSSM_md.jpg"
id: "9dots-Oiybdio"
title: Javascript Programming 3
fullImage: "http://uploads.9dots.io/Ol3wSSM_lrg.jpg"

---

## Setup

### Materials

- Computer
- Powerpoint

### Lesson Time

- 45 minutes

## Engage/Explore - 15 minutes

Students go to www.getcoding.io and play the Spaceman Function levels.

## Explain - 10 minutes

1. Review with students by asking, “What is a function?”
	- A function is a piece of code that can be called to complete a certain task.

2. So far, students have been using function calls to move the spaceman around.

3. Each function is an algorithm (set of instructions) that be used many times by calling that function.

4. Ask students, “What are the functions that are provided with spaceman?”
	- move();
	- rotate();
	- getPart();

5. Ask students, “What do you have to do to turn right in a spaceman level?”
	- The rotate() function turns the spaceman to the left. To turn to the right, the rotate function needs to be called 3 times.

6. Instead of having to write `rotate(); rotate(); rotate();` every time a right turn is required, student can create a function to turn right.

7. How to define a function
	1. To define a function, start with the word “function” 
	2. The word is followed by the name of the function (which can be anything since it is your own function).
	3. In this example, name the function “turnRight”
	4. After the name, add parentheses ()
	5. After the parentheses an open curly brace is written on the same line and then a closed curly brace on the line below.
	6. It should look like:
    ![](http://uploads.9dots.io/P3GBAZi_md.jpg) 
	7. The code that should be executed when the function is called goes between the curly braces.
	8. Ask students, “What is the code that the function turnRight should perform?”
		- The function should call the `rotate()` function three times.
	9. On a piece of paper, students write the a function called turnRight with the code it should execute.
	10. When it is finished the function should look like this:
    ![](http://uploads.9dots.io/P3GKsIh_md.jpg) 

8. To use this function, simply call it like any of the other functions that have been used so far. An example could look like this:
![](http://uploads.9dots.io/P3GL9K7_md.jpg) 

9. On the first level of the Spaceman Functions game, students create this turnRight function and use it to solve the maze.

## Elaborate - 15 minutes

Students do the Spaceman Function levels again but this time they need to use at least one original javascript function on each level.

Example of some javascript functions they could create are:

- A function that does a move() two times
- A function that does a move() and a rotate()
- A function that does a move() and getPart()

## Evaluate - 5 minutes

Ask students some follow up questions

- What is a function?
- How do you call a function?
- How do you define a function?
- What is the best original function you wrote to solve a level?
