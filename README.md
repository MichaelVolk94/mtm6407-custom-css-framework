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
Inter CSS uses two types of container classes





Custom CSS Framework - Web Development IV - MTM6407




-Installation, usage, and customization instructions must be added to the README file.
-https://www.markdownguide.org/cheat-sheet/ 