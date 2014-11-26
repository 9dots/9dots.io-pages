---
author: danleavitt0
views: 0
published: true
type: lesson
blurb: "This lesson introduces students to the concept of nested tags, by learning the div and body #HTML tags. They practice the concept by adding to the document from the [Building a Website](http://www.9dots.io/9dots/OevYoBW) lesson. Students demonstrate learning by producing an HTML document on codepen.io."
org: 9dots
objective: 
  - Recognize grouped tags as belonging to the same div
  - Translate an example website to HTML tags including divs
  - Know how to log in to and create websites using codepen
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
image: "http://uploads.9dots.io/Ol3rJC2_md.jpg"
fullImage: "http://uploads.9dots.io/Ol3rJC2_lrg.jpg"

---

## Setup

### Materials:

- Computers with internet access

### Preparation:

- Print example websites
- Create a login for codepen.io (one account can be used by all of the students)

### Project Time:

- 45 minutes

## Engage - 5 minutes
Start of by reviewing what students have learned about HTML so far in this unit.

1. _Which HTML tags have you learned about so far? What is each one used for?_
	- Students have learned about the header, image, and paragraph tags. The header is for creating titles, the image is for adding pictures, and the paragraph is for adding text.

2. _What are the 3 parts to an HTML tag?_
	- Each HTML tag is composed of 3 parts: the start tag, content, and the end tag. 

3. Today, students are learning about two new types of tags: **body** and **div**.  
	- These tags are written the same as the others with a start tag, content, and an end tag.  
    - Instead of the content being text, the content of these tags is one or multiple HTML tags.

## Explain - 20 minutes
Teach students about the body and div elements and how to use them to organize their website.

1. Write this on the whiteboard:
```
<body>
	<p> this is a nested paragraph because it is inside the body </p>
	<img src=“thesource.png”>
</body>
```

1. Notice how in the example above, there are 2 HTML elements between the body start tag and end tag.

2. This is what web designers call nested tags. It is similar to a set of russian dolls, with one big one on the outside, and several smaller ones that are kept within.  

3. The **body** tag is used on every website and contains the entirety of the HTML nested within it. 

4. The **div** tag is used to create sections which make it easier to organize and style a webpage. 

5. Using the puppy pals worksheet from the last lesson (a large poster version would be preferable) outline the body (around the entire website) and the divs (should contain one image and one paragraph). 
![](http://uploads.9dots.io/Offq4HV_md.jpg) 

6. Handout the new puppy pals worksheet to students. Students should open the worksheet so that they can see both pages at the same time. As a group label each section as one of the 5 HTML elements that have been covered. By color they should be:
![](http://uploads.9dots.io/Owlb01h_md.jpg) 

7. As a class, write the HTML on the corresponding page. 
	- Make sure to point out to students that the start tag for the body is at the top but the end tag is at the very bottom of the page. 
    - Similarly for the divs the start tag should be at the top of the blue box and the end tag should be at the bottom with the paragraph and the image between them.

## Elaborate - 20 minutes

1. Check for understanding by asking a couple of questions
	1. _What makes the **div** and **body** tag different from the ones that we have learned previously?_
		- The content of the new tags is more HTML instead of text.
	2. _Why does the end tag for the **body** at the bottom of the page?_
    	- The end tag is at the bottom because the contents of the body is the entire rest of the HTML.

2. Handout the Musical Mayhem worksheet. Students work individually on translating this document into HTML. When they finish, they should check their answers with their neighbors. 

3. Students type the translated HTML into codepen.io so that they can see how it builds a website.

4. Inform the students that they now have the tools to turn their prototype into websites. Next lesson they will be translating their own prototypes into HTML.
