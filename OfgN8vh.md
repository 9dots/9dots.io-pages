---
author: danleavitt0
views: 0
published: true
type: lesson
blurb: "Students will get an introduction to styling a #website with #CSS and learn about the #properties and values for styling text."
org: 9dots
objective: 
  - Explain why a website needs CSS
  - Define a CSS selector
  - Recognize all of the parts of a CSS rule
attachments: 
  - path: "http://uploads.9dots.io/OfgSn5Q.docx"
    name: CSS Practice Handout.docx
id: "9dots-OfgN8vh"
title: "Now, With Style"
image: "http://uploads.9dots.io/Ol3rpCw_md.jpg"
fullImage: "http://uploads.9dots.io/Ol3rpCw_lrg.jpg"

---

## Setup

### Materials:

- Computers with internet access

### Preparation:

- Create a poster with the example CSS rule
- Create a poster with a list of CSS properties and the possible values for the properties
- Print the CSS checklist worksheet

## Engage - 5 minutes

1. _What is HTML?_
	- HTML is the language that web developers use to create websites. Each HTML tag translates to an element on the page.

2. Does HTML style a website?
	- Students recognize from their own experience typing their HTML on codepen, that on its own, HTML creates elements but has no style. Ask students if this is a web page that they would like to make? Why not?

## Explain - 15 minutes

1. To style the website students need a second language called  Cascading Style Sheets or CSS.  CSS is written as a series of rules that define what the HTML tags look like.

2. Using the example website type the following into the CSS box:
```
h1 { text-align:center; }
```
The title of the page in the preview area will jump to the middle of the page. 

3. Each rule consists of two parts: the selector and a series of declarations that are separated by semi-colons. The selector determines which tag(s) the rule is for, and the declaration defines the rule.  
![](http://uploads.9dots.io/OfgP3vE_md.jpg) 
In this example, the selector **h1** selects any `<h1>` elements in the HTML. The declaration ‘text-align : center’ sets the text to align to the middle of the heading.

4. There are different types of selectors but today students are getting introduced to only the element selector. The element selector will set the rule for all of the HTML elements with the tag. 
	- For example the selector ‘h1’ will set the rules for all of the `<h1>` elements. 
    - The ‘img’ selector will set the rules for any `<img>` elements on the page.

5. _Which elements are affected by the above CSS rule?_
	- Any element with the `<h1>` tag will be affected.

6. Using the properties poster in the classroom, figure out the correct CSS rule to change the font size of all of the paragraphs to 25px.
```
p { font-size:25px; }
```

7. Ask a couple of questions to check for understanding.
	1. _Which tags contain text?_
		- The heading and paragraph tags contain text.
	2. Which CSS selector will set the rules for the paragraphs?
		- The selector ‘p’ will set rules for all of the paragraphs.

## Elaborate - 25 minutes

1. Distribute the [CSS practice checklist handout](http://uploads.9dots.io/OfgSn5Q.docx).

1. Students now get on the computer and go to the Batman Bowling example website and set CSS rules for the various selectors according to the handout.

2. After practicing, student now use the font properties to practice changing the text of the webpage. Students need to try all of the properties to see the effect that they have on the text.
```
TIP: It can be fun to project student's projects for the class when they finish styling all of the elemnts on their website.
```

3. If students complete the work early, they can try editing one of the featured pens on the codepen home site. When they are editing the website they should try to find the CSS relating to text and change it to see what happens to the website.

## Standards

Standard | Description | Connection
--- | --- | ---
CSTA.CD.L2-01 | Recognize that computers are devices that execute programs. | Explain
