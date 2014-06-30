---
author: danleavitt0
views: 0
published: false
type: lesson
title: Line Follow
blurb: This lesson will focus on using the color sensor to follow a line on the ground.
org: 9dots
objective: "By the end of the lesson, the student will be able to identify a programming switch statement and discuss the strategy for programming a robot to follow a black line."
attachments: 
  - path: "http://uploads.9dots.io/OihVx8V.pdf"
    name: IterationLog (1).pdf
  - path: "http://uploads.9dots.io/OihVy5K.pdf"
    name: "Dailywrap-up.pdf"
id: "9dots-OihTZql"

---

## Materials:
- Lego Mindstorm kit
- Computer with EV3 software

## Media and Handouts
- Iteration and Wrap-Up Handouts

## Project time:
1 hr 15 min

## Lesson Plan

### DISCUSS:
Students will have 3 minutes to answer the following questions on a piece of paper:

_What markers on the robot playing surface could help navigate the robot?_
Black lines placed on the field mat can help the robot to know where to move.

_Which sensor can allow the robot to see those black lines?_
The color sensor can detect how bright the colors on the mat are.

### WATCH:
Show a [video](http://www.youtube.com/watch?v=aJor5MXycoY) of a robot following a black line.

### BUILD:
At this point, students will attempt to attach a light sensor (facing down so it can see the lines) to their robot.

### STRATEGY:
Show students the black line they will be programming their robot to follow. With a turned off robot, demonstrate the situations the robot will face and what students think the robot should do in those situations. Those situations are:

1. The robot is to the right of the line
	- Turn left
2. The robot is on the line
	- Turn right
    
```
Student's first idea will be to go straight when the robot is on the line. Explain that when the line curves to the right, the robot would go off the path and the turn to the left (see rule 1). 
```

### EXPLAIN:
With the strategy figured out, students will learn about the the programming blocks required to execute this strategy. The **switch** statement takes the readings from the sensor and breaks it into two possible cases, just like the two rules in our strategy. For the color sensor, the two cases will be dark and light. To set up the switch:

1. Select the color sensor
2. Click on compare
3. Select reflected light intensity

![](http://uploads.9dots.io/Oiha8uX_md.jpg) 

In the example above, the top track will be triggered if the color sensor is over the black line, and the bottom track will be triggered if it has moved off of the line.

![](http://uploads.9dots.io/Oihrsws_md.jpg) 

### APPLY:
Using the previously discussed strategy as the guide, add the **move steering** blocks. The finished product should look like:

![](http://uploads.9dots.io/Oihyzmy_md.jpg) 

### DISCUSS:
_How can you make that process repeat indefinitely?_
Put that entire switch statement in a loop so that the process repeats forever. If there is no loop it will move once and be done.




### PROGRAM:
The setup for the competition: Each group has 30 minutes to create a robot capable of following the line accurately and as quickly as possible. The robot that completes the entire maze the quickest will be the winner. To change the speed of the robot the students need to alter the values of the turning and the power in the move blocks. At the end of the 30 minutes, each group tests their robot.

### DISCUSS:
Which numbers made for the fastest line following robot?

### WRAP-UP:
Students should now finish their robotics wrap-up handout.
