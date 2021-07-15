# Dynamic Web Pages with JavaScript

**JavaScript:** a scripting language for web pages that allows you to create dynamic content such as animations, multimedia, and any other interactive feature on a website. 

- Store values inside variables
- **Strings:** operations on peices of text
- Run code in response to certain events such as a click 
- Browser runs JavaScript in order from top to bottom
- **Client-Side:** code that is run on the user's computer
- **Server-Side:** code run on the server (server side web languages are Python, Ruby, ASP.NET, and JavaScript)


## Adding JavaScript to Your Page

- Add the `<script>` element for JavaScript
- **External:** better than internal beucase it may be used across multiple HTML files
    - new file under `script.js`
    - add `<script src="script.js" defer></script>` to start JavaScript
-**Internal:** JavaScript can live inside of an HTML ffile
- Bad practice to add to HTML file and is inefficient
- Would have to include an attribute to every button you want JavaScript applied to. 

## Script Loading Strategies

- Code won't work if JavaScript is loaded and parsed before the HTML. Will slow down your site

**Async:** scripts using the `async` attribute will download the script without blocking the page while the script is being fetched.
- once the download is complete, the script will execute and blocks the page from rendering
- best to use when scripts in page run independently 

**Defer:** the `defer` attribute loads only in the order they appear on the page. Won't run until the page content as loaded

## Comments

> `// this is a comment`

> `*/ this is a`
> `multiline comment */`

## Variables

**variables:** containers for storing data (values)

` var x = 5;` x is a variable that stores the value 5 and is declared by the `var` keyword


## Identifiers

**Identifiers:** unique names that identify variables
- Names can contain letters, digits, underscores, and dolarsigns
- Must begin with a letter
- Names are case sensitive 
- JavaScript keywords cannot be used as names

## The Assignment Operator

`=` is an assignment operator and not an equal to operator 

`x = x + 5` assignes the value of x+ + 5 to x

## Data Types

**Strings:** text or number values
- written inside double or single quotes
- numbers are written without quotes

> `var pi = 3.14;`
> `var person = "John Doe";`
> `var person = 'Yes I Am!;`

## Declaring (Creating) JavaScript Variables

- Declare a JavaScript variable with the `var` keyword
- After declaration, variable has no value so you must **assign** a value
- Can declare many variables in one statement separating them by a comma
- A variable is `undefined` if it is declared without a variable 

>  `var carName;`
> `carName = "Volvo";`

OR

> `var carName = "Volvo";`

[HOME](README.md)
