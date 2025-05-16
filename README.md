
# coding-beyond-bugs

Welcome to **Coding Beyond Borders and Bugs** – a responsive, multipage blog website that celebrates tech journeys, coding adventures, and the inspiration behind innovative software development.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [File Structure](#file-structure)
- [Technologies Used](#technologies-used)

- [Future Improvements](#future-improvements)
- [License](#license)

## Overview

**Coding Beyond Borders and Bugs** is a blog website designed to introduce visitors to the stimulating world of tech storytelling. The site includes:
- A **Homepage** that welcomes users with a hero image, an introduction to our tech adventures, and a call-to-action button directing readers to the **Story** page.
- A **Story Page** featuring a rich narrative and navigation buttons (e.g., "Back to Home" and "Sign Up") for a seamless user experience.
- (Optional) A **Sign Up/Contact** page referenced via the navigation bar for users who want to join our community.

Interactivity is a core component of the project. Visitors can customize the header subtitle and background color (with animations), interact with an image gallery that cycles through images on click, and (if implemented) enjoy real-time form validation on the sign-up page.
The site is live at https://eokusimba.github.io/coding-beyond-bugs/
## Features

- **Responsive Design:**  
  - Developed with a mobile-first approach using HTML5 and CSS3.
  - Utilizes media queries to ensure a smooth experience on any device.

- **Interactive Elements:**  
  - Dynamic header controls (change subtitle and background color with animations).
  - Interactive hero image gallery with animated transitions.
  - Keyboard interactions and double-click actions for added fun and user engagement.

- **Multipage Navigation:**  
  - Consistent navigation menus across pages (Home, Story, and Sign Up) ensure a cohesive browsing experience.

- **Persistent User Preferences:**  
  - Uses Local Storage to maintain header customizations (e.g., subtitle and background color) across sessions.

- **Form Validation:**  
  - (If the Sign Up page is implemented) Real-time feedback helps users create accounts with valid information.

## File Structure

├── index.html # Homepage with introduction, hero image, and call-to-action button

├── story.html # Story page featuring a detailed narrative and navigation buttons

├── contact.html # (Optional) Sign Up page for user registration (linked via navigation)

├── style.css # Main stylesheet containing responsive and aesthetic styles

├── script.js # JavaScript file handling interactivity, animations, and local storage

└── README.md # This documentation file


## Technologies Used

- **HTML5:** Provides semantic structure for accessible and well-organized content.
- **CSS3:** Implements a responsive design using modern layout techniques (Flexbox, media queries) and CSS animations.
- **JavaScript:** Adds dynamic functionality (header and image interactions, form validation, and local storage persistence).
- **Git & GitHub:** Used for version control and project hosting.
  

## Future Improvements

1. **Expand Sign Up Functionality**: Incorporate back-end integration for user registration and authentication.

2. **Enhanced Animations**: Explore more advanced transitions using additional CSS animations or JavaScript libraries.

3. **Additional Pages**: Consider adding more pages (e.g., Blog Post Archive, Contact Information, etc.) to expand the content.

4. **Accessibility Enhancements**: Continue improving the site for accessibility, including ARIA attributes and better keyboard navigation paths.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
