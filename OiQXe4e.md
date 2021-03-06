---
author: danleavitt0
views: 0
published: true
type: lesson
title: Introduction to EV3 Programming
blurb: "This lesson serves as an introduction to programming using the EV3 software (this is useable with the older NXT bricks as well). To start, students learn about what it means to be a programmer. Next, inform students that their goal for the day is to program a robot to navigate through a maze. After, students learn about simple and complex robot behaviors. To finish the lesson, students have their first programming challenge to guide their teacher through a maze using programming instructions."
org: 9dots
objective: 
  - Explain what a programmer is
  - Define a simple behavior
  - Write a program capable of navigating their robot through a simple maze
id: "9dots-OiQXe4e"
image: "http://uploads.9dots.io/Ol3tbrJ_md.jpg"
attachments: 
  - path: "http://uploads.9dots.io/OiQdggn.pdf"
    name: Behaviors.pdf
  - path: "http://uploads.9dots.io/OiQe2ix.pdf"
    name: "Dailywrap-up.pdf"
  - path: "http://uploads.9dots.io/OiQe49h.pdf"
    name: IterationLog (1).pdf
fullImage: "http://uploads.9dots.io/Ol3tbrJ_lrg.jpg"

---

# Day 1

## Setup

### Materials:

- Lego Mindstorm kit
- Computer with [EV3 Software](http://www.lego.com/en-us/mindstorms/downloads/software/ddsoftwaredownload/download-software/) 
- Teacher-created maze (black electrical tape on the floor works well)
- Completed Mindstorm [robot from lesson 1](http://www.9dots.io/9dots/OJ8iMiY)
- [Programming Introduction Video](http://www.education.rec.ri.cmu.edu/previews/robot_c_products/teaching_rc_lego_v2_preview/fundamentals/introtoprogramming/videos/fundamentals1.html)
- [Handout for robotic behaviors](http://uploads.9dots.io/OiQdggn.pdf) 
- [Iteration log](http://uploads.9dots.io/OiQe49h.pdf)

### Project time:

- 45 min
    
    
## Engage - 5 minutes
Give students an introduction to what it means to program robots and discuss the goal for this lesson.

1. Start a discussion with students by asking, _"What do programmers do?"_
	- Programmers give detailed instructions to computers to solve problems and accomplish tasks.  

2. Show the [Programming Introduction Video](http://www.education.rec.ri.cmu.edu/previews/robot_c_products/teaching_rc_lego_v2_preview/fundamentals/introtoprogramming/videos/fundamentals1.html).

3. Tell students that their goal is to create a robot that is capable of pushing a lego through a maze without crossing any of the lines. 

```
TIP: Make sure to start the robot in the exact same place each time. Placing an extra piece of tape in the starting area to mark the correct position can help ensure consistency.
```

![](http://uploads.9dots.io/OiQa9tW_md.jpg)
**Above: An example of what the maze could look like. The robot must push the lego from the green ‘Start’ zone to the red ‘Finish’  zone without crossing the lines.**

## Explore - 10 minutes
Students take to the engineering side of robotics to develop an attachment to help accomplish their goal.

1. A robot attachment is an additional part made out of legos that can easily be connected to the robot to help complete a specific goal. 

2. To push legos, students need to build an attachment that keeps legos from getting trapped under the robot or lost while turning.

3. Break students in to groups of no more than four

4. Groups now have 10 minutes to develop an attachment that is capable of pushing legos.

![](http://uploads.9dots.io/OiQb3yI_md.jpg) 
**Above: An attachment for pushing the legos.**

## Explain - 15 minutes
Students learn about programming and learn about simple and complex robotic behaviors.

1. Discuss with students, _"Now that the robot has an attachment to push the lego, how does the robot know what to do?"_
	- The robot needs to be programmed to accomplish the goal of getting through the maze.

2. Check for understanding by asking, "_What does programming mean?_"
	- Programming means giving the computer detailed instructions to solve problems.  

3. In robotics, these instructions that are given to the robot are called behaviors.

4. Pass out the Behaviors handout and use it as a guide to discuss simple and complex behaviors in robotics.

5. Gauge understanding by asking, "_Is navigating the maze a simple or complex behavior?_"
	- Going through the maze is complex because it is made up of several different programmable steps.

## Elaborate - 10 minutes
Play a game in which students program the instructor to move through a maze like the robot.

1. Break into groups of no more than four students. 

2. Students have 5 minutes to program the teacher robot (you) to go through the robot maze. 
	- The teacher robot only understands the simple behaviors:
		1. Move Straight (1 step forward)
		2. Turn Left (90 degrees)
		3. Turn Right (90 degrees)
 
3. After surverying the maze, each group writes down their instructions on a piece of paper. 

4. After students have their instructions written down, groups take turns having the teacher robot act out their program. 
	- When behaving as the robot, make sure to follow the instructions very literally.

## Evaluate - 5 minutes

- _What is the difference between a simple and a complex behavior?_
	- A simple behavior is a single programmable action, a complex behavior is made up of two or more simple behaviors.
    
- _What does a programmer do?_
	- A programmer gives detailed instructions to computers to make computers useful to users.
    
## Standards

| Standard      | Description   | Connection  |
| ------------- |---------------| ------|
| 3-5-ETS1-1 | Define a simple design problem reflecting a need or a want that includes specified criteria for success and constraints on materials, time, or cost | Explore |

# Day 2

## Lesson Overview
Students continue learning about simple and complex behaviors by programming their mindstorm robots. Start by teaching how to program in the EV3 environment and download programs to the robot for testing. Students demonstrate learning by giving their robots commands to navigate a maze.

## Setup

### Materials:

- Finished robot from [Robotic Engineering](http://www.9dots.io/9dots/OJ8iMiY)
- Hand written program and lego attachment from [Introduction to EV3 Programming](http://www.9dots.io/9dots/OiQXe4e)
- Computers with EV3 software
- [Move Steering Handout](http://uploads.9dots.io/Os1oGrk.docx)

### Preparations:

- Distribute the [Move Steering Handout](http://uploads.9dots.io/Os1oGrk.docx)

### Project Time:

- 45 minutes

## Engage - 5 minutes
To get the students interested, show them a video of a very well designed and programmed EV3 robot.

1. Show the [video](https://www.youtube.com/watch?v=wzDjg595AiU) of the world champion robot from 2013-14 First Lego League challenge.

2. Discuss with students the importance of combining good engineering and good programming.

3. Review what students know about robotic behaviors.
	- What is a simple behavior?
    	- A simple behavior is a single programmable step.
    - What is the relationship between simple and complex behaviors?
    	- Complex behaviors are made up of several simple behaviors.

## Explain - 15 minutes
Teach students how to use the move steering block to accomplish a simple behavior. Students follow along on the Move Steering handout.

1. In the Mindstorm EV3 software, to program the robot, drag blocks from the bottom bar and connect them to the start block that is on the screen. 
	- When using the EV3 software, a simple behavior is a single programming block.
	- To program the Mindstorm Robot, students use the same 3 simple behaviors; move straight, turn left, and turn right. 
	- The three behaviors that have been discussed are all achievable using the Move Steering block.
![](http://uploads.9dots.io/OiQbdRA_md.jpg) 

2. Students fill in the 3 parts of the Move Steering block on their handout:
	- *Turning:* Positive numbers turn right, Negative numbers turn left, and 0 means straight.
	- *Power:* How fast the motor spins. 0 is the slowest; 100 is the fastest.
	- *Duration:* How long the motor turns on for in rotations. 1 rotation is one full spin of the motor.
![](http://uploads.9dots.io/OiQc16D_md.jpg) 

3. To make a complex behavior, connect as many Move Steering blocks (simple behaviors) together as are required.

4. On the handout, students describe the behaviors for each move steering block. The finished answer should look like this:
![](http://uploads.9dots.io/OiQcewv_md.jpg) 

## Elaborate - 20 minutes 
Show students the maze from the previous lesson to remind them of what their robots needs to navigate. Students begin programming their robot to complete the maze.

1. Demonstrate how to download a program to the robot. 
	- A how to on downloading programs to the EV3 can be found in the Wiki section of 9dots.io.

2. Groups should be as small as possible with one computer per group. 

3. Each team has 35 minutes to build an attachment and program their robot to complete the maze. 
	- Students should use their program (the written down instructions) from the ‘teacher robot’ activity to help with organizing the behaviors for the actual maze challenge.

## Evaluate - 5 minutes
Students test their programs and keep a log of where each attempt could be improved.

1. Students may test their robot at any point. 

2. After each attempt, students should write down what worked and what they should change using the [iteration log handout](http://uploads.9dots.io/OiQe49h.pdf).

## Standards

| Standard      | Description   | Connection  |
| ------------- |---------------| ------|
| 3-5-ETS1-1 | Define a simple design problem reflecting a need or a want that includes specified criteria for success and constraints on materials, time, or cost | Elaborate |
| MS-ETS1-2 | Evaluate competing design solutions using a systematic process to determine how well they meet the criteria and constraints of the problem | Evaluate |
