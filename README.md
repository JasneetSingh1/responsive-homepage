## Table of Contents

1. [Description](#description)  
1. [Features](#features)  
1. [Technologies Used](#technologies-used)  
1. [Project Challenges](#project-challenges)  
1. [Thoughts and Observations](#thoughts-and-observations)  
1. [Future Enhancements](#future-enhancements)  


## Description

This project is a responsive homepage built as the final project for the Advanced HTML and CSS course. The goal was to practice advanced layout and design techniques by replicating a multi-screen design brief (mobile, tablet, and desktop). It serves as a mock portfolio homepage, where I could demonstrate layout proficiency, semantic HTML usage, and responsive design using mobile-first principles. The project showcases not just technical skills but also design thinking—such as visual hierarchy, layout consistency, and user-friendly responsiveness.

## Features

- Responsive layout with tailored designs for mobile, tablet, and desktop views.
- A unique angled hero background created with pure CSS using `::after` and border tricks.
- An "About" section where the image overlaps the text content and allows for natural text wrapping.
- Social media icon links (GitHub, LinkedIn, Twitter) using Devicon.
- Semantic HTML5 structure with accessibility in mind.
- Fluid layout using Flexbox and media queries for breakpoints.

## Technologies Used

- HTML5  
- CSS3 (Mobile-first approach)  
- Flexbox  
- Media Queries  
- Devicon.dev for social icons  
- Google Fonts (Playfair Display, Roboto)  

## Project Challenges

- Positioning overlapping elements with float and relative positioning while maintaining responsiveness was tricky, especially getting the image and text to flow naturally at larger breakpoints.
- Getting the angled background section to scale well across screen sizes took some experimentation with viewport units and `border`-based triangles.
- Ensuring the design maintained visual balance and alignment through all breakpoints was a recurring task during development.
- Mobile-first development required rethinking layout defaults to progressively enhance styles for wider screens.

## Thoughts and Observations

This project really reinforced the importance of planning layout structure before diving into styling. Starting from a mobile-first mindset helped keep things clean and manageable. It also gave me a chance to creatively use CSS techniques like floats, `z-index`, and pseudo-elements to recreate designs that would normally require graphic assets. Having a real-world-like mockup made the development process more grounded and helped simulate client or job-ready development.

## Future Enhancements

- Add smooth scroll navigation and a sticky header for better UX.
- Introduce animations or transitions to section reveals for more interactivity.
- Optimize for performance and accessibility (e.g. color contrast improvements, `aria` attributes).
- Include a working contact form and expandable projects section.
- Add dark mode toggle support for better personalization.
