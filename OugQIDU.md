---
author: miketeja
views: 0
published: false
type: lesson
title: Viewing and Editing Stored Items
org: 9dots
objective: 
  - Identify and apply block coding when given a description of app functionality
id: "9dots-OugQIDU"
image: "http://uploads.9dots.io/OwH0wHt_md.jpg"
fullImage: "http://uploads.9dots.io/OwH0wHt_lrg.jpg"
blurb: "Students continue with the 'Blocks' page, where students move on to the final screen, the Info Screen, where students have can view the Food Name and Food Fact they have submitted on Screen2, and also have the option to edit these Tags and values. Students are given the challenge to program the app using the select blocks when given a description of the app functionality."

---

## Setup
### materials:
- Computer with internet for [MIT AppInventor](http://appinventor.mit.edu/explore/)
- Android phone OR computer with [Android emulator downloaded](http://appinventor.mit.edu/explore/ai2/setup-emulator.html)

### project time:
- 45 minutes

## Engage - 5 minutes
Have an Android enabled device present with the completed app uploaded to the device. Show this to students for them to visualize the final design and functionality of the app they are to complete today.

## Explore (Part 1) - 8 minutes
The 'Info' screen functions to retrieve and view stored items in the _TinyDB1_. 

1. Create an event: When ‘Info’ is initialized, two actions will occur:
	- Set the ‘Text’ in the ‘ViewFoodName’ Label to ‘get start value.’
	- Set the ‘Text’ in the ‘ViewFoodFact’ Label to call the TinyDB1.GetValue, using the ‘tag,’ ‘get start value’ (which has already been set.) The value ‘IfTagNotThere’ must be set to empty text. 

## Explain (Part 1) - 5 minutes
Provide the answers for each description.

1. Recall our 'start value' has been set in 'Screen2' when the Tag and values were input and saved into the _TinyDB1_.
![](http://uploads.9dots.io/OugVnqP_md.jpg) 

## Explore (Part 2) - 3 minutes
1. Create an event: When ‘Info’ is ‘Backpressed, the following reaction will occur:

	- Open another screen called “Screen1.”

## Explain (Part 2) - 3 minutes
Provide the answers for the description.
![](http://uploads.9dots.io/OugWI5U_md.jpg) 

## Explore (Part 3) - 3 minutes
1. Create an event: When ‘Edit’ button is ‘Clicked,’ the following reaction will occur:

	- Open another screen called “Screen2” that has a ‘startValue’ of ‘get start value’

## Explain (Part 3) - 3 minutes
Provide the answers for the description.
![](http://uploads.9dots.io/OugWOtS_md.jpg) 

## Elaborate/Evaluate - 15 minutes

1. Students use this time to check their code on their devices/emulators. Students also input the different foods and facts they researched on Day 1 into their app to check the functionality. 
2. Students who confirm the functionality of their app may continue to edit the properties of each component to customize their app design. 

## Standards
| Standard      | Description   | Connection  |
| ------------- |---------------| ------|
| 3-5-ETS1-3 | Plan and carry out fair tests in which variables are controlled and failure points are considered to identify aspects of a model or prototype that can be improved | Explore, Explain |
| CCSS.MATH.PRACTICE.MP1 | Make sense of problems and persevere in solving them | Explore | 
| CSTA.CL.L2-03. | Collaborate with peers, experts, and others using collaborative practices such as pair programming, working in project teams, and participating in group active learning activities | Explore, Explain |
| CSTA.CPP.L2-03. | Design, develop, publish, and present products (e.g., webpages, mobile applications, animations) using technology resources that demonstrate and communicate curriculum concepts | Evaluate |
