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


#### Download the file for this class:
1. Go to https://github.com/GalvanizeOpenSource/Learn-To-Code-Intro-HTML
2. Click on the button on the right-hand side that says "Download ZIP"
3. Go to your downloads folder and double click on the .zip file to unzip it
4. From Atom: File > open, select the folder and then click "Open"
5. From Atom: If the file tree does not appear on the left hand View > Toggle Tree View -- this will show you the entire folder within Atom
6. Open up the file in your browser -- `index.html`

#### Alternative 1: Use CodePen to code for this course

1. Go to [http://codepen.io](http://codepen.io) and click on the button `+New Pen`.
2. Focus on the window called "HTML". We'll work mostly in that one. Feel free to close the other windows.

#### Alternative 2: Create an empty HTML file on your computer
1. If you've already downloaded Atom, you can save an empty file called `index.html`.
2. Open that file in your browser.

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

### HTML Tags:
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

This one is nice and easy: Add a few `<hr />` tags in your page between the `<html></html>` tags. What happens after you refresh?

Try more activities with void elements:
* Add a `<br />` tag and refresh. What happens?
* The other tags won't do much without an attribute. Let's dive deeper!

### HTML Attributes:
HTML attributes inform the browser on what to do with a tagged piece of content.
Attributes generally appear as name-value pairs. 
```
<p class="foo">This is the content of an element with class 'foo'.</p>
```
###### The most common attributes are:
- id="" - id is used on only a single element"
- class="" - class can be used on multiple elements" *More on that in our CSS class*
- href=”” - hyperlink reference to an internal or external link
- src=”” - source file to an image, video, etc.
- style=”” - add some color, font, margins, etc.
- ^ *There’s a MUCH better way to do this via CSS - more on that in a different lesson!*

#### LET'S CODE

Let's build a working link in your new file. Shamelessly, here's how you build a link to the Galvanize web page.
```html
<html>
  <h1>Hello World!</h1>
  <a href="https://galvanize.com">Click here to go to Galvanize!</a>
</html>
```
Notice the syntax of the `href=""` inside the `<a>` tag. That's all you need to create text that direct the content to the page.

Try some other attributes:
* Create an image from another page using the `<img src="" />` element. Use any image with a hyperlink.
* See if you can change the color of your text to green. *Hint: use the `style="color:green;` attribute.*


### Inspecting Your Code

How do we check elements for whether they're talking to the browser? Use the **inspect element** feature!

This is great for reviewing whether certain elements, attributes, or imported information are actually working.

If something didn't work, open up **Inspect Element** and see what happened.

## Play around in the sandbox!

Try one of the following (some of this is HTML5):
- Change the name of the site to...whatever!
- Create a `<body>` file that will be a placeholder for all your HTML content in the browser.
- Create a `<header>` and `<footer>` elements - what happens?
- Create a navigation bar with links and headers with the `<nav>` tag
- Trying adding a video from YouTube.com. *Hint: every YouTube clip contains "embedded" HTML content.*
- Show what you did with the others! 

# YOU DID IT! YOU'RE NOW A CODER!

Welcome to the cool kids club.

#### Want to code more? Check out Galvanize's Web Development Immersive Program!

- 24 Week Full-Time Program
- Scholarships available for those who qualify
- Learn more at [http://galvanize.com/courses/web-development/](http://galvanize.com/courses/web-development/)

#### Looking for something more flexible? Check out our Evening Workshops!

- Zero to Web Designer
- Foundations of JavaScript
- Web Development Immersive Prep
- Learn more at [http://www.galvanize.com/workshops/](http://www.galvanize.com/workshops/)

#### About the Authors

[Lee Ngo](http://linkedin.com/in/leengo) is an evangelist for Galvanize based in Seattle. Previously he worked for UP Global (now Techstars) and founded his own ed-tech company in Pittsburgh, PA. Lee believes in learning by doing, engaging and sharing, and he teaches code through a combination of visual communication, teamwork, and project-oriented learning.

You can email him at lee.ngo@galvanize.com for any further questions.
