## Table of contents

- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### Links

- Solution URL: https://github.com/shadymo2291/clipboard-landing-page-master-solution

### Built with

- Semantic HTML5 markup
- CSS custom properties
- grid
- flexbox
- position
- pseudo-elements
- hover effect

### What I learned

In this project, I used some CSS properties to help with responsive font size, such as @media
and pseudo-elements and hover effect

To see how you can add code snippets, see below:

.container {
width: 600px;
margin: 0 auto;
}

@media (max-width: 768px) {
.container {
width: 350px;
}
}

.buttom-blue,
.buttom-green {
padding: 10px 20px;
border-radius: 25px;
color: #fff;
transition: all 0.2s;
width: fit-content;
cursor: pointer;
}

.buttom-blue {
background-color: var(--second-color);
border: 1px solid var(--second-color);
box-shadow: 0 5px 20px -5px var(--second-color);
}

.buttom-blue:hover {
background-color: var(--hover-1-color);
}

.buttom-green {
background-color: var(--main-color);
border: 1px solid var(--main-color);
box-shadow: 0 5px 20px -5px var(--main-color);

}

.buttom-green:hover {
background-color: var(--hover-2-color);
}

### Continued development

I want to learn more about responsive websites and how to use the pseudo-elements and hover effect

### Useful resources

- [w3schools] https://www.w3schools.com/cssref/sel_hover.php
- [w3schools] https://www.w3schools.com/css/css_pseudo_elements.asp

## Author

- Frontend Mentor - [@shadymo2291](https://www.frontendmentor.io/profile/shadymo2291)

## Acknowledgments

I want to thank everyone who helped me to learn and to code, especially the Elzero Web School channel on YouTube
