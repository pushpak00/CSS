# CSS (Cascading Style Sheets)

### CSS (Cascading Style Sheets) is the code that styles web content.

## What is CSS?
Like HTML, CSS is not a programming language. It's not a markup language either. CSS is a style sheet language. CSS is what you use to selectively style HTML elements. For example, this CSS selects paragraph text, setting the color to red:
```
p {
  color: red;
}
```

Let's try it out..
  * Inside your first-website folder, create another new folder called styles.
  * Using a text editor, paste the three lines of CSS shown above into a new file.
  * Save the file inside your styles folder with a filename of style.css.

To make the code work, we still need to apply this CSS (above) to your HTML document. Otherwise, the styling won't change the appearance of the HTML.

  * Open your index.html file. Paste the following line inside the HTML head (between the <head> and </head> tags):
```
<link href="styles/style.css" rel="stylesheet" />
```

  * Save index.html and load it in your browser.

 <img width="476" alt="Screenshot 2025-01-03 113615" src="https://github.com/user-attachments/assets/81c9ab69-5c0a-4dd2-a307-13b6fe61e922" />

The whole structure is called a ruleset. (The term ruleset is often referred to as just rule.)

#### Selector:
This is the HTML element name at the start of the ruleset. It defines the element(s) to be styled (in this example, < p > elements). To style a different element, change the selector.

#### Declaration:
This is a single rule like color: red;. It specifies which of the element's properties you want to style.

#### Properties:
These are features of an HTML element that you can change the values of, to make it styled differently. (In this example, color is a property of the < p > elements.) In CSS, you choose which properties you want to affect in the rule.

#### Property value:
To the right of the property—after the colon—there is the property value. This chooses one out of many possible appearances for a given property. (For example, there are many color values in addition to red.)

**Note the other important parts of the syntax:**

  * Apart from the selector, each ruleset must be wrapped in curly braces. ({})
  * Within each declaration, you must use a colon (:) to separate the property from its value or values.
  * Within each ruleset, you must use a semicolon (;) to separate each declaration from the next one.


To modify multiple property values in one ruleset, write them separated by semicolons, like this:
```
p {
  color: red;
  width: 500px;
  border: 1px solid black;
}
```

### Selecting Multiple Elements
You can also select mulltiple elements and can apply a single ruleset to all of them. Seperate multiple selector by comma.
```
p,
li,
h1 {
  color: red;
}
```

### Diffrent Types of Selectors
visit this link [Diffrent types of selectors ](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website/Styling_the_content#different_types_of_selectors)










