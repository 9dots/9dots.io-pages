---
author: miketeja
views: 0
published: false
type: lesson
title: Designing the Health App
blurb: "Focus on design components for the three screens of the Health App using the #AppInventor"
org: 9dots
objective: 1. SWBAT design three screens for a health app using the designer page components on the AppInventor  2. SWBAT edit the design properties of their screen and components upon completion of the app design framework
id: "9dots-OtGhCXe"

---

## Overview
This week is dedicated to user interface (UI) design. Elements of design are critical when programming an app and students will work to make their app design intuitive and easy for the user and also customize the app framework with different colors, layouts, and graphics. 

## Setup
### materials:
- Health App Day 5-6: Handout
- Computer with internet for [MIT AppInventor](http://appinventor.mit.edu/explore/)
- Android phone OR computer with [Android emulator downloaded](http://appinventor.mit.edu/explore/ai2/setup-emulator.html)

### project time:
- 90 minutes

## App Description
“FoodieFacts” is an app that is designed to input different common foods and a basic nutrition fact to help users make healthier eating decisions. This app will be composed to 3 different screens:
### Screen1
The home screen for the user which will consist only of an ‘Add’ button and a ListView. The ListView will display the List of previously added food Values. 
![](http://uploads.9dots.io/OtGkrYc_md.jpg) 

###Screen2
Upon adding a food item with the ‘Add’ button, users will be navigated to ‘Screen2.’ This screen is dedicated to adding a ‘Food,’ adding a ‘Fact’ about the specified food, and a ‘Submit’ button to add the Values to the database and the ‘Food’ to the 'Screen1' ListView.
![](http://uploads.9dots.io/OtGkyT6_md.jpg) 

###Info
This screen is accessible by selecting a ‘Food’ on the 'Screen1' homepage. Upon selecting a ‘Food,’ the Info screen will display the ‘Food’ and the ‘Fact,’ both which were previously input by the user. There will also be an ‘Edit’ button at the bottom, allowing the user to update or add to information. 
![](http://uploads.9dots.io/OtGl3df_md.jpg) 

#Day 5
## Engage - 5 minutes

1. Show students [Latera Logics](http://www.lateralogics.com/home.html) and explain this is the website of 12 year old Android App developer, Arjun Kumar. 

2. Arjun has made two successful Apps, one that tracks buses and notifies parents and one that helps women and teens in unsafe situations, using the MIT AppInventor. These are official apps that can be downloaded in the Android App store and have helped many people so far. 

**Note: Keep the emulator open on the instructor screen throughout the lesson to allow students to see how changing the code affects the app in real-time.**

## Explore - 10 minutes
Today’s explore is to give students an opportunity to select the correct components for 'Screen1' and 'Screen2' (Day 6 will be reserved for the 'Info' Screen and further customizing the properties of each screen.)

1. Provide students with a screen shot of 'Screen1' and 'Screen2' on Handout: Day 5. 
2. Students they have 3 minutes to re-read the description of 'Screen1' and 'Screen2' in order to determine what components are needed for each screen and add these components to their viewer.

## Explain - 15 minutes
Complete the following steps with students, displaying the instructor’s screen for all students to observe. 

1. Review the correct components for 'Screen1' and 'Screen2' with students. 

### The Components: 
Screen1: _ListView1, Button1_
Screen2: _Label1, Label2, TextBox1, TextBox2, Button1_

- Define the missing component with students:
	- _TinyDB1_ (non-visible): A Database is a place where information or data can be stored until it is removed or replaced, and will remain on the device even if the app is closed (TinyDB means a very small database)

### The Text Properties: 
The text written on each component can be edited using the ‘Properties’ portion of the page. 

- On Screen1, edit the Button1 text to read, ‘Add’ by erasing _Button1_ from ‘Text’ and typing ‘Add.’ 
- Instruct students to edit all the component’s properties to replicate 'Screen1' and 'Screen2' from their Handout: Day 5 (5 minutes). Review answers. 

### The Layout: 
The layout is found in the 'Palette' and allows the components to be arranged in several ways. 

- On 'Screen1', edit the _Button1_ text to read, ‘Add’ by erasing _Button1_ from ‘Text’ and typing ‘Add.’ 

- Show students how to add _HorizontalArrangement_ to 'Screen1' _Button1_.
	- This is done by dragging the _HorizontalArrangement_ component into the Viewer, then dragging the _Button1_ inside the _HorizontalArrangement_. 
	- Inside the ‘Width’ Property of the _Button1_ and _HorizontalArrangement_ components, select ‘Fill parent...’ This will ensure it will fit the entire width of the larger component it is resting inside of ('Screen1' for the _HorizontalArrangement_ and the _HorizontalArrangement_ for the _Button1_.)
- Have students match their Layout properties of the Layout for 'Screen2' (5 minutes). Review answers. 

## Evaluate - 10 minutes
This time is dedicate to students receiving feedback from their Android companion (Android device or on screen emulator.) 

#Day 6
## Engage - 5 minutes
Open the emulator and connect the screen to allow students to see your code. Have some fun images or memes open and use the ‘Properties’ section of the ‘Designer’ page. Upload the images to show how easy it is to customize their apps and make them fun and exciting. 

## Explore - 10 minutes
Remind students the function of the 'Info' screen:

- **Info**: This screen is accessible by selecting a ‘Food’ on the Screen1 homepage. Upon selecting a ‘Food,’ the Info screen will display the ‘Food’ and the ‘Fact,’ both which were previously input by the user. There will also be an ‘Edit’ button at the bottom, allowing the user to update or add to information. 
![](http://uploads.9dots.io/OtGqBc3_md.jpg) 

1. Challenge students to select the correct components for the Info screen to match the screenshot on Handout: Day 6. 
2. Challenge students to organize their Info screen layout to match the screenshot on Handout: Day 6.

## Explain - 10 minutes

1. Call on students for component answers

	- Components: _Label1, Label2, Button1_

2. Explain a Database is also required to store the information of this screen. Ask students to recall what a Database is:

	- _TinyDB1_ (non-visible): A Database is a place where information or data can be stored until it is removed or replaced, and will remain on the device even if the app is closed (TinyDB means a very small database)

3. Have students rename the following components:

	- _Label1_: name
	- _Label2_: fact
	- _Button1_: Edit

## Elaborate - 15 minutes
This time is dedicated to customizing the app design with the ‘Properties’ section of the ‘Designer’ page. 

- Add background color of each screen
- Change text alignment
- Change the button shape
- Change the text color
- Add a background image

## Evaluate - 5 minutes
Test on device (emulator or Android device)
