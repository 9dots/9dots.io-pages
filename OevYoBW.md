---
author: danleavitt0
views: 0
published: false
type: lesson
blurb: "In this lesson, students will gain a basic understanding of the image, paragraph, and heading HTML elements."
org: 9dots
objective: "By the end of the lesson, students will be able to define an HTML tag, understand how to implement HTML tags in coding, and translate and example website into HTML tags."
id: "9dots-OevYoBW"
title: "What is HTML?"
attachments: 
  - path: "http://uploads.9dots.io/OfUeM8G.pdf"
    name: PuppyPals.pdf
  - path: "http://uploads.9dots.io/Ofg7Jv6.pdf"
    name: PuppyPals Answer Key.pdf
  - path: "http://uploads.9dots.io/Ofg7PJi.pdf"
    name: Stickman.pdf
  - path: "http://uploads.9dots.io/OfgEeVM.pdf"
    name: Stickman Answer Key (1).pdf

---

## Materials

- Stickman worksheet
- Puppy pals worksheet

##Preparation

- Print worksheets

## Lesson

### REVIEW:
_What is HTML?_
HTML is the code that programmers use to make websites. Each line of HTML represents an element on the page. 

### INTRODUCE:
_What does HTML look like?_
HTML is a series of tags which describe the elements on the webpage. Tags are the building blocks of a website and usually come in pairs. The exception is for the image element which only has one. Today we are going to focus on three specific tags:

Element | HTML
-|-
Heading | ```<h1>...</h1>```
Paragraph | ```<p>...</p>```
Image | ```<img src=”...”>```


The first in the pair is the start tag and the second is the end tag.  The end tag is the same as the start tag, but with a forward slash in front of it. As you can see, the exception is for the image element, which only has a start tag. Any words written in between the tags will be displayed as text on the page. An example is:	

![](http://uploads.9dots.io/OfUXVZ7_md.jpg) 

### EXPLAIN:
In HTML we write the tags in order from the top of the page to the bottom of the page.

### WORK TOGETHER:
Handout the HTML example worksheet. Together the class will translate the example document into HTML tags. The example document is color coded to match with the answer page. To begin, show students how a tag is constructed. The title at the beginning of the page would use the header tag like the example above. Ask students which tag they think will be used for the red image box. The correct answer is the image tag <img>. Make sure to explain that with the image tag it is necessary to add the source (‘src’) to the tag which tells the computer which image to display. For the source today they will write “stickman.png.” It should be written:
```
<img src="stickman.png">
```
The green paragraph box comes up next. Ask students which tag they think they will use to write a paragraph. Explain that normally they would need to write the entire paragraph between the start and end tags but for today they can just write “words...” It should look like this:
```
<p> words... </p>
```

### CHALLENGE:
Challenge students to complete the page. The source for the second image should be the same as the first one. Once everyone has finished, review the answers. Next, show the students the ‘puppy pals’ worksheet. Together, label each section as header, image, or paragraph. Once that is done students will translate them to HTML.
