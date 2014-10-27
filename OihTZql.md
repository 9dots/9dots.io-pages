---
author: danleavitt0
views: 0
published: true
type: lesson
title: Line Follow
blurb: This lesson focuses on programming the robot to use the color sensor to follow a line on the ground
org: 9dots
objective: SWBAT identify a programming switch statement and discuss the strategy for programming a robot to follow a black line.
attachments: 
  - path: "http://uploads.9dots.io/OihVx8V.pdf"
    name: IterationLog (1).pdf
  - path: "http://uploads.9dots.io/OihVy5K.pdf"
    name: "Dailywrap-up.pdf"
id: "9dots-OihTZql"
image: "http://uploads.9dots.io/Ol3uHeh_md.jpg"
fullImage: "http://uploads.9dots.io/Ol3uHeh_lrg.jpg"

---

## Lesson Overview
Students learn how to make their robot follow a black line.  The lesson starts by giving students time to connect a color sensor facing down so that the robot can react to the line. Next, students learn about using a switch statement in programming that takes the data from the sensor and splits it in to two categories (light or dark). Students demonstrate learning by completing an obstacle course by following a black line.

## Setup

### Materials:

- Lego Mindstorm kit
- Computer with EV3 software
- [Iteration handout](http://uploads.9dots.io/OihVx8V.pdf)
- [Wrap-up handout](http://uploads.9dots.io/OihVy5K.pdf)

### Preparation:

- Create a path for the robot to follow using black electrical tape on a white floor or poster. 

### Project time:

- 1 hr 10 min

## Engage - 15 minutes
Get students thinking about how a black line can help their robot navigate to a desired location. Then, students have time to connect a color sensor their robot.

1. Show students the black electrical tape maze that the robot needs to navigate through.

2. Ask, "_What markers on the robot playing surface could help navigate the robot?_"
	- Black lines placed on the field mat can help the robot to know where to move.

3. _Which sensor can allow the robot to see those black lines?_
	- The color sensor can detect how bright the colors on the mat are.

4. Show a [video](http://www.youtube.com/watch?v=aJor5MXycoY) of a robot following a black line.

5. At this point, students have ten minutes to attach a color sensor (facing down so it can see the lines) to their robot.

## Explain - 20 minutes
Show students the line and demonstrate the simple behaviors needed to program a robot to follow the line. Next, introduce students to the new programming blocks they need to accomplish their goal.

1. Show students the black line that their robot will follow. 

2. With a turned off robot, demonstrate the situations the robot will face and what students think the robot should do in those situations.
  1. The robot is to the right of the line
      - Turn left
  2. The robot is on the line
      - Turn right 

3. Student's first idea is often to go straight when the robot is on the line. Explain that when the line curves to the right, the robot would go off the path and the turn to the left (see rule 1). 

4. With the strategy figured out, teach students about the the programming blocks required to execute this strategy. 
	- The **switch** statement takes the readings from the sensor and breaks it into two possible cases, just like the two rules in our strategy. 
    - For the color sensor, the two cases are dark or light. To set up the switch: 
      1. Select the color sensor
      2. Click on compare
      3. Select reflected light intensity
      
![](http://uploads.9dots.io/Oiha8uX_md.jpg) 

**In the example above, the top track is triggered if the color sensor is over the black line, and the bottom track is triggered when it has moved off of the line.**

![](http://uploads.9dots.io/Oihrsws_md.jpg) 
5. Using the previously discussed strategy as the guide, add the **move steering** blocks. The finished product should look like:

![](http://uploads.9dots.io/Oii19BC_md.jpg) 
6. Ask, "_How can you make that process repeat indefinitely?_"
	
   - Put that entire switch statement in a loop so that the process repeats forever. If there is no loop it will move once and be done.

![](http://uploads.9dots.io/Oihyzmy_md.jpg) 

## Elaborate - 30 minutes
Students take thirty minutes to finish building their attachments and program their robot to follow the black line.

1. Each group has 30 minutes to create a robot capable of following the line accurately and as quickly as possible. 

2. The robot that completes the entire maze the quickest is the winner. 
	- To change the speed of the robot the students need to alter the values of the turning and the power in the move blocks. 
    
3. At the end of the 30 minutes, each group tests their robot.

## Evaluate - 5 minutes
Check for understanding by discussing the outcomes of the project and asking a few review questions.

1. Discuss, "_Which numbers made for the fastest line following robot?_"

2. What does a switch statement do?

3. Why is a loop necessary to make the robot follow a line?

4. Students should now finish their robotics wrap-up handout.
