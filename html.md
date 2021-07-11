# Structure Web Pages with HTML

## [Wireframes](https://careerfoundry.com/en/blog/ux-design/how-to-create-your-first-wireframe/)

**Wireframe:** a low fidelity sketch of a screen that allows designers to define and plan the IA of their design for a website, app, or product
- Based off of user research 
- Plan the layout and interaction of your interface


### Tools for Wireframing

- Pen and paper
- InVision
- Wireframe.cc
- UXPin

### How to make a wireframe

1. User research
2. Consolidate research for quick reference
3. User Flow and IA
4. Sketch and Draft - no need for aesthetics
5. Question: Are we creating something that meets the user's needs?
6. Add details such as CTA's
7. Gain feedback from user testing
8. Turn wireframes into prototypes with online tools such as Figma, Adobe XD, Sketch.


### 3 Key Principles for a Good Wireframe

- Clarity
- Confidence
- Simplicity


## HTML Basics

**HTML:** Hypertext Markup Language is the code used to structure a web page.
- Consists of a series of elements which you can use to change the functionality of them

### Anatomy of an HTML element

> `<p>My cat is very grumpy</p>`

**Opening Tag:** name of element (p)
**Closing Tag:** same as opening tag but includes a `/` before element name. States where the element ends
**Content:** content of the element which is the text
**Element:** Opening/closing tag and content together

**Attributes:** contain extra information about the element that doesn't appear in the content

> `<p> class="editor-note">My cat is very grumpy</p>`

`class`: attribute name
`editor-note`: attribute value

**Nesting Elements:** puting elements inside other elements
- Make sure to close the elements properly

> `<p>My cat is <strong>very</strong> grumpy.</p>`

**Empy Elements:** elements that have no content

> `<img src="images/firefox-icon.png" alt="My test image">`

- `<img>` does not have a closing tag becuase it doesn't wrap content 


### Anatomy of an HTML document

`<!DOCTYPE html>`: required preamble

`<html></html>`: wraps all content on the entire page (root element)

`<head></head>`: container for all the stuff you want to include on the HTML page that isn't visible on the web page such as keywords and page descriptions

`<meta charset="utf-8">`: allows the document to handle and produce most characters from most languages

`<title></title>`: Sets the title of you page that appears in the browser tab the page is loaded on

`<body></body>`: contains all the context on the web page that is visable


### Images

> `<img src="images/firefox-icon.png" alt="My test image">`

`src`: source attribute. The path to image file
`alt`: alternative attribute. Specify descriptive text for users who cannot see the image


### Marking up text

**Headings:** allow you to speciffy certain parts of the content are headings 
- Contains 6 heading levels. `<h1>-<h6>`

**Paragraphs:** elements for containing paragraphs of text
- `<p></p>`

**Lists:** 2 types of lists `<li>`
- Ordered: order of items matters `<ol>`
- Unordered:lists where order doesn't matter `<ul>`

**Links:** contains an anchor `<a>` (what the linked text will appear to say)

> `<a href="https://www.mozilla.org/en-US/about/manifesto/">Mozilla Manifesto</a>`

## Semantics 

**Semantics:** referes to the meaning of a piece of code
- HTML should be coded to represent the data that will be populated, not based on presentation and styling 
- ex: `<h1>`element means it contains the "top level heading on your page"
- Benefits of Semantic markup:
    - influence a website's SEO
    - helps screen readers
    - finding blocks of code is easier