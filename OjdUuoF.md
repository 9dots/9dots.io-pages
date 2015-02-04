---
author: danleavitt0
views: 0
published: false
type: lesson
title: Javascript Programming 4
blurb: ""
org: 9dots
objective: 
  - Define a programming loop
  - Explain what a conditional is
  - Write a while loop and an if statement using proper Javascript syntax
  - Develop code that incorporates loops and conditionals
id: "9dots-OjdUuoF"
image: "http://uploads.9dots.io/Ol46jjh_md.jpg"
fullImage: "http://uploads.9dots.io/Ol46jjh_lrg.jpg"

---

## Setup

### Materials

- Computer
- Powerpoint

### Lesson Time

- 45 minutes

## Engage/Explore - 15 minutes
Today students programs are getting smarter by using loops and conditionals.

1. Loops are segments of code that repeat whatever is inside of them.
	- For example, “while there are more parts” will keep repeating whatever comes next until there is no more parts.

2. Conditionals choose between two options.
	- For example, “If there is a path to the left, rotate” will rotate the spaceman when there is a possible path in that direction

3. Students go to www.getcoding.io and play the Spaceman Loops Blockly levels.

## Explain - 10 minutes

1. These levels show the power of being able to use loops and conditionals to solve a coding problem.

2. The loop that student have been using in Blockly is called a while loop.
	- The while loop keeps repeating until a condition is met (it becomes true)

3. To write a while loop in Javascript
	1. Start by writing the word ‘while’
	2. In parentheses give the condition to keep going
	3. In this case there is a function called notOnPart() that checks if the Spaceman has made it to the part
	4. Add curly braces
	5. The code between the curly braces is repeated while there are still more parts to gather
	6. The finished while statement should look like this: 
	7. This means that while the spaceman is not on a part, the spaceman continues to call the move function

4. To write a conditional in Javascript
	1. Write the word ‘if’
	2. In parentheses write the condition to check for
	3. In this case there is a function called pathLeft() that checks to see if there is an available path on the left for the spaceman to take
	4. Add curly braces
	5. The code between the curly braces is what is executed when the condition is true
	6. The finished conditional should look like this:
	7. This code means that if there is a path to the left, the spaceman should rotate

5. To combine the two, simple put the if statement in the while loop.

6. Ask students what this code will do.

	1. While the spaceman is not on a part (repeats until the spaceman is on a part)
		1. move forward
		2. if there is a path to the left
		3. rotate to turn towards that path


## Elaborate - 15 minutes

1. Students play the www.getcoding.io and play the Spaceman Loops levels
2. In each level, students write down the number of lines of code it took them to solve each level. Students should be aiming to write as few lines as possible.

## Evaluate - 5 minutes
Ask students some follow up questions.

- What is a conditional?
- What is a while loop?
- What goes in the parentheses of a while loop?
