# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview
The project consists of a single HTML file and a CSS file. The HTML file contains a container div that holds the QR code and text elements. The CSS file contains styles for the container div, the QR code, and the text elements.

The QR code is created using an image file, and is displayed within a div that has a fixed width and height. The text elements are contained within another div, and are styled to have a white background with a blue border.

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

1. First, I created a new HTML file and added the basic structure of an HTML document, including the head and body tags.
2. I added the necessary meta tags for character set and viewport.
3. I added a link to the favicon and gave the page a title.
4. I created a style tag within the head tag to add CSS styles to the    HTML file.
5. I added a background color to the body of the page.
6. I created a container div with a class of qr-code-container and added CSS styles to center the container on the page and give it some padding.
7. Inside the container div, I added a div element with a class of qr-code, which is where the QR code image will be displayed. I added CSS styles to center the QR code and give it a shadow and rounded corners.
8. Below the QR code, I added another div element with a class of text-container. I added CSS styles to center the text and give it a background color, rounded corners, and a shadow.
9. Inside the text-container div, I added two p elements, one with a class of bold-text, which contains a bolded message, and the other containing a message about scanning the QR code.
10. Finally, I added an image of a QR code and saved it with a file name of image-qr-code.png, which I then linked to in the CSS for the .qr-code class.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Box shadow
- Background Image
- Border radius

### What I learned

1. Using flexbox to position and layout elements:
The use of flexbox made it easy to position and layout the elements on the page in a responsive manner. The container element .qr-code-container is set to display: flex; and flex-direction: column; to stack the child elements vertically.

2. Styling with CSS:
CSS is used to style the QR code component with various properties like background-color, padding, box-shadow, border-radius, etc. The properties are used to make the component look visually appealing and user-friendly.

3. Setting a background image with CSS:
The .qr-code class has a background-image property set to a URL pointing to an image of a QR code. The property is used to display the image as the background of the div.

4. Using media queries for responsive design:
The viewport meta tag and the @media rule in CSS are used to make the component responsive on different screen sizes. The component adjusts to the width of the viewport, and the text container's max-width is set to 320px to prevent it from overflowing on smaller screens.

5. Creating semantic HTML markup:
Semantic HTML markup is used to structure the content of the page in a meaningful and understandable way. The head section contains metadata, while the body section contains the page content. The div element is used to group related elements together, and the p element is used to define paragraphs of text.

### Useful resources

- [Dicoding](https://www.dicoding.com/) - This website helped me acquire the fundamentals of web development.
- [Stack Overflow](https://stackoverflow.com/) - This is a common Q&A website for programmers. In this project, I used this website almost everytime I forgot something and needed a quick solution.

## Author

- Website - [@nurwandhika](https://github.com/nurwandhika)
- Frontend Mentor - [@nurwandhika](https://www.frontendmentor.io/profile/nurwandhika)
- Twitter - [@nurwandhikar](https://www.twitter.com/nurwandhikar)
