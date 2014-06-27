---
author: danleavitt0
views: 0
published: false
type: lesson
title: Introduction to Programming and Basic Robot Features
blurb: This lesson will provide students with a basic knowledge of the programming process and introduce them to the Lego Mindstorm software
org: 9dots
objective: "By the end of the lesson, students will be able to write a program capable of navigating their robot through a simple maze"
id: "9dots-OiQXe4e"
image: "http://uploads.9dots.io/OiQaXZD_md.jpg"

---

## Materials:
- Lego Mindstorm EV3 kit
- Computer with EV3 software
- Teacher-created maze (black electrical tape on the floor works well)
- Completed Mindstorm robot from lesson 1 (instructions)

## Media and Handouts:
- Programming Introduction Video
- Handout for robotic behaviors  
- Iteration and wrap-up handout

## Project time:
1 hr 15 min
    
## Lesson
### DISCUSS: 
_What do programmers do?_
Programmers give detailed instructions to computers to solve problems and accomplish tasks.  

### WATCH:
Show the Programming Introduction Video.

### GOAL: 
Tell students that their goal is to create a robot that is capable of pushing a lego through a maze without crossing any of the lines. 
```
TIP: Make sure to start the robot in the exact same place each time. Placing an extra piece of tape in the starting area to mark the correct position can help ensure consistency.
```

![](http://uploads.9dots.io/OiQa9tW_md.jpg) 
**Above: An example of what the maze could look like. The robot will have to push the lego from the green ‘Start’ zone to the red ‘Finish’  zone without crossing the lines.**

### EXPLAIN:
A robot attachment is an additional part made out of legos that can easily be connected to the robot to help complete a specific goal. To push legos, students will need to build an attachment that keeps legos from getting trapped under the robot or lost while turning.

![](http://uploads.9dots.io/OiQb3yI_md.jpg) 
**Above: An attachment for pushing the legos.**

### DISCUSS: 
_The attachment will allow the robot to push the legos, but how will the robot know what to do?_
The robot needs to be programmed to accomplish the goal of getting through the maze.

### CHECK FOR UNDERSTANDING: 
_What does programming mean?_
Programming means giving the computer detailed instructions to solve problems.  In robotics, these instructions are called behaviors.

### IN-DEPTH: 
Pass out the Behaviors handout and discuss simple and complex behaviors in robotics.

### DISCUSS: 
_Is navigating the maze a simple or complex behavior?_
Going through the maze is complex because it is made up of several different programmable steps.

### GROUP UP: 
Break into groups of no more than four students. 

**The Game:**
Students have 5 minutes to program the teacher robot (you) to go through the robot maze. The teacher robot only understands the simple behaviors:

1. Move Straight (1 step forward)
2. Turn Left (90 degrees)
3. Turn Right (90 degrees)
 
Students should write down their instructions on a piece of paper. After students have their instructions written down, students will state the instructions to the you, the teacher robot. When behaving as the robot, make sure to follow the instructions very literally.

### EXPLAIN: 
To program the Mindstorm Robot, students will use the same 3 simple behaviors; move straight, turn left, and turn right. In the Mindstorm EV3 software, to program the robot, drag blocks from the bottom bar and connect them to the start block that is on the screen. The three behaviors that have been discussed are all achievable using the Move Steering block.

![](http://uploads.9dots.io/OiQbdRA_md.jpg) 

The 3 parts of the Move Steering block are:

1. *Turning:* Positive numbers turn right, Negative numbers turn left, and 0 means straight.
2. *Power:* How fast the motor will spin. 0 is the slowest; 100 is the fastest.
3. *Duration:* How long the motor will turn on for in rotations. 1 rotation is one full spin of the motor.

![](http://uploads.9dots.io/OiQc16D_md.jpg) 

To make a complex behavior, connect as many Move Steering blocks (simple behaviors) together as are required.

![](http://uploads.9dots.io/OiQcewv_md.jpg) 

Demonstrate how to download a program to the robot. A how to on downloading programs to the EV3 can be found in the Wiki section of 9dots.io.

### GROUP UP: 
Groups should be as small as possible with one computer per group. 

### PROGRAM: 
Each team has 35 minutes to build an attachment and program their robot to complete the maze. Students should use their program (the written down instructions) from the ‘teacher robot’ activity to help with organizing the behaviors for the actual maze challenge.

### RUN CODE: 
Students may test their robot at any point. After each attempt, students should write down what worked and what they should change using this handout. 

### CHALLENGE: 
At the end of the allotted time, each group will test their robot by running it through the maze.

### EXPLORE FURTHER: 
If a group finishes early, they can attempt to do the entire maze backwards. Let students figure out how to program the robot to move backwards on their own. To move backwards the power needs to be set to a negative number.
```
TIP: 
The robots turns will differ slightly with battery life so students may need to adjust their programs accordingly.
```
### DISCUSS:
_Did any students use different strategies for programming their robots?_
When programming, there are often multiple solutions to the same problem.

_How many blocks did you use to program your robot?_
In programming, it is advantageous to write as few steps as possible.

_What is the difference between a simple and a complex behavior?_
A simple behavior is a single programmable action, a complex behavior is made up of two or more simple behaviors.
