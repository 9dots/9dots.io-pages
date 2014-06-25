---
author: danleavitt0
views: 0
published: false
type: lesson
blurb: This lesson will introduce students to the concept of nested tags by learning the div and body tags.
org: 9dots
objective: "By the end of the lesson, students will be able to recognize grouped tags as belonging to the same div, translate an example website to HTML tags including divs, and know how to log in to and create websites using codepen."
attachments: 
  - path: "http://uploads.9dots.io/OffsaEv.pdf"
    name: Musical Mayhem.pdf
  - path: "http://uploads.9dots.io/OfgEv12.pdf"
    name: MusicalMayhem Answer Key.pdf
  - path: "http://uploads.9dots.io/OfgFWEI.pdf"
    name: PuppyPals2.pdf
  - path: "http://uploads.9dots.io/OfgFXe6.pdf"
    name: PuppyPals2 Answer Key.pdf
id: "9dots-OfflsfX"
title: Nested Tags
image: "http://uploads.9dots.io/OiEbc6S_md.jpg"

---

## Materials:

- Computers with internet access

## Preparation:

- Print example websites

##Lesson

### REVIEW: 
_Which HTML tags have you learned about so far? What is each one used for?_
So far, students have learned about the header, image, and paragraph tags. The header is for creating titles, the image is for adding pictures, and the paragraph is for adding text.

_What are the 3 parts to an HTML tag?_
Each HTML tag is composed of 3 parts: the start tag, content, and the end tag. 
Ask students what content means?
Content is whatever is between the start tag and end tag and is normally words.


### INTRODUCE:
Today, students will be learn about two new types of tags: **body** and **div**.  These tags are written the same as the others with a start tag, content, and an end tag.  However, instead of the content being words, the content of these tags is one or multiple HTML tags.
```
<body>
	<p> this is a nested paragraph because it is inside the body </p>
	<img src=“thesource.png”>
</body>
```
Notice how in the example above, there are 2 HTML elements between the body start tag and end tag.

This is what programmers call nested tags. It is similar to a set of russian dolls, with one big one on the outside, and several smaller ones that are kept within.  The **body** tag is used on every website and contains the entirety of the HTML nested within it. The **div** tag is used to create sections which make it easier to organize and style a webpage. 

### SHOW:
Using the puppy pals worksheet from the last lesson (a large poster version would be preferable) outline the body (around the entire website) and the divs (should contain one image and one paragraph). 

![](http://uploads.9dots.io/Offq4HV_md.jpg) 

### AS A GROUP: 
Handout the new puppy pals worksheet to students. Students should open the worksheet so that they can see both pages at the same time. As a group label each section as one of the 5 HTML elements that have been covered. By color they should be:

Color | Element
-|-
Black | body
Yellow | header
Blue | div
Green | paragraph
Red | image

With the website labeled, the group should now start to write the HTML on the corresponding page. Make sure to point out to students that the start tag for the body is at the top but the end tag is at the very bottom of the page. Similarly for the divs the start tag should be at the top of the blue box and the end tag should be at the bottom with the paragraph and the image between them. An answer key is available here (link).

### RECAP:
_What makes the **div** and **body** tag different from the ones that we have learned previously?_
The content of the new tags is more HTML instead of text.

_Why does the end tag for the **body** at the bottom of the page?_
The end tag is at the bottom because the contents of the body is the entire rest of the HTML.

### INDIVIDUALLY:
Handout the Musical Mayhem worksheet. Using the knowledge gained from this lesson, students will complete this handout on their own. When they have finished they should check their answers with their neighbors. 

### EXPLORE:
Students will now type the translated HTML into codepen.io so that they can see how it builds a website.

### WRAP-UP:
Inform the students that they now have the tools to turn their prototype into websites. Next lesson they will be translating their own prototypes into HTML.
