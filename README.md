# webdev-portfolio-website
Responsive HTML website layout for on pure HTML + CSS. Freelance portfolio site. Finishing the layout with Figma. Let's make an adaptation for mobile devices

Materials for the website
Layout in Figma : https://www.figma.com/file/NlH3naDNbp8x1rGeS27GLy/Freelancer-portfolio?node-id=0%3A1

Reset Styles reset.css : 

```css
CSS 

/* Reset and base styles  */
* {
	padding: 0px;
	margin: 0px;
	border: none;
}

*,
*::before,
*::after {
	box-sizing: border-box;
}

:focus,
:active {
	/*outline: none;*/
}

a:focus,
a:active {
	/* outline: none;*/
}

/* Links */

a, a:link, a:visited  {
    /* color: inherit; */
    text-decoration: none;
    /* display: inline-block; */
}

a:hover  {
    /* color: inherit; */
    text-decoration: none;
}

/* Common */

aside, nav, footer, header, section, main {
	display: block;
}

h1, h2, h3, h4, h5, h6, p {
    font-size: inherit;
	font-weight: inherit;
}

ul, ul li {
	list-style: none;
}

img {
	vertical-align: top;
}

img, svg {
	max-width: 100%;
	height: auto;
}

/* Form */

input, textarea, button, select {
	font-family: inherit;
    font-size: inherit;
    color: inherit;
    background-color: transparent;
}

input::-ms-clear {
	display: none;
}

button, input[type="submit"] {
    display: inline-block;
    box-shadow: none;
    background-color: transparent;
    background: none;
    cursor: pointer;
}

input:focus, input:active,
button:focus, button:active {
    outline: none;
}

button::-moz-focus-inner {
	padding: 0;
	border: 0;
}

label {
	cursor: pointer;
}

legend {
	display: block;
}


```

Animation Library AOS : https://michalsnik.github.io/aos/
CDN storage — AOS : https://cdnjs.com/libraries/aos
