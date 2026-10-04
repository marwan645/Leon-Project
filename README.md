## Leon - Creative Agency Landing Page

- A responsive, single-page website for a creative agency, built with HTML, CSS and a little vanilla JavaScript.
 
## Screenshots:
- <img width="1919" height="1199" alt="home" src="https://github.com/user-attachments/assets/ffd08292-7ff1-4052-ad05-343d5cb06586" />
- <img width="1920" height="497" alt="home1" src="https://github.com/user-attachments/assets/ea8ae87f-7595-4132-865f-ac166e6b9baf" />
- <img width="1919" height="858" alt="services" src="https://github.com/user-attachments/assets/8f095837-2280-46ca-a2b7-6ec5764b0e0d" />
- <img width="1916" height="1094" alt="portfolio" src="https://github.com/user-attachments/assets/ada30797-93d6-4785-b1fa-07ca0bde7c79" />
- <img width="1919" height="808" alt="about" src="https://github.com/user-attachments/assets/ca83bb83-b443-47d1-b210-4d1a9f338735" />
-<img width="1919" height="543" alt="contact" src="https://github.com/user-attachments/assets/4753d88f-9949-4ae7-b976-650467911a14" />

## About this project
- This is a learning project. I built it by converting a free PSD design into code while After finishing it with Elzero Web School (https://www.youtube.com/watch?v=MBq8ZFEIIaQ&list=PLDoPjvoNmBAzHSjcR-HnW9tnxyuye8KbF), I reviewed my own code, fixed the mistakes I found, and refactored it to be cleaner and more accessible.
- PSD design credit: https://www.graphberry.com/item/leon-psd-agency-template
- Icons: [Font Awesome](https://fontawesome.com)
- Fonts: [Google Fonts](https://fonts.google.com)

## Sections
- Landing hero
- Features
- Services
- Portfolio
- About
- Contact and footer

## Built with
- HTML5 - semantic structure (header, main, section, article, footer)
- CSS3 - Grid, Flexbox, CSS variables, clamp() for fluid type
- Font Awesome for icons, Google Fonts (Work Sans), normalize.css

## What I improved after the first version
- Fixed invalid HTML (unclosed and extra </div> tags) and a broken mailto link
- Replaced position hacks and negative margins with Grid and Flexbox
- Made the mobile menu work with tap and keyboard (aria-expanded, Escape to close)
- Added alt text, a form label, and visible keyboard focus
- Respected prefers-reduced-motion
- Reduced loaded font weights and lazy-loaded below-the-fold images
- Reviewed and refactored with help from an AI assistant (Claude)

## Project structure
-leon/
 - index.html
 - css/
            core.css, normalize.css, all.min.css

## What I learned
- Turning a PSD design into a real layout
- Building responsive layouts without fixed pixel offsets
- Writing accessible navigation and semantic HTML
- Debugging and refactoring my own code

## Next steps
- Replace the placeholder portfolio cards with real projects
- Add a working contact form
- Add dark mode
