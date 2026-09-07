# Project 0 - Template Analysis

- **Template Name:** HighTechIT
- **Bootstrap Version:** 5.0.0

## Section 1: The <head>

### External CSS

- **Google Web Fonts**
  - Inter
  - Saira
  - Used for the fonts and text styling on the website.

- **Font Awesome**
  - Provides icons used throughout the website, such as social media, phone, email, and location icons.

- **Bootstrap Icons**
  - Provides additional icons used throughout the template.

- **Animate.css**
  - Provides animation effects for different sections and elements on the website.

- **Owl Carousel**
  - Provides styling for carousel and slider sections.

- **Bootstrap CSS**
  - Provides the Bootstrap grid system, layout, buttons, navigation, spacing, and responsive design.

### Custom CSS

- [css/style.css](css/style.css)
  - This is the template's main custom stylesheet.
  - It controls the custom design and appearance of the HighTech template.

```
```
## Section 2: Site Inventory (Top Half)

### 1. The Navigation/Menu

- **Line Numbers:** 58-106
- **Top-Level Classes:** `navbar navbar-dark navbar-expand-lg py-0`
- **Research:**
  - `navbar` creates the main Bootstrap navigation structure.
  - `navbar-dark` styles the navigation for use on a dark background.
  - `navbar-expand-lg` keeps the menu collapsed on smaller screens and expands it on large screens.
  - `py-0` removes the top and bottom padding from the navbar.

### 2. The Logo/Branding

- **Line Numbers:** 62-64
- **Top-Level Classes:** `navbar-brand`
- **Research:**
  - `navbar-brand` identifies the HighTech name as the main branding area of the navigation.
  - It keeps the website branding positioned inside the navbar.

### 3. Carousel / Hero Section

- **Line Numbers:** 108-151
- **Top-Level Classes:** `container-fluid px-0`
- **Research:**
  - `container-fluid` allows the section to stretch across the full width of the page.
  - `px-0` removes the left and right padding so the carousel can extend across the page.

### 4. Fact Section

- **Line Numbers:** 154-185
- **Top-Level Classes:** `container-fluid bg-secondary py-5`
- **Research:**
  - `container-fluid` makes the section stretch across the full width of the page.
  - `bg-secondary` gives the section the secondary Bootstrap background color.
  - `py-5` adds vertical padding to the top and bottom of the section.