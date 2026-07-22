#Frontend Mentor - Digital-bank-landing-page

This is a solution to the Frontend Mentor Challenge (https://www.frontendmentor.io/challenges/digital-bank-landing-page-WaUhkoDN)

## Overview

### The Challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size (Mobile, Desktop)
- See hover and focus states for all interactive elements on the page
- Toggle the mobile navigation menu via the hamburger icon

### My process

### Built with

- Semantic HTML markup
- SASS/SCSS and Bootstrap
- Flexbox & CSS Grid
- Mobile-first workflow

### What was challenging for me

- **Working with Bootstrap Utilities:** Integrating Bootstrap for this layout was challenging.
- **Positioning the Phone Mockup Image:** Aligning the hero phone mockup image proved to be the hardest part of this project.
  Getting it to overflow the hero container correctly while remaining responsive across different screen sizes—without creating horizontal scrollbars—was quite tricky,
  and it remains a work in progress that I plan to refactor and perfect.

### Summary

- During the development of the Digital Bank Landing Page, my biggest technical challenge was working with Bootstrap to handle complex layout positioning—specifically aligning 
the hero phone mockup image (image-mockups.png). Getting the graphic to partially overflow the main container on desktop viewports while staying responsive and preventing unwanted 
horizontal scrollbars proved particularly difficult within Bootstrap's rigid grid system.
- To tackle this, I experimented with utility classes and custom CSS overlays, using relative and absolute positioning combined with overflow: hidden on parent containers.
  While this approach helped manage the layout across most screen sizes, achieving a pixel-perfect match with the original design remained a hurdle.
- Given more time, I would refactor the layout by removing Bootstrap in favor of custom CSS Grid and Flexbox combined with SASS/SCSS. This would provide cleaner, more semantic code
  and offer absolute control over absolute positioning, media queries, and responsive background layers. Additionally, I would implement focus trapping and keyboard navigation controls
  to enhance overall accessibility (A11y) for the mobile menu.
