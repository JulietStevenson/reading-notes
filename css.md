# What is CSS?

**CSS (Cascading Style Sheets):** allows you to give style to a webpage and make it look good.

## What is CSS for?

- Color
- Size
- Layout
- animation

## CSS Syntax

Css is a rule based language

**Selector:** Selects the HTML element that will be styled

> `h1 {color: red; font-size: 5em;}`

**Curly Braces {}:** contain the declaration
**Declaration:** tells the web how to style the text
- take the form of a property and value pairs
    - **Property:** specifies a style such as color, font-size
    - **Value:** specifies the outcome such as red, 5em


## CSS Modules

- CSS language is broken down into different modules
- Developed by the CSS Woriking Group
- CSS is constantly being updated
- Can only work on supported web browsers

# How to Add CSS

## Three Ways to Insert CSS

**External CSS:** change the look of a website by changing one file
- Each HTML page must include a reference to the CSS file  inside the link element, inside the head section.
- External CSS file should not contain any HTML tags

> `<head>`
> `<link rel="stylesheet" href="mystyle.css">`
> `</head>`

**Internal CSS:** change the look of one single HTML page
- defined inside the `<style>` element, inside the head section

> `<style>`
> `body {`
>  `background-color: linen;`
> `}`

**Inline CSS:** used to apply a unique style for a single element
- add style attributes to the relevant element in HTML document 

> `<p style="color:red;">This is a paragraph.</p>`

## Multiple Style Sheets

- If some properties have been defined for the same element in different style sheets (external/internal), the value from the *last* style sheet will be used
    - Defined after the link to the external style sheet

## Cascading Order**

- All styles in a page will follow in a "cascading" pattern
    1. Inline (inside an HTML element)
    2. External and Internal style sheets (in the head section)
    3. Browser default

## CSS Color Property

`color` property specifies color of text
- Property Values: 
    - color text: `red`
    - hex code: `#92a8d1`
    - RGB value: `rgb( 201, 76, 76)`
    - RGBA value: `rgb( 201, 76, 76, 0.6)`
    - HSLA value: `hsla(89, 43%, 51%, 0.6)`

**Reset Stylesheet:** reduce browser inconsistencies such as line height, margins, and font sizes

[HOME](README.md)
