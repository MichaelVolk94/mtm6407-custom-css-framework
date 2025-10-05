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

The font element was used as a way to connect a custom font with the @use tag, as it was required to move it forward to help control scope and reusability, specifically the chosen font.

### Containers
Inter CSS uses two types of container classes. One for headings, and one for form.

`<div class="container">`
`<!-- Headings -->`
![image](https://github.com/MichaelVolk94/mtm6407-custom-css-framework/blob/master/images/Headings.png)

`<form class="container w-75 my-3">`
  `<div class="row text-left mb-2">`
    `<label for="name" class="col-4">Full Name</label>`
    `<input type="text" class="col-8 " placeholder="Enter your name..">`
  `</div>`
  `<div class="row text-left mb-2">`
    `<label for="language" class="col-4">Language</label>`
    `<select name="language" id="language" class="col-8">`
      `<option value="English">English</option>`
      `<option value="French">French</option>
      <option value="French">Spanish</option>
      <option value="French">German</option>
      <option value="French">Russian</option>
      <option value="French">Japanese</option>
      <option value="French">Slovenian</option>
    </select>
  </div>
  <div class="row text-left">
    <label for="textarea" class="col-4">Tell me know what you think</label>
    <textarea id="textarea" cols="30" rows="5" placeholder="Enter the content.." class="col-8"></textarea>
  </div>
    
  <input type="submit" value="Submit" class="btn float-left">
</form>`

### Flexbox
Use `.d-flex`, `.flex-row` or one of the responsive variants (e.g., `.flex-column`, `.align-items`) to utilize flexbox display on alignments.

- Flex Direction
.flex-row sets a horizontal direction.
.flex-column sets a vertical direction.

(Code)
<div class="d-flex flex-row justify-content-between mx-3 bg-default-light">
            <div class="p-2 bg-default">Flex item 1</div>
            <div class="p-2 bg-default">Flex item 2</div>
            <div class="p-2 bg-default">Flex item 3</div>
        </div>
        <div class="d-flex flex-column align-items-end mx-3 bg-default-light mb-3">
            <div class="p-2 bg-primary-light">Flex item 1</div>
            <div class="p-2 align-self-center bg-primary-light">Flex item 2</div>
            <div class="p-2 bg-primary-light">Flex item 3</div>
        </div>

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


Custom CSS Framework - Web Development IV - MTM6407




-Installation, usage, and customization instructions must be added to the README file.
-https://www.markdownguide.org/cheat-sheet/ 