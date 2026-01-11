# Harbor & Hearth - Responsive Homepage

A responsive homepage for a fictional coastal design company, built as part of Codecademy's Full Stack Development course.

## Live Preview
Link: https://imabyrd.github.io/Homepage-Project/

## About The Project

Harbor & Hearth Design Co. is a fictional New England-based interior design company specializing in coastal aesthetics. This project demonstrates responsive web design principles using HTML5 and CSS3 with Flexbox layouts.

### Built With

- HTML5
- CSS3
- Flexbox
- Google Fonts (Ysabeau family)
- SVG Icons

## Features

- **Fully Responsive Design** - Adapts seamlessly across desktop, tablet, and mobile viewports
- **Three Navigation Variants**
  - Desktop: Text-based logo with text navigation links
  - Tablet: SVG wave logo with text navigation links
  - Mobile: SVG wave logo with icon-based navigation
- **Flexbox Layouts** - Used throughout for flexible, responsive content arrangement
- **CSS Custom Properties** - Centralized color scheme using CSS variables
- **Interactive Elements** - Hover and active states on buttons and links
- **Accessible** - Semantic HTML structure with proper alt text and link labels

## Responsive Breakpoints

| Viewport | Width | Navigation Style |
|----------|-------|------------------|
| Desktop | > 768px | Text logo + text links |
| Tablet | 481px - 768px | SVG logo + text links |
| Mobile | ≤ 480px | SVG logo + icon links |

## Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Primary | `#2C3E50` | Headings, logo, nav links |
| Secondary | `#2c76b4` | Buttons, accent elements |
| Accent | `#F39C12` | Hover states |
| Light | `#ECF0F1` | Backgrounds, light text |
| Dark | `#34495E` | Body text, dark backgrounds |

## Project Structure

```
harbor-and-hearth/
├── index.html
├── README.md
└── resources/
    ├── styles.css
    └── images/
        ├── logo.png
        ├── exterior1.jpg.webp
        ├── exterior2.jpg.webp
        ├── interior1.jpg
        ├── interior2.jpg
        ├── interior3.jpg
        ├── interior4.jpg
        ├── interior5.jpg
        ├── employee-one.jpg
        ├── employee-two.jpg
        └── employee-three.jpg
```

## Getting Started

### View Live

Visit the live site: [Harbor & Hearth](https://yourusername.github.io/harbor-and-hearth/)

### Run Locally

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/harbor-and-hearth.git
   ```

2. Open `index.html` in your browser

## What I Learned

- Implementing responsive design with CSS media queries
- Using Flexbox for complex layouts
- Managing multiple navigation variants for different screen sizes
- Working with SVG icons and the `currentColor` property
- CSS custom properties (variables) for maintainable styling
- Debugging CSS selector specificity issues
- Safari-specific flexbox quirks and workarounds

## Future Improvements

- [ ] Add smooth scrolling for anchor links
- [ ] Implement a hamburger menu toggle for mobile
- [ ] Add form functionality to contact section
- [ ] Include animations and transitions
- [ ] Add a project detail page template

## License

This project was created as part of Codecademy's curriculum. Feel free to use it as inspiration for your own learning projects.

## Acknowledgments

- [Codecademy](https://www.codecademy.com/) - Project curriculum
- [Google Fonts](https://fonts.google.com/) - Ysabeau font family
- [Iconify](https://iconify.design/) - SVG icons

---

*Claude only used for CSS understanding*
*Created by Emma as part of the Codecademy Full Stack Development path*
