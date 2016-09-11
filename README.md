# Learn to Code - Intro to HTML
Brought to you by Galvanize. Learn more about the way we teach code at [galvanize.com](http://galvanize.com).

## Overview
The goal of this brief course is to provide you with a fun introduction to the world of web development, starting with HTML. We will explore a variety of ways to build HTML elements, and if we have time, we'll explore some HTML5 as well. 

#### Here's what we'll be doing:
* Setting up our computers for web development
* Overview of basic HTML syntax
* Inspecting basic HTML elements
* Playing around in the sandbox

#### Before you begin, a quick gut check:
* This course is for absolute beginners
* Feel free to move ahead
* Help others when you can
* Be patient and nice
* You will get through it!

#### What web coding is (really)?
Recipes to give to your computer to “cook” up some awesome things for you online

## Setting up your computer
(Brace yourself...)

#### Please set up the following:
* A web browser to see what we're working on as others see it (Recommend Google Chrome: [chrome.google.com] (http://chrome.google.com))
* A text editor to modify your files (Recommend the Atom text editor: [Atom.io](http://atom.io))
* Download the tutorial files on this page within the zip file  


#### Download the files for this class:
1. Go to https://github.com/GalvanizeOpenSource/Learn-To-Code-Intro-HTML
2. Click on the button on the right-hand side that says "Download ZIP"
3. Go to your downloads folder and double click on the .zip file to unzip it
4. From Atom: File > open, select the folder and then click "Open"
5. From Atom: If the file tree does not appear on the left hand View > Toggle Tree View -- this will show you the entire folder within Atom
6. *Now if you already know some of what we're talking about,* open up the file in your browser -- `index.html`

#### Alternative: Use CodePen to code for this course

1. Go to codepen.io and click on the button `+New Pen`.
2. Focus on the window called "HTML". We'll work mostly in that one. Feel free to close the other windows.

Patience! Setting up your computer takes time and can be tricky, especially across platforms.

Once you're ready, you can move onto the next lesson.

## H.T.M.L. - "the building blocks of the internet"

Hyper Text Markup Language, or HTML, is the most elemental language of the internet. Everything you see within your web browser is an interpretation of HTML in some form of other, and it is essential to learn in all web development.

###### The syntax of most HTML is as follows:
* `<Tags>` - code that wraps around the content of HTML to designate a particular effect, sometimes inherent to the tag.
* `Attributes=""` - code inserted into tags to implement a particular effect that is external to the tag.
* _Elements_ - the combined syntax of tags, attributes, and elements.

```
e.g. Element = <tag attribute=”blahblah”>content content</tag>
```

#### HTML Tags:
Tags are used to mark up the beginning and end of an HTML element.

Almost everything in HTML needs to start and end with a tag
Everything is wrapped like layers of an onion, `<opened>` and `</closed>`
- e.g. `<div>”Hello!”</div>`
- *Note: not every tag is like this!*

###### Common Tags:
- `<html></html>` designates document as HTML
- `<div></div>` notes a block element in the page
- `<a></a>` anchor, activates a link in the page
- `<head></head>` contains meta information
- `<body></body>` contains browser information
- `<span></span>` notes an inline element

#### LET'S CODE!

You currently have a blank HTML page. Let's make it say the classic coding phrase "Hello World!"

First, to define the page to the browser as HTML, you have to add an `<html>` opening tag and `</html` closing tag.
```html
<html>
</html>
```

Let's add a header tag to create some text. Add the following code:
```html
<html>
  <h1></h1>
</html>
```

Still, no `Hello World!` We can add it now in between the `<h1></h1>` tags:
```html
<html>
  <h1>Hello World!</h1>
</html>
```

Check your browser. Did it work? If so, try some other exercises:
* Add a `<title></title>` to your page. Notice the change in the browser tab?
* Add a few `<div></div>` tags and put some text in them. What happens?
* Add a few `<span></span>` tags with text. What happens?


###### Irregular Tags:
- `<img />` creates an image in the page
- `<br />` creates a big break in the page
- `<hr />` creates a horizontal line
- `<link />` connects this to related documents
- `<input />` creates an input field


#### LET'S CODE

This one is nice and easy: Add a few `<

#### HTML Attributes:
HTML attributes inform the browser on what to do with a tagged piece of content.
Attributes generally appear as name-value pairs. 
```
<p class="foo">This is the content of an element with class 'foo'.</p>
```
###### The most common attributes are:
- id="" - id is used on only a single element"
- class="" - class can be used on multiple elements" *More on that in CSS*
- href=”” - hyperlink reference to an internal or external link
- src=”” - source file to an image, video, etc.
- style=”” - add some color, font, margins, etc.
- ^ *There’s a MUCH better way to do this via CSS - more on that in a different lesson!*

How do we check elements for whether they're talking to the browser? Use the **inspect element** feature!


#### What are IDs?
IDs are attributes that are used only on one element ONLY and noted with a “#” symbol in CSS
e.g.
```
HTML: 
<a id=”leesName”>Lee Ngo</a>
```
IDs are used to direct functions to unique elements in the HTML so that there’s no confusion

*e.g clicking to a specific part of page*

Classes are used to change or affect multiple items in an HTML document at once

*e.g. everything with class=”ninja” should have the same attributes*

In tandem, you can do a lot with HTML & CSS! Let's give it a shot!

## LET'S CODE!

###### Remember:
- Coding can be hard - be patient!
- Work in pairs! Even the pros do it
- Ask for help - we’re in a school!

#### Let's get started!
1. Open up your text editor
2. Navigate to your repo
3. Open up the following files
- index.html


#### Let's change the font!
1. Navigate to Google Fonts: https://www.google.com/fonts
2. Find a font you like and click "Add to Collection".
3. On the bottom right side of your screen click "Use".
4. On the "Use" page, scroll down to "Number 3" and copy the link tag provided.
5. Paste that link tag in your index.html file with the new link tag you copied from Google Fonts.
6. Copy the CSS code under “Number Four.”
7. Paste that code into your CSS under the body tag.
8. Save and refresh!

Did it work! Great! If not open up **Inspect Element** and see what happened.

## Play around in the sandbox!

Try one of the following:
- Change the name of the site to...whatever!
- Change all the navigation links & section headers
- Replacing the images with your own images - locally, online, etc.
- Show what you did with the others! 

# YOU DID IT! YOU'RE NOW A CODER!

Welcome to the cool kids club.

#### Want to code more? Check out Galvanize's Web Development Immersive Program!

- 24 Week Full-Time Program
- Scholarships available for those who qualify
- Learn more at http://galvanize.com/courses/web-development/

#### Looking for something more flexible? Check out our Evening Workshops!

- Zero to Web Designer
- Foundations of JavaScript
- Learn more at http://www.galvanize.com/workshops/

#### About the Authors

[Lee Ngo](http://linkedin.com/in/leengo) is an evangelist for Galvanize based in Seattle. Previously he worked for UP Global (now Techstars) and founded his own ed-tech company in Pittsburgh, PA. Lee believes in learning by doing, engaging and sharing, and he teaches code through a combination of visual communication, teamwork, and project-oriented learning.

You can email him at lee.ngo@galvanize.com for any further questions.
