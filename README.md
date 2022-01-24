# holberton-headphones
## An exercise in building a design from scratch

## Prompt from Holberton
In this project, you will implement from scratch, without any library, a web page. You will use all HTML/CSS/Accessibility/Responsive design knowledges that you learned previously.

You won't have a lot of instruction, you are free to implement it the way that you want - the object is simple: Have a fully functional web page that looks the same as the designer file. (Holberton_School_Headphones_company.fig)

## Organization
For this project, some tasks were iterative, giving the 0-, 1-, ..., 4-, pattern in the filenames. The final product includes:
- 4-index.html
- 07-styles.css
- form-test.html
- The assets have been cleaned up and placed in their folders

You can view this project live hosted using github pages [here](https://zacwoll.github.io/holberton-headphones/)
and see the prototyped contact us form [here](https://zacwoll.github.io/holberton-headphones/form-test.html)

Also I've included renders of both of those links under Final_Contact_Form.png and Final_Product.png

## Specific Insights from this Project
This project was a great example of working with Figma, a design tool with shared language between developers and designers. Distance is frequently measured in pixels, font size is clearly identifiable, This tool aims to help bridge the gap between what the designer has envisioned and how the developer can implement it.

In files 0-index.html & 0-styles.css, I was tasked with creating a hamburger menu for Mobile users. I really liked how this turned out, we take a 3 line hamburger menu, hide the center line and rotate the longer lines 45 degrees in place to form an 'X' that functions to close the menu.

In files 1-index.html & 1-styles.css, I implemented custom font icons to demonstrate the kinds of services a customer could expect from the company. These icons are designed to respond dynamically to screen size and organize themselves as 4/row, 2/row and 1/row at laptop, tablet and mobile sizes respectively.

In files 2-index.html & 2-styles.css, I set up pentagons as backgrounds that display the companies results in a creative, eye-catching way, matching the design document closely.

In 3-index.html & 3-styles.css I set up an easy contact form with a red CTA button, customers will now be able to easily send our fake company feedback.

The footer was added in 4-index.html & 4-styles.css, and it's meant to display the logo one last time, and leave links to the social outlets, Twitter, Facebook & Instagram

As a bonus, I created an additional form in form-test.html, and this one has some validation involved. The form on this file is pretty neat, there's client-side validation on the fields, if you do not include an '@' sign in the email the box lights up red and displays a small 'x', correct input is highlighted green and shows a '✓' mark. Simply clicking on each field with the cursor will reveal the requirements for input, and lightly shade the area to indicate focus.