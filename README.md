# Order Summary Component

A responsive order summary card built with **HTML5** and **CSS3** as a [Frontend Mentor](https://www.frontendmentor.io/) challenge. This project focuses on translating a Figma design into a clean interface using reusable CSS design tokens, Flexbox, and interactive hover states.

## Preview

![Desktop preview of the Order Summary Component](./assets/preview.jpg)

The component includes a music-themed illustration, annual subscription details, a **Change** link, and **Proceed to Payment** and **Cancel Order** buttons.

## Built With

- Semantic HTML elements and CSS3
- CSS custom properties for colors, spacing, and typography
- Flexbox for alignment and flexible spacing
- CSS media queries for smaller screens
- CSS transitions and hover states
- SVG illustrations and background artwork
- [Red Hat Display](https://fonts.google.com/specimen/Red+Hat+Display) via Google Fonts

No JavaScript framework, build tool, or package installation is required.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/damenta-yg/FEM-Order-Summary-Component.git
   ```

2. Open the project directory:

   ```bash
   cd FEM-Order-Summary-Component
   ```

3. Open `index.html` in a browser. You can also use a local development server, such as the **Live Server** extension in VS Code.

> The font is loaded from Google Fonts, so an internet connection is needed for the intended font to appear.

## Project Structure

```text
FEM-Order-Summary-Component/
├── index.html             # Component markup
├── style.css              # Styles, design tokens, and media query
├── Background.svg         # Decorative page background
├── Music_Flatline.svg     # Hero illustration
├── Path.svg               # Music icon
├── assets/
│   └── preview.jpg        # Screenshot for this README
└── README.md
```

The Figma source file is a design reference and is not needed to run the website.

## Key Concepts Practiced

### CSS design tokens

The stylesheet defines custom properties in `:root` for consistent colors, spacing, font sizes, font weights, and line heights.

### Flexbox layout

The annual-plan row uses Flexbox to align the music icon, plan details, and Change link. `margin-left: auto` pushes the Change link toward the right edge without a fixed margin.

### Responsive styling

A media query at `max-width: 30rem` adjusts parts of the component for narrow screens.

### Interactive states

The Change link and action buttons have hover styling with CSS transitions. These are visual interactions only; **the subscription and payment actions are not connected to an application or payment service**.

## Current Limitations and Next Improvements

- Make the Change control a functional link or button with appropriate behavior.
- Add visible `:focus-visible` styles for keyboard navigation.
- Improve small-screen padding and viewport-height handling.
- Refine semantic HTML and decorative-image alt text.
- Ensure form controls inherit the intended font.
- Test layout and text readability across more screen sizes.

## Acknowledgments

- Challenge and design inspiration: [Frontend Mentor](https://www.frontendmentor.io/)
- Font: [Red Hat Display on Google Fonts](https://fonts.google.com/specimen/Red+Hat+Display)

---

**Note:** This is a frontend practice project, not a working checkout or subscription service.
