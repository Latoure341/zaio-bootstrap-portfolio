# Eric's Portfolio

A modern, responsive portfolio website built with Bootstrap 5, featuring automatic dark mode support using CSS variables and the `prefers-color-scheme` media query.

## Features

- **Responsive Design**: Built with Bootstrap 5 for mobile-first, responsive layouts
- **Auto Dark Mode**: Automatically switches between light and dark themes based on user's system preference
- **No JavaScript**: Pure CSS solution for theme switching using media queries
- **Modern UI**: Clean, professional design with smooth animations
- **Sections**: Home, About, Projects, and Contact sections
- **Bootstrap Components**: Utilizes Bootstrap's navigation, cards, and layout utilities

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with CSS variables for theming
- **Bootstrap 5.3.8**: CSS framework for responsive design
- **CSS Variables**: For dynamic theming
- **Media Queries**: `prefers-color-scheme` for automatic dark mode

## Project Structure

```
zaioPortfolio/
├── index.html          # Main HTML file
├── style.css           # Custom CSS styles with theme variables
├── assets/             # Static assets
│   └── background.jpeg # Background image for banner
└── README.md           # Project documentation
```

## Theme System

The portfolio uses CSS custom properties (variables) to implement automatic dark mode:

### Light Mode (Default)
- Background: White (#ffffff)
- Text: Black (#000000)
- Cards: White background
- Navigation: Semi-transparent dark overlay

### Dark Mode (Auto-detected)
- Background: Dark gray (#121212)
- Text: White (#ffffff)
- Cards: Dark gray background (#1e1e1e)
- Navigation: Semi-transparent light overlay

## Getting Started

1. **Clone or Download** the project files
2. **Open** `index.html` in your web browser
3. The theme will automatically adapt to your system's dark/light mode preference

## Customization

### Changing Colors
Edit the CSS variables in `style.css`:

```css
:root {
  --bg-color: #ffffff;      /* Light mode background */
  --text-color: #000000;    /* Light mode text */
  /* ... other variables */
}

@media (prefers-color-scheme: dark) {
  :root {
    --bg-color: #121212;    /* Dark mode background */
    --text-color: #ffffff;   /* Dark mode text */
    /* ... other variables */
  }
}
```

### Adding Content
- **About Section**: Update the personal information and description in `index.html`
- **Projects Section**: Add your project cards with images and descriptions
- **Contact Section**: Add your contact information and social links

## Responsive Breakpoints

- **Mobile**: < 576px
- **Tablet**: 576px - 768px
- **Desktop**: > 768px

## Browser Support

- Modern browsers with CSS custom properties support
- Chrome 49+, Firefox 31+, Safari 9.1+, Edge 16+
- Graceful degradation for older browsers (falls back to light mode)

##  License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Eric Mothupi**
- Email: tukamothupi@gmail.com
- Phone: +27 835560546
- LinkedIn: https://www.linkedin.com/in/tukaericmothupib3660a1b7/

---
*Built using Bootstrap and modern CSS*