# Inter CSS
My CSS Framework assignment; Inter CSS, is about the process of how I was able to make my CSS framework to function properly.
Built speifically for simplicity, speed, and stability, Inter CSS greets users with flexibility and appealing components
of CSS frameworks. 

## Get Started/Installation
https://github.com/MichaelVolk94/mtm6407-custom-css-framework, add it to your project, and get started right away

## Usage
### Layout
**SCSS usage**
Inter CSS uses the following breakpoints in our source Sass files for the layout, and components.
`@use './reset' as reset;`
`@use './variables/' as variables;`
`@use './base/' as base;`
`@forward './font-inter';`

It's required to use SCSS reset for this framework. Resets adresses inconsistencies in how browsers render default styles for HTML elements. The reset element was used on the html to fix mobile safari users to increase font size on landscape mode, giving the live server instant stability. 

The font element was used as a way to connect a custom font with the `@use` tag, as it was required to move it forward to help control scope and reusability, specifically the chosen font.

### Containers
Inter CSS uses two types of container classes. One for headings, and one for form.

`<div class="container">`
`<!-- Headings -->`

Example:

![image](https://github.com/MichaelVolk94/mtm6407-custom-css-framework/blob/master/images/Headings.png)

(Code)
![image](https://github.com/MichaelVolk94/mtm6407-custom-css-framework/blob/master/images/heading-code.png)

Form example:
![image](https://github.com/MichaelVolk94/mtm6407-custom-css-framework/blob/master/images/form.png)

(Code)
![image](https://github.com/MichaelVolk94/mtm6407-custom-css-framework/blob/master/images/Form-code.png)


### Flexbox
Use `.d-flex`, `.flex-row` or one of the responsive variants (e.g., `.flex-column`, `.align-items`) to utilize flexbox display on alignments.

### Flex Direction
- .flex-row sets a horizontal direction.
- .flex-column sets a vertical direction.

Example:
![image](https://github.com/MichaelVolk94/mtm6407-custom-css-framework/blob/master/images/flexbox.png)

(Code)
![image](https://github.com/MichaelVolk94/mtm6407-custom-css-framework/blob/master/images/flex-direction.png)

### Width
Use the following classes to control the width of elements:

`.w-25 (width 25%)`
`.w-50 (width 50%)`
`.w-75 (width 75%)`
`.w-100 (width 100%)`
`.w-auto (width auto)`

### Text Alignment
Use the following classes to set the text alignment:
`.text-left`
`.text-right`
`.text-justify`
`.blockquote`
`.blockquote-footer`

Example:
![image](https://github.com/MichaelVolk94/mtm6407-custom-css-framework/blob/master/images/Blockquote.png)

(Code)
![image](https://github.com/MichaelVolk94/mtm6407-custom-css-framework/blob/master/images/blockquote-code.png)

### Table
Use the following classes to create and style table elements:
- .table

Example:
![image](https://github.com/MichaelVolk94/mtm6407-custom-css-framework/blob/master/images/Table.png)

(Code)
![image](https://github.com/MichaelVolk94/mtm6407-custom-css-framework/blob/master/images/table-code.png)

### Lists
Inter CSS offers basic, default styling for unordered lists, ordered lists, and description lists.

Example:
![image](https://github.com/MichaelVolk94/mtm6407-custom-css-framework/blob/master/images/List.png)

(Code)
![image](https://github.com/MichaelVolk94/mtm6407-custom-css-framework/blob/master/images/list-code.png)


Custom CSS Framework - Web Development IV - MTM6407
