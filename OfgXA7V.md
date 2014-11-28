---
author: danleavitt0
views: 0
published: true
type: lesson
blurb: "During this lesson, students will continue to explore #CSS, learn how to resize elements, and create margins create space between elements."
org: 9dots
objective: 
  - Use the height and width properties to resize elements
  - Explain how the margin property is used to create space between elements
  - Inspect websites to look at the HTML and CSS rules for an element
id: "9dots-OfgXA7V"
title: Selectors and Size
image: "http://uploads.9dots.io/Ol3s23B_md.jpg"
fullImage: "http://uploads.9dots.io/Ol3s23B_lrg.jpg"

---

## Setup

### Materials:

- Computers with internet access and Chrome browser

### Preparation:

- Create a poster with the box model to help explain margins
- Create a poster with a list of CSS properties and the possible values for:
	- Width
	- Height
	- Margin
    
### Project Time:

- 45 minutes

## Engage - 5 minutes

1. _What is CSS?_
	- Cascading Style Sheets or CSS is a language that adds styles and formatting to a website. The HTML creates the elements and the CSS defines what they look like with a series of rules.

2. _What is the structure of a CSS rule?_
	- A CSS rule is broken into two parts: the selector and the declaration. The declaration has a property and the value for that property.
![](http://uploads.9dots.io/OfgY5jj_md.jpg) 

3. Show students one of the styled Batman Bowling sites from the previous class. What can we do to improve the style of the website? Guide them to the answer that many of the elements are the wrong size and are too close to each other. To change that, students need to learn about some new CSS properties.

## Explain - 20 minutes

1. CSS uses the box model to organize elements. Using the Box Model poster, show students that every element has:
	- a width property: how wide the element is
    - a height property how tall the element is
    - a margin property: a box that surrounds the element to add spacing between the element and other elements on the page.
![](http://uploads.9dots.io/OfgYlPa_md.jpg) 

2. Using the Batman Bowling example site input the following into the CSS box:
```
img {
	width:300px;
    height:400px;
    margin:15px;
}
```

3. In Google Chrome, right click one of the images and the select ‘Inspect Element’. This will open a window in your browser that shows all of the HTML and CSS used on the element.  The section on the right is where the CSS is shown. Scroll to the bottom of that section and there is an interactive version of the box model. Hovering over each section will show where it is on the element.

4. Students now open their computers to the same Batman Bowling example site. With the teacher, students attempt to change the height, width, and margin of the images on their website.

5. _Do you always want all of the images to be the same size?_
	- No, sometimes we want to be able to set the size of an individual image without changing the rest of them. To do this we are going to give an HTML element an id **attribute**.

6. _What is an attribute?_
	- An attribute is an extra piece of information about an element written inside of the start tag. 

7. _What is an example of an attribute that you have used?_
	- Students have been using the 'source' **attribute** for every image they have added.

8. _What does it look like?_
	- **Attributes** are written just like the source that students have already written many times. There is a space separating it from the name of the tag followed by three parts:
		1. The name of the attribute (in this case it will be **id**)
		2. An equals sign
		3. The value in quotation marks (for this example "logo")

9. In the HTML add an id attribute named 'logo' for the batman image.
```
<img id=”logo” src=”batman”>
```

9. Once the HTML has an **id**, instead of selecting all of the `<img>` tags, it is possible to edit just one. This is called an id selector. To select by an **id** we need to put a `#` followed by the id. For the example above that would be:
```
#logo { 
	width:600px;
	height:400px;
	margin:20px;
}
```

## Elaborate
Using the new information student will have 10 minutes to attempt to edit the website and make it look as nice as possible.  The student who is working the hardest will have his/her website displayed on the projector for the entire class.

## Standards

Standard | Description | Connection
--- | --- | ---
CSTA.CD.L2-01 | Recognize that computers are devices that execute programs. | Explain
