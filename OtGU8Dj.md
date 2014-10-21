---
author: miketeja
views: 0
published: false
type: lesson
title: List App
org: 9dots
objective: "SWBAT define specific components and program a functioning list app using #AppInventor"
blurb: "Learn the specific functions of each component and build a basic list application using #AppInventor"
id: "9dots-OtGU8Dj"

---

## Overview
Students gain a deeper understanding of the AppInventor components and functionality as they create a basic list app.

## Setup
### materials:
- Health App Day 3-4: Handout
- Computer with internet for [MIT AppInventor](http://appinventor.mit.edu/explore/)
- Android phone OR computer with [Android emulator downloaded](http://appinventor.mit.edu/explore/ai2/setup-emulator.html)

### project time:
- 90 minutes

#Day 1
## Engage - 5 minutes

1. Show the app, [ZombieRun](https://www.zombiesrungame.com/)
2. Explain to students how apps can combine fun, interactive gameplay with a focus on health, fitness and well-being.
3. Show students the potential profit on making successful apps, as the app costs $3.99 and there are over 800,000 players worldwide.

## Explore - 10 minutes
In this section of the guided explore, students will work together and with the instructor to identify the components of the List app. 

1. Students login to their MIT AppInventor account and open their Health App Project Page. 
2. Show students the completed list app on a projector (an emulator works best to use on a projector)
3. On Health App Day 3: Handout, have students recall what a component is.
	- Component = control specific behaviors for the phone that can each be individually programmed 
4. Students should work together for 2-3 minutes to determine what 3 components from the Palette they will be using
	- They should drag 'List', 'Button', and 'Textbox' from the Palette into the 'Viewer.'
	- Instruct students they may order these 3 components on the design page however they like (Button on top, List on top, or Textbox on top, etc.)
	- Students are ready to move on to the Blocks page

## Explain - 10 minutes
In this section of the lesson, students begin to learn fundamentals of programming vocabulary and basic theory. Students fill in the bold sections on Handout: Day 3

- Vocabulary:
	- **Event**: An action that occurs and tells the program to “do” something as a result of the user, such as a button or key being clicked.  
    - **List**: Stores information. When an item (or value) is added to a list, it is placed in a certain position, starting with 1. The position of an item is called an index. 
    - **ListView**: The visual display of the list on your phone screen.
    - **Variable**: A container that holds a value. We must define a variable, in this case, we are defining it as Food.
    - **Value**: A word or number that can be added to a list.
    
- To be diagrammed/Explained by instructor:
![](http://uploads.9dots.io/OtGZSHg_md.jpg) 

## Elaborate - 15 minutes

1. Guide students in creating a list. Explain to students we are creating an 'Empty List' and as a general function of the app, ask where students will find this.

	- As a general behavior, students will find in the Built-In Drawers
	- Give students 1 minute to search through the Built-In drawer and find the block that will help define a list.
		- Students will likely go to 'Lists' and select 'create empty list'
    
	- Explain this is correct and have all students drag this block out. Explain this list must connect with another General Behavior block. 
	- Create a 'Global' list. Give students 1 minute to explore the drawers to find a block that the 'create empty list' can attach to 
		- Students should select 'Initialize global'
    ![](http://uploads.9dots.io/OtGZtjn_md.jpg) 
    
3. The next component to program is the Button 1 component.
	- Ask students, because this is a specific component we have added to our design page, where would we find blocks for this page?
		- Give students 1 minute to discuss and identify. They should select _Button1_ under the _Screen1_ components.
        
![](http://uploads.9dots.io/OtGa3Ji_md.jpg) 
	
- Provide a series of multiple choice questions for students that will help by giving limited options, but still require critical thinking.
	- What is the primary function block we should select for the Button 1 block?
    ![](http://uploads.9dots.io/OtGaMiA_md.jpg) 
	- Students should select **B** as this option will tell the app to do something when Button1 is clicked.

- Ask students to define what our app is to do
	- Add food items to the list
- Ask students to take 1 minute to identify the general block behavior that may perform this function
	- Provide 3 options:
    ![](http://uploads.9dots.io/OtGaa2Z_md.jpg) 
    
	- Students should select option **B**. Cold call 3 students to explain each answer and why it is incorrect or correct.
- Instruct students to drag option **B** into their Button1 block. Ask students what they notice occurred on their screen. 
	- One warning was noted in the bottom left of the viewer page. Show warning and see:
    ![](http://uploads.9dots.io/OtGatSO_md.jpg) 

## Evaluate - 5 minutes
In the last 5 minutes, instruct students to select the 'Connection' tab and select 'Emulator'

- This opens their emulator and they will observe their app design, but realize it does not function. We will continue programming the List app on Day 2. 


#Day 2
## Engage - 8 minutes
Begin by having students login to their project page and opening to the Design page. Conduct a 5 minute review of Day 1 using multiple choice questions. Cold call for each answer and have student provide brief explanation for their answer choice. 

1. What is each specific section on _Screen1_ called?
	- Group
	- **Component**
	- Part
	- Function

2. What is the difference between Lists and ListViews?
	- They are the same
	- Lists display the values, ListViews store the values
	- **ListViews display the values, Lists store the values**

3. If I want to find blocks for the _Button1_ component, where can I find these blocks?
	- Variables in Built-in Drawer
	- Procedures in Viewer
	- Any Button drawer in Any Component
	- **Button1 drawer in Screen1**

## Explore - 10 minutes
During this segment of the lesson, students work together and with the instructor to analyze the incomplete block coding segment they left off on Day 3. 

1. Remind students where they are in the code:
![](http://uploads.9dots.io/OtGckMm_md.jpg) 

2. Give students 5 minutes to explore the drawers to identify the 2 possible blocks they will snap to the “add items to list” block.

	- Students should select the following:
![](http://uploads.9dots.io/OtGd71s_md.jpg) 

- Cold call to ask why there is a Red exclamation point near the 'get' block.
	- Because you need to identify what List you are adding to 
- Cold call to ask if 'BackgroundColor' is the correct item. If so why, if not, which would be a better option? 
	- Text because this will tell the app that you are adding an item from the Text you type into _TextBox1_.
    ![](http://uploads.9dots.io/OtGdDYq_md.jpg) 

## Explain - 10 minutes
In this section of the lesson, students review and continue to implement fundamentals of programming vocabulary and basic theory. Quickly review the steps for the MIT AppInventor for the List App

1. Name Variable 'Food'
	- Defines our new List
2. Using the _Button1_ component, select 'when _Button1_.Click' to set off a reaction 
	- Our reaction is to add a Value to our List
3. Values are added to the List by inputting text into _TextBox1_
	- These are the various food items we have previously selected
4. Values are displayed in the ListView
![](http://uploads.9dots.io/OtGdiZw_md.jpg) 

- New Vocabulary:
	- **Getter**: Block found in the Variables drawer that is used to get values from a List
    
1. Explore challenge: Give students 3 minutes. They need to find a way to 
	- “set” Elements in ListView1 to global food list
	- “set” the Text in TextBox1 to blank

![](http://uploads.9dots.io/OtGej1b_md.jpg) 

- The first “set” block commands the added elements to go to the global food list
- The second “set” block commands the TextBox to clear whatever was typed into it

## Elaborate - 10 minutes
Allow students time to extend their code by working with the 'properties' on the Design page. Here are some options for students.

- Rename _Button1_
- Rename what _TextBox1_ says when there is no text in it
- Add background color
- Add a specific layout
- Change the default font 
- Change the sizes and shapes of the button, textbox, and listview.
- Add screen animation

## Evaluate - 7 minutes
Instruct students to select the 'Connection' tab and select 'Emulator'

## Standards
 
| Standard      | Description   | Connection  |
| ------------- |---------------| ------|
| 3-5-ETS1-3 | Plan and carry out fair tests in which variables are controlled and failure points are considered to identify aspects of a model or prototype that can be improved | Explore, Elaborate |
| MS-ETS1-4 | Develop a model to generate data for iterative testing and modification of a proposed object, tool, or process such that an optimal design can be achieved | Explore, Evaluate |
| CCSS.MATH.PRACTICE.MP7 | Look for and make use of structure | Elaborate |
