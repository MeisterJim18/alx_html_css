## Headphones Website

The Headphones Website is a single-page responsive web design project that showcases a fictional brand of premium headphones.  
It focuses on clean structure, modern styling, and adaptability across devices. The page layout is optimized for both desktop and mobile users, ensuring a smooth browsing experience.  
It demonstrates fundamental front-end development skills, including semantic HTML5 structure, CSS styling, and media queries for responsive behavior.

## Features

- Responsive design: The layout switches to a mobile version when the screen width is 480px or less.
- Link interaction: All links change color to #FF6565 on hover and when active.
- Button interaction: All buttons have an opacity of 0.9 on hover and when active.
- Centered content: The maximum content width is 1000px, centered horizontally.

## Technologies

- HTML5
- CSS3
- CSS media queries

## Project structure

alx_html_css/ └── headphones/ ├── index.html ├── styles.css └── README.md

## Usage

- Navigate to the headphones directory.
- Open index.html in a web browser.

## Key CSS Snippets

`css
/* Mobile version */
@media screen and (max-width: 480px) {
    /* Styles for screens 480px or less */
}

/* Links hover/active */
a:hover,
a:active {
    color: #FF6565;
}

/* Buttons hover/active */
button:hover,
button:active {
    opacity: 0.9;
}

/* Centered container */
.container {
    max-width: 1000px;
    margin: 0 auto;
}

Author

Jim Mariel Ngasseu
School assignment project