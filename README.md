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

## Flexbox

CSS Flexbox was used for one-dimensional layouts.

The featured content cards use Flexbox to:

- Arrange cards horizontally on larger screens
- Allow cards to wrap when required
- Maintain consistent spacing
- Give cards flexible sizing
- Stack cards vertically on smaller screens

The implementation uses properties such as:

```css
display: flex;
flex-wrap: wrap;
gap: var(--space-lg);
align-items: stretch;
```

## CSS Grid

CSS Grid was used for two-dimensional page layouts.

Grid was applied to the About and Menu sections to create structured multi-column layouts. The Gallery section also uses a responsive grid structure.

The layouts use flexible grid columns and gaps so that content can reorganise at smaller viewport sizes.

Example:

```css
display: grid;
grid-template-columns: repeat(2, minmax(0, 1fr));
gap: var(--space-lg);
```

On smaller screens, the relevant grids change to single-column layouts where appropriate.

## Responsive Design

Responsive design was implemented using media queries, flexible units, responsive images, and layout changes for different viewport sizes.

The website was tested at:

- Desktop viewport
- Tablet viewport
- Mobile viewport

The mobile layout does not simply shrink the desktop layout. Navigation, cards, grids, and other content structures adapt to make the pages usable at smaller widths.

The mobile navigation changes to a vertically stacked layout, while content cards and grid sections reorganise into single-column arrangements where appropriate.

## Responsive Images and Media

Images are controlled using responsive sizing so they can adapt to the available content width without overflowing the page.

The gallery and other image-based content use consistent sizing, cropping, and border-radius styling to maintain a coherent visual presentation.

## Typography and Visual Hierarchy

Typography was improved through reusable font-size, line-height, spacing, and heading variables.

The design uses a consistent hierarchy for:

- Page headings
- Section headings
- Card headings
- Body text
- Supporting text

Spacing variables were also used to create a consistent visual rhythm between sections and components.

## Accessibility and Usability

Accessibility and usability were considered during the A3 refinement process.

The website includes:

- Semantic HTML5 structure
- Meaningful headings
- Alternative text for images
- Labels for form controls
- Keyboard-accessible links and controls
- Visible focus states
- Readable text and contrast
- Clear navigation
- Responsive layouts

Keyboard navigation was manually checked using the Tab key to confirm that links and interactive elements could receive focus visibly.

---

# Testing and Validation

## HTML Validation

All five HTML pages were checked using the W3C HTML Validator.

Validation result:

- **index.html — 0 errors, 0 warnings**
- **about.html — 0 errors, 0 warnings**
- **menu.html — 0 errors, 0 warnings**
- **gallery.html — 0 errors, 0 warnings**
- **contact.html — 0 errors, 0 warnings**

An HTML validation warning relating to the About page article heading was corrected by adding an appropriate `h3` heading for the article content. The page was then revalidated successfully.

## CSS Validation

The external stylesheet was checked using the W3C CSS Validator.

Validation result:

- **0 CSS errors**
- **8 warnings**

The warnings relate to CSS custom properties and repeated colour declarations. They do not indicate invalid CSS syntax or a broken stylesheet. The website was also manually tested in the browser after validation.

## Responsive and Browser Testing

The website was manually tested across desktop, tablet, and mobile viewport sizes.

The following areas were checked:

- Page layout
- Navigation
- Text readability
- Images
- Cards and sections
- Forms
- Links and buttons
- Grid layouts
- Flexbox layouts
- Mobile navigation
- Content overflow
- Keyboard focus states

The website remained usable across the tested viewport sizes.

## Navigation Testing

Navigation links were checked across all five pages to confirm that users can move between the Home, About, Menu, Gallery, and Contact pages.

## Accessibility Testing

Keyboard navigation and visible focus states were checked manually. Text readability and colour contrast were also reviewed across the main page layouts.

---

# Technologies Used

- HTML5
- CSS3
- CSS Custom Properties
- Flexbox
- CSS Grid
- Media Queries
- Responsive Web Design
- Visual Studio Code
- Git
- GitHub
- GitHub Pages

**No CSS frameworks such as Bootstrap or Tailwind were used.** No downloaded themes or page builders were used.

---

# Project Structure

```text
Kumul-Cafe-Web-Design-Project-A3/
├── index.html
├── about.html
├── menu.html
├── gallery.html
├── contact.html
├── README.md
├── css/
│   └── style.css
└── images/
    ├── barista.jpg
    ├── breakfast.jpg
    ├── cafe-food.jpg
    ├── cafe-interior.jpg
    ├── coffee.jpg
    └── dessert.jpg
```

---

# Version Control and Git History

Git and GitHub were used throughout the development process to track changes and maintain progressive development history.

Major A3 development commits included:

- **Create A3 visual design system**
- **Refine CSS architecture and reusable components**
- **Implement Flexbox and Grid layouts**
- **Improve responsive navigation and mobile layout**
- **Refine gallery responsive structure**
- **Fix About page HTML validation**
- **Update A3 project documentation**

The project was maintained on the `main` branch and pushed to the GitHub repository.

---

# Deployment

The completed website was published using GitHub Pages.

**Live Website:**

https://theodorah-roy-ger-42k.github.io/Kumul-Cafe-Web-Design-Project-A3/

**GitHub Repository:**

https://github.com/Theodorah-Roy-Ger-42K/Kumul-Cafe-Web-Design-Project-A3

GitHub Pages was configured to deploy from the `main` branch using the repository root as the publishing source.

---

# Submission Evidence

The A3 submission evidence includes:

- GitHub repository URL
- Live website URL
- Updated README.md
- Desktop responsive screenshot
- Tablet responsive screenshot
- Mobile responsive screenshot
- Browser/responsive testing evidence
- HTML validation evidence
- CSS validation evidence
- Accessibility/navigation testing evidence
- Complete source code and assets
- Meaningful Git history
- AI Use Declaration

---

# AI Use Declaration

AI tools were used as development and learning assistance during the project. They were used to support planning, explanations, troubleshooting, refinement, validation guidance, and documentation.

I reviewed, tested, edited, and validated the final website and remains responsible for the submitted work. AI-generated suggestions were not accepted without review, and the final implementation was checked through browser testing and validation.

---

# Academic Purpose

This website was developed as an individual practical assessment for **IS229 Web Design** at the **Papua New Guinea University of Technology**.

The project demonstrates the student's practical application of HTML5, CSS3, responsive web design, Flexbox, CSS Grid, accessibility, testing, Git/GitHub, and web deployment.

---

# Conclusion

Assessment 3 successfully extends the Kumul Café website developed in Assessment 2 into a responsive and visually refined website. The project demonstrates organised CSS architecture, reusable design components, Flexbox, CSS Grid, responsive navigation, media queries, responsive images, accessibility considerations, validation, browser testing, Git version control, and GitHub Pages deployment.

The completed website is available through the GitHub repository and published live website listed above.

