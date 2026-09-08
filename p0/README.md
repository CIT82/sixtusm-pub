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
```
```

## Section 3: Site Inventory (Bottom Half)

### About Section

- **Line Numbers:** 188-210
- **Top-Level Classes:** `container-fluid py-5 my-5`
- **Research:**
  - `container-fluid` makes the section stretch across the full width of the page.
  - `py-5` adds vertical padding to the top and bottom of the section.
  - `my-5` adds vertical margin above and below the section.

### Services Section

- **Line Numbers:** 213-297
- **Top-Level Classes:** `container-fluid services py-5 mb-5`
- **Research:**
  - `container-fluid` makes the section full width.
  - `services` applies the template's custom styling for the services section.
  - `py-5` adds vertical padding to the top and bottom.
  - `mb-5` adds margin below the section.

### Project Section

- **Line Numbers:** 300-389
- **Top-Level Classes:** `container-fluid project py-5 mb-5`
- **Research:**
  - `container-fluid` makes the section stretch across the full width of the page.
  - `project` applies custom styling for the project section.
  - `py-5` adds vertical padding.
  - `mb-5` adds margin below the section.

### Blog Section

- **Line Numbers:** 392-496
- **Top-Level Classes:** `container-fluid blog py-5 mb-5`
- **Research:**
  - `container-fluid` makes the section full width.
  - `blog` applies the template's custom blog styling.
  - `py-5` adds vertical padding.
  - `mb-5` adds spacing below the section.

### Team Section

- **Line Numbers:** 499-586
- **Top-Level Classes:** `container-fluid py-5 mb-5 team`
- **Research:**
  - `container-fluid` makes the section stretch across the page.
  - `py-5` adds vertical padding.
  - `mb-5` adds margin below the section.
  - `team` applies the template's custom styling for the team section.

### Testimonial Section

- **Line Numbers:** 588-684
- **Top-Level Classes:** `container-fluid testimonial py-5 mb-5`
- **Research:**
  - `container-fluid` makes the section full width.
  - `testimonial` applies custom styling for the testimonial section.
  - `py-5` adds vertical padding.
  - `mb-5` adds spacing below the section.

### Contact Section

- **Line Numbers:** 687-760
- **Top-Level Classes:** `container-fluid py-5 mb-5`
- **Research:**
  - `container-fluid` makes the contact section stretch across the full width of the page.
  - `py-5` adds vertical padding.
  - `mb-5` adds margin below the contact section.

### The Footer

- **Line Numbers:** 763-820
- **Top-Level Classes:** `container-fluid footer bg-dark wow fadeIn`
- **Research:**
  - `container-fluid` makes the footer stretch across the full width of the page.
  - `footer` applies the template's custom footer styling.
  - `bg-dark` gives the footer a dark background.
  - `wow` works with the WOW.js animation library.
  - `fadeIn` gives the footer a fade-in animation effect.

```
```
## Section 4: The Scripts

### Vendor JS Files

- **Line 828:** jQuery 3.6.4
  - Provides JavaScript functionality used by some of the template's plugins.

- **Line 829:** Bootstrap 5.0.0 Bundle
  - Provides Bootstrap's interactive JavaScript features.

- **Line 830:** WOW.js
  - Provides scroll-based animation effects.

- **Line 831:** Easing
  - Provides smooth easing effects for animations.

- **Line 832:** Waypoints
  - Helps trigger functions when scrolling to certain parts of the page.

- **Line 833:** Owl Carousel
  - Provides the carousel and slider functionality used in the template.

### Main JS File

- **Line 836:** `js/main.js`
  - This is the template's main custom JavaScript file.
  - It controls the template's custom interactive features and behavior.