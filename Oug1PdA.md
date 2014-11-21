---
author: miketeja
views: 0
published: false
type: lesson
title: Databases
org: 9dots
objective: 
  - Identify and apply block coding when given a description of app functionality   SWBAT retrieve and store values to a database
id: "9dots-Oug1PdA"
image: "http://uploads.9dots.io/OwGzZ5G_md.jpg"
fullImage: "http://uploads.9dots.io/OwGzZ5G_lrg.jpg"

---

## Overview
In Today's lesson, students program Screen2 to store and retrieve food names and food facts to a database.

## Setup
### materials:
- Computer with internet for [MIT AppInventor](http://appinventor.mit.edu/explore/)
- Android phone OR computer with [Android emulator downloaded](http://appinventor.mit.edu/explore/ai2/setup-emulator.html)

### project time:
- 45 minutes

## Engage - 5 minutes
Have an Android enabled device present with the completed app uploaded to the device. Show this to students for them to visualize the final design and functionality of the app they are to complete in the next two lessons.

## Explore (Part 1) - 10 minutes
Explain the first of this screen to students. 'Screen2' stores and retrieves tags and values. There are two possible scenarios for data storage or retrieval

- A start value that is not blank. This is when a new tag (Food name) and value (Food fact) is added and stored to the database to later be viewed on the 'Info' screen. 
- A start value that has already been stored and is being edited. This is when a tag is being retrieved from the _TinyDB1_.


1. Create an event: When 'Screen2' is initialized, it will check if the start value is empty or not. 

2. Program the app, if the 'start value' is empty, then it will perform an action.

3. If the 'start value' is empty:
	- Set the ‘Text’ in the ‘EditFoodName’ Textbox to 'get start value.'
	- Set the ‘Text’ in the ‘EditFoodFact’ Textbox call the TinyDB1.GetValue, using the ‘tag,’ ‘get start value.’ The value ‘IfTagNotThere’ must be set to empty text. 

## Explain (Part 1) - 5 minutes
Provide the answers for each description.

1. Create an event: When 'Screen2' is initialized, it can do two actions:
![](http://uploads.9dots.io/Oug4xVd_md.jpg) 
2. If the 'start value' is not empty (blank text), then the app will perform an action.
	- Explain a blank text means they are adding a new item, otherwise they get (retrieve) information about the item.
	- Note: the ‘get start value’ returns the start value given to the current screen, and is given when opening a new screen (i.e. opening Screen2 after selecting the ‘Add’ button on Screen1.)
	- We must set the start value in this screen. 
![](http://uploads.9dots.io/OugK8YW_md.jpg) 

3. Then, we must set two our app to perform two tasks:

	- Set the ‘Text’ in the ‘EditFoodName’ Textbox to ‘get start value.’ (The name of the food)
	- Set the ‘Text’ in the ‘EditFoodFact’ Textbox call the TinyDB1.GetValue, using the ‘tag,’ ‘get start value’ (which we have just set.) The value ‘IfTagNotThere’ must be set to blank text. (The information stored about that food)
![](http://uploads.9dots.io/OugKPMP_md.jpg) 

## Explore (Part 2) - 10 minutes
Upon entering tags and values to 'Screen2,' the user 'Submits' them to be stored in the database. 

1. Create a second event: When the ‘Submit’ button is clicked, 3 actions will occur within the same event block:

	- Call the TinyDB1 to Clear the ‘tag’ for the ‘EditFoodName’ label. 
	- Call the TinyDB1 to Store the ‘tag’ and a ‘valueToStore.’
		- The ‘tag’ will be the Food name you will input. 
		- The ‘valueToStore’ will be the Food fact you will input. 
2. The final action to be added to ‘Submit’ button click is open another screen, “Screen1,” which is our homepage where the ‘tag’ (folder) has been added to our _ListView1_. 

## Explain (Part 2) - 5 minutes
Provide the answers for each description.

1. Remind students that the tag can be thought of as a folder, and the value is the file inside the folder. In this case, the tag is the food name that is storing the file, or the fact about that particular food. 
![](http://uploads.9dots.io/OugMxfD_md.jpg) 

## Evaluate - 5 minutes
This time is dedicate to students receiving feedback from their Android companion (Android device or on screen emulator.)

## Standards
| Standard      | Description   | Connection  |
| ------------- |---------------| ------|
| 3-5-ETS1-3 | Plan and carry out fair tests in which variables are controlled and failure points are considered to identify aspects of a model or prototype that can be improved | Explore, Explain |
| CCSS.MATH.PRACTICE.MP7 | Look for and make use of structure | Explore, Explain | 
| CSTA.CPP.L3A-02. | CSTA.CT.L3A-07 | Explain |
| CSTA.CL.L3A-01 | Work in a team to design and develop a software artifact | Explore, Explain |
