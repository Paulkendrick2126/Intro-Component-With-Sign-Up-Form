# Intro-Component-With-Sign-Up-Form
Live site   https://unrivaled-signup.netlify.app/
Intro Component With Sign-Up Form (Challenge from frontend mentor)

# Frontend Mentor - Intro component with sign up form solution

This is a solution to the [Intro component with sign up form challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/intro-component-with-signup-form-5cf91bd49edda32581d28fd1). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
This project involved building an intro component with a sign-up form, replicating the design and functionality provided by Frontend Mentor. The goal was to practice essential HTML, CSS, and potentially JavaScript skills for creating responsive and user-friendly UI components.

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Receive an error message when the `form` is submitted if:
  - Any `input` field is empty. The message for this error should say *"[Field Name] cannot be empty"*
  - The email address is not formatted correctly (i.e. a correct email address should have this structure: `name@host.tld`). The message for this error should say *"Looks like this is not an email"*

The challenge focused on:

Constructing the intro component using HTML, including headings, paragraphs, and potentially images to convey the purpose of the application.
Developing a sign-up form using HTML form elements like input fields, textarea (optional), and a submit button.
Applying CSS styles to achieve the visual design specified in the challenge guidelines. This might involve styling text, backgrounds, layout, and responsiveness for different screen sizes.
Implementing JavaScript for form validation (e.g., checking email format, password strength) or enhanced user experience (e.g., displaying success messages).

### Screenshot

![](./images/Screenshot%202024-04-12%20210517.png) 


### Links
-Frontend Mentor Challenge: Link to the specific intro component with sign up form challenge on Frontend Mentor:(https://www.frontendmentor.io/challenges/intro-component-with-signup-form-5cf91bd49edda32581d28fd1/hub)
- Solution URL: [Add solution URL here](https://github.com/Paulkendrick2126/Intro-Component-With-Sign-Up-Form)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
1. Initialize the project as a public repository on [GitHub](https://github.com/). Creating a repo will make it easier to share your code with the community if you need help. If you're not sure how to do this, [have a read-through of this Try Git resource](https://try.github.io/).
2. Configure your repository to publish your code to a web address. This will also be useful if you need some help during a challenge as you can share the URL for your project with your repo URL. There are a number of ways to do this, and we provide some recommendations below.
3. Look through the designs to start planning out how you'll tackle the project. This step is crucial to help you think ahead for CSS classes to create reusable styles.
4. Before adding any styles, structure your content with HTML. Writing your HTML first can help focus your attention on creating well-structured content.
5. Write out the base styles for your project, including general content styles, such as `font-family` and `font-size`.
6. Start adding styles to the top of the page and work down. Only move on to the next section once you're happy you've completed the area you're working on.

11. Understanding the Challenge: I thoroughly reviewed the challenge guidelines, including the design mockup and any specific requirements.

22. HTML Structure: I planned the HTML structure for both the intro component and the sign-up form, ensuring proper hierarchy and element usage.
33. CSS Styling: I progressively styled the component using CSS, focusing on replicating the design, achieving responsiveness, and maintaining good code organization.
44. (Optional) JavaScript Implementation: If the challenge involved JavaScript, I implemented the necessary functionality for form validation or enhanced user experience.
55. Testing and Refinement: I thoroughly tested the component across different screen sizes and browsers, making refinements to ensure optimal functionality and visual consistency.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Desktop design workflow
- [Styled Components](https://styled-components.com/) - For styles


### What I learned

This challenge helped me solidify my understanding of:

Building responsive web components using HTML and CSS.
Implementing basic form elements and styling techniques.
(Optional) Applying JavaScript for form validation or user experience enhancements.
The importance of following design guidelines and best practices.




To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>

<div class="field-group">
                <label for="lastName">Last Name</label>
                <input type="text" name="lastname" id="lastname" placeholder="Last Name">
                <img src="images/icon-error.svg" class="error-icon" alt="error image">
                <p class="error-text">last name cannot be empty</p>
              </div>
```


```css
.proud-of-this-css {
  color: papayawhip;
}

@media screen and (max-width: 1024px){
    .container{
        flex-direction: column;
    }

    .left-col{
        text-align: center;
        margin-bottom: 10px;
        
    }
}
```


```js
const proudOfThisFunc = () => {
  console.log('🎉')
}

form.addEventListener("submit", (e)=>{
  e.preventDefault();
  inputs.forEach((input) => {
    if (!input.value) {
      input.parentElement.classList.add("error");
    } else {
      input.parentElement.classList.remove("error");
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.



### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.



### Useful resources

- [Example resource 1](https://stackoverflow.com/questions/29716543/form-validation-using-javascript) - This helped me for form validation. I really liked the answers and will use it going forward.
- [Example resource 2](https://stackoverflow.com/questions/46155/how-can-i-validate-an-email-address-in-javascript) - This is an amazing article that helped me understand validation. I'd recommend it to anyone still learning this concept.


## Author

- Website - [Links](https://linktr.ee/paul_ad)
- Frontend Mentor - [@https://www.frontendmentor.io/profile/Paulkendrick2126](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@littlehomiz_ken](https://twitter.com/littlehomiz_ken)



## Acknowledgments

This is where I give a hat tip to everyone who helped me out on this project. Thank you to all who provided support and guidance during the development process. Jojo and CJ Panda


