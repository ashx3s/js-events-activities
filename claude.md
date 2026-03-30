# Web 1 Javascript Events Practice Lab

This repo is a lab designed for students close to the end of their web 1 semester.

**OBJECTIVE**: Create a series of challenges for students to implement important javascript patterns in frontend web development.

**LANGUAGES & PATTERNS**

- HTML, CSS, JS
- semantic html that has a header with a navbar outside of main, and then the header with the h1 in main, a footer outside of main
- css: brief reset.css and style.css. prioritize reusable classes and clean readable code. clamp fonts, use rem sizing units when posible
  - color theme: Bauhaus design
  - fonts: geometric and congruent with bauhaus aesthetic, declare all typography rules in the fonts.css file and comment out an example of font setup for locally hosted in the README.md file
  - layouts: prioritize flexbox. use grid for the gallery
  - philosophy: mobile first media queries
- JS: declarative programming. you won't write really much of this but will be creating comments for students to follow.
- fonts and icons: import through the html file: iconify and google fonts
- README: use this to explain the goals, key topics, and definition of done for each challenge. be brief and easily scannable.

## Extra Challenge for file organization:

- download the fonts from google fonts and create the fonts rules

## Directory Structure

- index.html
- assets/
  - css/
    - reset.css
    - style.css
    - fonts.css
  - js/
    - script.js
    - characters.js
  - images/
- README.md

## Challenges

1. Button based event listeners
   - mobile nav menu toggle: we will provide the 2 sets of classes but they need to make it so that the button toggles. they should have to implement click/tap anywhere except the menu to close it as well. and finally it should flow naturally between desktop and mobile regardless of if the menu is left open
2. Image Carousel: I will provide a set of images, you will create the carousel css and layout. we want to have little dots hollow for not selected and darkend for selected (kind of like radio buttons). they will have to use js to generate this, the dots should be clickable, and there should be left and right buttons on the sides that use chevrons. The left right toggles are the priority task and then the bottom indicators being buttons is an extra challenge.

## Form Implementation

- a user name validation. on submit the js should check that there are no spaces or special characters like @ or leading with numbers. extra challenge: get them to replace any spaces with -
- filter and sort: include a list of characters from Mary Poppins with their name, age (estimated), description, and list of attributes. this should be kept in a characters.js file and be imported into the script file. implement a set of checkboxes for filter and a dropdown list to sort by name alphabetical a-z and z-a or by age young to old.

---

## Difficulty Level and amount of guidance

- describe clear TODOS but not enough for it to be a step by step. They should have to research and think it through but we should give guidance on the main things to consider
