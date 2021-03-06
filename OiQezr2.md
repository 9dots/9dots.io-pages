---
author: danleavitt0
views: 0
published: true
type: lesson
title: Mindstorm Pinball
blurb: "This lesson teaches students about programming loops and event handlers for their robots. It starts by discussing senses and how they help humans and robots react to their environment. Then, students work on building a touch sensor attachment for their robots. Next, students figure out the behaviors required to accomplish their goals and learn about how to program those behaviors. Students demonstrate learning by testing their created programs in a competition called Mindstorm Pinball."
org: 9dots
objective: 
  - Define a programming loop
  - Explain the importance of sensors to programming a robot
  - Create a robot capable of running indefinitely and turning whenever it runs into a wall
attachments: 
  - path: "http://uploads.9dots.io/OiQgDvK.pdf"
    name: touchsensorbuilding.pdf
  - path: "http://uploads.9dots.io/OiQgFvf.pdf"
    name: IterationLog (1).pdf
  - path: "http://uploads.9dots.io/OiQgHq5.pdf"
    name: "Dailywrap-up.pdf"
id: "9dots-OiQezr2"
image: "http://uploads.9dots.io/Ol3tnfD_md.jpg"
fullImage: "http://uploads.9dots.io/Ol3tnfD_lrg.jpg"

---

## Setup

### Materials:

- Lego Mindstorm kit (with Touch Sensor)
- Computer with EV3 software
- Example touch sensor attachment
- Iteration and wrap-up handout

### Preparations:

- [Create Mindstorm Says images](http://uploads.9dots.io/OiQkWO7_md.jpg)
- Set up projector

### Project Time:

- 45 minutes

## Engage - 5 minutes
Relate human senses to robotic sensors and discuss how those senses can be used to react to external stimuli. Then, explain the goal for this lesson.

1. Discuss with students how people use their senses to react to their environment.
	- _What do people do if they bump into a wall?_
		Answers should include: stop walking, turn around, or back up.

	- _Which of your senses do you use to know that you are touching the wall?_
		The sense of touch is how a person knows that they have run into a wall.

2. Explain that the robot uses sensors to mimic human senses and allow it to react to its surroundings.
	- The touch sensor can let the robot know when it has run into a wall.

2. The goal of the day is to make a robot that can run into as many walls as possible in 1 minute.

## Explore - 5 minutes
Review the definition of an attachment for a robot and then give students time to create a touch sensor attachment.

1. An attachment is a lego structure added to the robot that gives it the ability to complete more tasks.
	- This attachment can not be used at the same time as their push attachments. 
    - Different attachments are used to solve different problems.

2. Students have five minutes to attempt to attach the touch sensor to their robot. The touch sensor should be connected to the front of their robot so that when it runs into a wall it gets pressed.

## Explain - 15 minutes
Start out by reviewing what they already know about programming the robot. Then, discuss what behaviors are necessary to accomplish the goal for today. Finally, show them how to program those behaviors and play a game to reinforce learning.

1. Revisit the options associated with the move block that they learned previously, specifically the steering and the duration.
![](http://uploads.9dots.io/OiQh9jS_md.jpg) 

2. To accomplish the goal for today there are four necessary behaviors:

    1. Make the robot move forward forever
    2. Wait for the touch sensor to be activated
    3. Turn
    4. Repeat steps 1-3

3. To accompish the first behavior the duration on the move block must be changed to **on**. This makes the robot move for an unlimited amount of time like referenced in the image below.
	- If there is no programming block after this it stops instantly.
    - If there is a wait block after this move block, the robot continues to move until the wait block condition is met.
![](http://uploads.9dots.io/OiQhIX8_md.jpg) 

4. This is called an **event handler** and reacts only when the event has happened. The wait block means that we continue whatever comes before the block until the condition is met.
	- In this case the condition the robot should wait for is when the touch sensor is activated.
![](http://uploads.9dots.io/OiQj0Nu_md.jpg) 

5. Students remember from the previous lesson to use the Move Steering block to turn.

6. The Loop block means that any blocks within the loop are repeated forever.
![](http://uploads.9dots.io/OiQjPzY_md.jpg) 

7. Play a game of Mindstorm Says. To play, draw the programming blocks onto pieces of paper. Tape the paper in different orders to review with the students what each programming block accomplishes. Sample rules are:

    - **Move block:** Walk in place.
        - For each rotation specified the students take 1 step.
        - If the paper says unlimited the students continue to walk in place until told otherwise.
    - **Wait block with touch sensor:** A tap on the head activates the student’s touch sensor. Students now move on to the next step in the program.
    - **Loop:** Any parts of the program that are between the start and end of loop pages should be repeated until the teacher says to stop.
![](http://uploads.9dots.io/OiQkWO7_md.jpg) 
**In the example above, students would take 2 steps, wait to be tapped on the head, and then repeat that process until they are told the program is finished.**

8. Check for understanding by asking some follow up questions.

	- _How can using the wait block help them to achieve their goal?_
    
	By combining the move block with the wait block, the students can program their robot to move forward indefinitely until the touch sensor is triggered.
![](http://uploads.9dots.io/OiQnPLd_md.jpg) 

	- _How can the loop block be utilized?_
	
    The loop can ensure that their robot continues to bounce off walls continuously without having to restart the program. Anything inside of the loop is repeated forever (or until the ‘stop’ button is pushed on the robot).
![](http://uploads.9dots.io/OiQnT0b_md.jpg) 

## Elaborate - 15 minutes
This time is used to program the robot and add final touches to the touch sensor attachment that is connected to the robot.

1. Each group now has 15 minutes to finish building an attachment and program the robot to bounce off as many walls as possible in 1 minute. 

2. Students can test their robots at any point during the building time.
	- After each attempt, students should write down what worked and what they should change using the iteration log handout. 

## Evaluate - 5 minutes
Students test their programs by competing in a game of Mindstorm Pinball (the rules are listed below). When they have finished, students will discuss their engineering designs and fill out the robotics wrap-up handout.

1. At the end of the allotted time, students test their robots by playing a game of Mindstorm Pinball.  To play, create a square playing area with walls on all four sides.  Place the robot in the center and set a timer for 1 minute. Points will be awarded for each wall that the robot can touch within that time limit.
  - 1st time bouncing off of a wall: 10 points
  - 2nd time bouncing off of the same wall:  5 points
  - 3rd + time bouncing off of the same wall: 1 point
  - 50 bonus point each time all four walls are hit

2. Discuss with students, "_How important was the placement of the touch sensor?_"
	The placement of the the touch sensor is very important because if it is not in a place where it can be bumped, the robot can not be successful.

3. Students fill in the robotics wrap-up handout.

## Standards

| Standard      | Description   | Connection  |
| ------------- |---------------| ------|
| NGSS-MS-ETS1-2 | Evaluate competing design solutions using a systematic process to determine how well they meet the criteria and constraints of the problem.| Explore |
| NGSS-MS-ETS1-3 | Analyze data from tests to determine similarities and differences among several design solutions to identify the best characteristics of each that can be combined into a new solution to better meet the criteria for success. | Evaluate |
| CCSS.MATH.PRACTICE.MP2 | Reason abstractly and quantitatively. | Explain, Elaborate |
