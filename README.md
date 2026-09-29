# Kumul Café: Web Design Project

> **“Fresh Flavours, Local Vibes.”**

## Project Overview

Kumul Café is a fictional café website created for the **IS229 Web Design Assessment** at the **Papua New Guinea University of Technology (PNGUoT)**.

The website provides users with information about Kumul Café, including its story, menu, gallery, events, contact information, and reservation enquiry form.

The project demonstrates the practical application of web design and development concepts using HTML5 and CSS3, together with responsive layouts, accessibility considerations, multimedia, forms, version control, testing, and deployment.

This website was created for educational and academic purposes.

---

## Continuation from Assignment 2

This project is a continuation and further development of the **Kumul Café website originally created for IS229 Web Design Assessment 2**.

In Assignment 2, the main focus was on establishing the website foundation. This included creating the HTML5 page structure, semantic elements, navigation, multimedia content, forms, accessibility considerations, basic CSS styling, and Git/GitHub version control.

For Assignment 3, the existing A2 website was retained and progressively enhanced rather than rebuilt from scratch. The focus was on improving the visual presentation, CSS organisation, responsive behaviour, accessibility, usability, testing, and deployment of the existing website.

The A3 development included:

- A reusable visual design system
- Improved CSS architecture
- CSS custom properties
- Flexbox layouts
- CSS Grid layouts
- Responsive navigation
- Media queries
- Responsive images
- Consistent cards, sections, forms, and buttons
- Keyboard focus states
- Typography and spacing improvements
- HTML and CSS validation
- Responsive testing
- GitHub Pages deployment

The five-page structure established in Assignment 2 was maintained:

- Home
- About
- Menu
- Gallery
- Contact

Therefore, Assessment 3 represents the **continued development, refinement, testing, and deployment of the original Kumul Café website from Assessment 2**.

---

## Project Goals

The main goals of the project are to demonstrate the practical application of web design and development principles, including:

- HTML5 semantic structure
- CSS3 styling
- Responsive web design
- Flexbox
- CSS Grid
- Media queries
- Multimedia and responsive images
- Forms and user input
- Accessibility and usability
- Typography and visual hierarchy
- Git and GitHub version control
- GitHub Pages deployment

---

## Website Pages

The website consists of five main pages.

| Page | Description |
|---|---|
| **Home** | Introduces Kumul Café and highlights key café content. |
| **About** | Presents the café story, background, and experience. |
| **Menu** | Displays café food and drink categories and menu information. |
| **Gallery** | Presents café images, events, and visual content. |
| **Contact** | Provides contact information and a reservation enquiry form. |

---

# A3 Development and Improvements

## Visual Design System

A reusable visual design system was introduced using CSS custom properties.

The design system defines reusable values for:

- Primary and secondary colours
- Accent colours
- Background and surface colours
- Text colours
- Border colours
- Typography sizes
- Line heights
- Spacing
- Border radius
- Shadows
- Content width
- Keyboard focus styling

This provides a consistent visual identity throughout the website and makes future styling changes easier to manage.

---

## CSS Architecture

The stylesheet was improved and organised using reusable classes and component-based styling.

Reusable styling was created for elements including:

- Site header
- Navigation
- Main content
- Content sections
- Content cards
- Action links
- Footer
- Menu categories
- Gallery layouts
- Forms

The use of reusable styles helps reduce unnecessary duplication and improves maintainability.

---

## Flexbox

CSS Flexbox was used for one-dimensional layouts.

The featured content cards use Flexbox to:

- Arrange cards horizontally on larger screens
- Allow cards to wrap when required
- Maintain consistent spacing
- Give cards flexible sizing
- Stack cards vertically on smaller screens

The implementation includes properties such as:

```css
display: flex;
flex-wrap: wrap;
gap: var(--space-lg);
