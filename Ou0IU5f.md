---
author: miketeja
views: 0
published: false
type: lesson
title: Block Coding
blurb: "Focus on programming components for Screen1 of the Health App using the #AppInventor"
org: 9dots
objective: SWBAT program the Blocks for Screen1 when given a description of the screen functionality
id: "9dots-Ou0IU5f"

---

## Overview
Today's lesson transitions from the 'Designer' page to the 'Blocks' page, where students begin programming one of the three screens. Students are given the challenge to program the app using the select blocks when given a description of the app functionality. 

## Setup
### materials:
- Health App [Day 5-6: Handout](http://uploads.9dots.io/OtMM4NC.gdoc)
- Computer with internet for [MIT AppInventor](http://appinventor.mit.edu/explore/)
- Android phone OR computer with [Android emulator downloaded](http://appinventor.mit.edu/explore/ai2/setup-emulator.html)

### project time:
- 45 minutes

## Engage - 5 minutes

1. Show students https://www.youtube.com/watch?v=nKIu9yen5nc#t=92 for 3-5 minutes.
2. Ask 2-3 students why they want to code and what they hope to achieve with this skill.

## Explore - 15 minutes

1. Instruct students to ‘Connect’ to the emulator to have in their view for the duration of the lesson. This will update real-time as the code is edited throughout the lesson, providing a visual for students.
2. Students need to rename several components to provide unique names for each component which will later prove to be useful in the block programming portion of the explore. 

	- Instruct students to rename a component, they must highlight the desired component within the ‘Components’ section of the web browser and then select ‘Rename’ at the bottom of the ‘Components’ section.
![](http://uploads.9dots.io/Ou0MUkl_md.jpg) 
		
	- Screen1’: 
		- _Button1_ → add
	- ‘Screen2’: 
		- _TextBox1_ → name
		- _TextBox2_ → fact
		- _Button1_ → submit
	- ‘Info’:
		- _Label1_ → name
		- _Label2_ → fact
		- _Button1_ → edit

3. Instruct students to read the following descriptions in Health App Day 7: Handout for 'Screen1' ‘Blocks.’ They should be referring to the on-screen emulator to check their work. 

	- Initialize a global variable to create an empty list, and define the variable as “Food” 
	- Create an event such that when the ‘Add’ button is clicked, the app opens another screen named ‘Screen2.’ 
	- Create an event when ‘AfterPicking’ _ListView1_, another screen opens that is titled, “Info” and has a start value that is the ‘Selection of _ListView1_.

## Explain - 20 minutes

1. Review the correct code for prompts 1, 2, and 3. 
![](http://uploads.9dots.io/Ou0NmjE_md.jpg) 
![](http://uploads.9dots.io/Ou0NtIz_md.jpg) 

	- Explain this code: Initializes a new variable that is an empty list and is defined as “food.”
	- When the ‘Add’ button is clicked, it takes the user to Screen2.
	- When an item in _ListView1_ is picked, it takes the user to the Info screen with the selected food item as the starting value (recall, an item that is added to a list, such as food in this case, is considered a ‘Value.’ 
		- (i.e. apple and big mac are considered ‘startValues’)

2. A Tag can be thought of as a folder on your computer finder.
	- This is a way to organize files and maintain organization throughout your saved material
	- The documents in the files are the stored items, such as the Foods, and Food Facts

3. The last section of code commands the app to call from the TinyDatabase1 when the Screen1 is initialized upon opening.

	- The ‘global food’ variable must be set to call data (values) that have been stored within folders (Tags) in the _TinyDB1_. 
	- The _ListView1_ component must be set to the elements listed that we get from the ‘global food’ list variable. 
![](http://uploads.9dots.io/Ou0nZHV_md.jpg) 

## Evaluate - 5 minutes
This time is dedicate to students receiving feedback from their Android companion (Android device or on screen emulator.) 

## Evaluate - 5 minutes
Test on device (emulator or Android device)

| Standard      | Description   | Connection  |
| ------------- |---------------| ------|
| 3-5-ETS1-2 | Generate and compare multiple possible solutions to a problem based on how well each is likely to meet the criteria and constraints of the problem | Elaborate |
| CSTA.CPP.L2-01. | Select appropriate tools and technology resources to accomplish a variety of tasks and solve problems | Explore, Explain | 
| CSTA.CPP.L3A-02. | Use mobile devices/ emulators to design, develop, and implement mobile computing applications | Evaluate |

