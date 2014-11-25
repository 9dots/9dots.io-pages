---
author: danleavitt0
views: 0
published: true
type: lesson
blurb: "In this lesson, students will gain a basic understanding of the image, paragraph, and heading #HTML elements."
org: 9dots
objective: 
  - Define an HTML tag
  - Understand how to implement HTML tags in coding
  - Translate and example website into HTML tags
id: "9dots-OevYoBW"
title: Building a Website
attachments: 
  - path: "http://uploads.9dots.io/OfUeM8G.pdf"
    name: PuppyPals.pdf
  - path: "http://uploads.9dots.io/Ofg7Jv6.pdf"
    name: PuppyPals Answer Key.pdf
  - path: "http://uploads.9dots.io/OfgEeVM.pdf"
    name: Stickman Answer Key (1).pdf
  - path: "http://uploads.9dots.io/OiK08rR.pdf"
    name: Stickman.pdf
image: "http://uploads.9dots.io/Ol3r9Tb_md.jpg"
fullImage: "http://uploads.9dots.io/Ol3r9Tb_lrg.jpg"

---

## Setup

### Materials:

- [Stickman worksheet](http://uploads.9dots.io/OiK08rR.pdf)
- [Puppy pals worksheet](http://uploads.9dots.io/OfUeM8G.pdf)

### Preparation:

- Print worksheets
- On a whiteboard, write out a table of the three HTML elements like the one below

## Engage

1. _What is HTML?_
	- HTML is the code that programmers use to make websites. Each line of HTML represents an element on the page. 

2. _What does HTML look like?_
![](http://uploads.9dots.io/OfUXVZ7_md.jpg) 

## Explain

1. HTML is a series of tags which describe the elements on the webpage. 
	- Tags are the building blocks of a website and usually come in pairs. 
    - The first in the pair is the start tag and the second is the end tag.  
    - The end tag is written the same as the start tag, but with a forward slash in front of the name. 
    - Any words written in between the tags will be displayed as text on the page. 

2. Today students are focussing on three specific tags:
![](http://uploads.9dots.io/OwfesBs_md.jpg) 

3. For their first HTML element, students will write a **heading** that says 'My First HTML Element'. To help facilitate the process, guide the students through the following steps:
	1. What kind of element is required?
    2. What is the tag for that element?
    3. What is the content?
    4. Don't forget the end tag!

4. When they have finished writing, their paper should read: 
```
<h1> My First HTML Element </h1>
```

5. There are two major differences between the **image** tag and the other elements that have been discussed:
	1. Images do not have content or an end tag
	2. Images have an attribute called **source** which is the path to the image's location

6. For this unit, all of the images will have a source that is a link to a picture on the internet.

7. For their second element, students will create an **image** that has a source of "http://www.example.com/firstimage.png". Take students through the steps again but with an additional step for writing the source:
	1. What kind of element is required?
    2. What is the tag for that element?
    3. What is the source?
    4. Make sure there is a space between **img** and **src**

8. When they have finished writing, their paper should read: 
```
<img src="http://www.example.com/firstimage.png" />
```

9. HTML tags are written in order from the top of the page to the bottom of the page.

## Elaborate

1. Handout the Stickman example worksheet. Together the class will translate the example document into HTML tags. First, students will label their document so that each element is catagorized as either a heading, paragraph, or an image. The example document is color coded to match with the answer page. To write the HTML for each element on the example document, guide students through the same steps as the examples above.

2. Challenge students to complete the page. The source for the second image should be the same as the first one. Once everyone has finished, review the answers. Next, show the students the ‘puppy pals’ worksheet. Together, label each section as header, image, or paragraph. Once that is done students will translate them to HTML.
