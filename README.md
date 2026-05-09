## Building QR code component

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Link](#link)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

This is the first of many challenges in my coding journey. This particular challenge covers the basics of HTML and CSS, with the task of creating a QR card displayed on a page alongside relevant information. Completing challenges like will be a great way to sharpen my coding skills by building realistic, hands-on projects.

### Screenshot

![](./qr-component.jpg)

### Links

- Live Site URL: https://ewusiessel.github.io/qr-code-component/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

I learned how elements are stacked in a block layout, how to use Absolute positioning to override the natural document flow, and how to use the Margin: auto property to center a component on a page. I also developed the problem-solving skill of breaking down a challenge into smaller, manageable steps. 

```css
.white-card {
        width: 280px;
        height: 450px;
        background-color: white;
        margin-top: 200px;
        margin-left: auto;
        margin-right: auto;
        border-radius: 18px;
        box-shadow: 5px 5px 10px 0px rgba(151, 151, 151, 0.2);
      }
```
```css
   img {
        width: 250px;
        position: absolute;
        margin: 15px;
        border-radius: 9.5px;
      }
```

### Continued development

I will continue exploring the different display properties and their characteristics, while also diving deeper into Flexbox and applying it in my next project

### Useful resources

- (https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/line-height) - This helped me discover the line-height property for fine-tuning the spacing between text
- (https://www.joshwcomeau.com/css/center-a-div/) - This is an amazing article which helped me  understand the concept of centering with margin auto property and centering text.

## Author

- Frontend Mentor - [@ewusiessel](https://www.frontendmentor.io/profile/ewusiessel)
