# sign-up-form

---

This is my submission for the [Sign-up Form project](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-sign-up-form) from [The Odin Project](https://www.theodinproject.com/). The idea behind the project is to apply the intermediate HTML and CSS skills learned just prior to working on this project.

Some of the skills used throughout this work are:
- CSS units (i.e. viewport)
- Pseudoclasses and pseudoelements
- Custom properties
- CSS functions
- Form basics
- Form validation

The main files are the HTML document, `index.html`, and the CSS stylesheet, `style.css`. Form validation is rudimentary in that only HTML properties are used to validate user input, and CSS is used to add visual cues when the input is not valid. A consequence of this is that there is no check for passwords to match in the password confirmation input, as this is commonly done using JavaScript.

The design of this form is *not* responsive, due to this material being taught at a later stage in the course. This form is designed to be viewed on fairly large screens with an aspect ratio in the vicinity of 16:9. For reference, I made sure that the layout works as intended on a 15.6-inch display as well as on a larger monitor. Do not attempt to render this form on a mobile phone or a smaller screen because the form will at best be unreadable and at worst break.

Below is the design file that was used as a guide:

![Design file](assets/sign-up-form.png)