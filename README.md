## Design and Development
This repository contains my submission for the Developing with Tailwind lab, where I took a Figma design from Frontend Mentor and implemented it using Tailwind. This project simulates a real-world task where I received a design handoff and was expected to create a responsive, pixel-perfect webpage. I applied my knowledge of Tailwind's grid system, components, and utility classes while utilizing version control through Git.

## 📋 Project Overview
Semantic HTML Structure
Used landmark HTML elements (< header >, < nav >, < main >, < section >, < article >, < footer >) instead of generic < div > containers to create meaningful document structure.

Implemented a logical heading hierarchy, starting with < h1 > in the hero section, < h2 > for major sections, and < h3 > for individual cards and service items.

Structure follows accessibility standards and mirrors the layout organization from the Figma design files.

## 🎨 Layout & Responsive Design
Accuracy to Design
Matched the Figma design precisely — alignment, spacing, font sizes, and element dimensions follow the provided style guide.

Colors, typography, and component sizing all reflect the original design specifications.

Flexbox Implementation
Header & Navigation: Built with Flexbox to align the logo and navigation links. On desktop, items sit inline with space between; on smaller screens (under 600px), the layout gracefully stacks into a centered column.

CSS Grid Implementation
Services Section: Uses CSS Grid with adaptive column layouts:

Desktop (1025px+): 3-column layout (repeat(3, 1fr))
Tablet (601px–1024px): 2-column layout for better readability
Mobile (≤600px): Single-column layout for easy scrolling on phones

CSS Styling
CSS is well-organized and matches the style guide exactly — colors, fonts, and sizes align with the Figma specifications.

Tailwind Utility Classes
Tailwind's utility-first approach was used throughout for styling — colors, fonts, spacing, and sizes align with the Figma specifications.
Responsive breakpoints (sm:, md:, lg:) keep the styling consistent across all screen sizes.
Reusable utility patterns made it easy to apply consistent styling to similar sections
Custom properties and media queries keep the styling consistent across all breakpoints.

## ♿ Accessibility Features
Keyboard Navigation & Interactive Elements
Hover and focus states are implemented as specified in the design, with smooth transitions and responsive feedback.

Keyboard focus management ensures all interactive elements are reachable and clearly indicated.

Color Contrast
All text, buttons, and background combinations have been checked against WCAG 2.1 AA standards using contrast checking tools to ensure readability.

Decorative Elements
Service icons are purely decorative and include alt="" to prevent screen readers from announcing them unnecessarily.

## 🛠️ Technologies Used
HTML — Semantic markup and accessibility

CSS — Flexbox, Grid, media queries, and custom properties

Figma — Design interpretation and style guide adherence

Frontend Mentor — Challenge specifications and assets

Tailwind CSS - A utility first CSS library

Git	- Version control with frequent, descriptive commits

## ✅ Assessment Criteria Met
☑ Design Selection — Selected a valid Frontend Mentor challenge and documented it in the README
☑ HTML Markup — Clean, semantic HTML used throughout with appropriate tags and structure
☑ Tailwind Utilization — Effective use of Tailwind's grid system, components, and utilities for responsive design
☑ Custom CSS — Minimal, well-organized, and complements Tailwind styles effectively
☑ Responsiveness — Fully responsive, adjusting well across all screen sizes
☑ Version Control — Frequent, clear, and descriptive commits following Git best practices
☑ Project Documentation — Thorough, well-organized README providing a clear overview
☑ Reflection — Detailed and insightful reflection on challenges, solutions, and improvements

## REFLECTION
One of the main challenges I faced was ensuring the Tailwind implementation matched the Figma design precisely across all breakpoints. Translating design specs into utility classes required careful attention to spacing, font sizes, and responsive behavior.

I approached these challenges by systematically reviewing the Figma style guide and mapping each design token to its corresponding Tailwind utility. For responsive issues, I used Tailwind's breakpoint prefixes (sm:, md:, lg:) and tested the layout at each screen size, adjusting column counts and spacing as needed. Version control helped me track changes and revert when a particular approach didn't work.

If I had more time, I would explore Tailwind's component extraction using @apply to reduce repetitive utility classes and improve maintainability. I would also add more comprehensive accessibility testing and implement dark mode support using Tailwind's dark: variant. Finally, I would refine animations and transitions for a more polished user experience.
