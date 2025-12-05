# mtm6201final — Happy Paws Animal Shelter (Pet Adoption Website)

## Project Overview
This repository contains a responsive 3page website built using Bootstrap. The site is a prototype for Happy Paws Animal Shelter and includes:

 `index.html` — Homepage (hero, featured pets, how it works, testimonials)
 `petprofiles.html` — Pet Profiles (search & filters, pet grid, pagination)
 `petpage.html` — Individual Pet Profile (hero photo, details, adopt CTA)
 `css/styles.css` — Custom theme and overrides (CSS variables used to customize Bootstrap)
 `images/'

This project was built to fulfill the MTM6201 final project brief: responsive design, accessibility, semantic markup, Bootstrap framework, and a small additional CSS library (Animate.css).

## Process, Challenges & Solutions (For interview)
Process
1. User & stakeholder research > created persona (Mark) and sitemap.
2. Lowfidelity wireframes for Desktop/Tablet/Mobile.
3. Highfidelity mockups and final HTML/CSS implementation using Bootstrap.
4. Tested responsiveness across breakpoints and keyboard accessibility.

Challenges
 Accessibility: Ensuring components are keyboardfocusable and include ARIA where needed.  
  Solution: Added a skip link, visible focus styles, `arialabel` attributes, and semantic markup.
 Image responsiveness: Need to provide multiple image sizes and use `picture` and `srcset`.  
  Solution: Used `picture` element with multiple `source` tags to demonstrate approach; instruct to add optimized images.
 Customizing Bootstrap theme: Changing default Bootstrap look while keeping its utility.  
  Solution: Used CSS variables and a small custom stylesheet to override button and color properties.

Learnings
 Overriding Bootstrap cleanly with a small custom stylesheet and CSS variables keeps code maintainable.
 Planning accessible interactions upfront (skip link, keyboard focus) greatly improves the user experience for all users.
 Using `picture` + `srcset` is essential for performance and responsive images.


 ## Figma link: https://www.figma.com/design/xyZqccm4C8LHNP6JWF6Fvy/Wireframing-Demo?node-id=2-6&t=UYk2cSkDwrrDRbkO-0

