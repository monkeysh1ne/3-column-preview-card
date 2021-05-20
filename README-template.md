# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot - Desktop

![](images/screenshot.jpg)

### Links

- Solution URL: [https://practical-einstein-36d417.netlify.app/](https://practical-einstein-36d417.netlify.app/)
- Live Site URL: [https://practical-einstein-36d417.netlify.app/](https://practical-einstein-36d417.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow
- SASS - For styles
- Figma - For assessing design

### What I learned

Positioning using Flex is still a largely undiscovered country for me. Positioning elements in general remains one of my greatest challenges. I feel I am making good progress though and am happy with the overall outcome.

This was my first project using SASS and the SASS compiler Visual Studio Code extension. It was also the first time I have incorporated partials for my CSS to improve modularity and ease of maintenance. For the same reason I also used variables for colors.

I've never coded SVGs but found this pretty straigh forward as it turned out (just drop the code into my document!)

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```

The following is an example of my use of CSS variables for colors...

```css
// colors
$first-card-bg: hsl(31, 77%, 52%)
$second-card-bg: hsl(184, 100%, 22%)
$third-card-bg: hsl(179, 100%, 13%)
$transparent-white: hsla(0, 0%, 100%, 0.75) //paragraphs
$very-light-gray: hsl(0, 0%, 95%) //(background, headings, buttons)
```

...and CSS partials.

```css
@import helpers;
@import typography;
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
