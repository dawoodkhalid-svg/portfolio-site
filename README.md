# Portfolio Website - Dawood Khalid

## Project Overview
A responsive portfolio website showcasing my work as a Networking and IT Security student at Ontario Tech University. The site includes information about my background, projects, skills, and contact information.

## Repository Link 
https://github.com/dawoodkhalid-svg/portfolio-site/tree/main

## Website Link 
https://dawoodkhalid-svg.github.io/portfolio-site/

## Viewport Sizes and Responsive Design

### Desktop (1025px and above)
- Target devices: Desktop computers, laptops
- Wrapper width: 100%
- Navigation: Horizontal inline-block menu with rounded buttons
- Box layout: Floated left with fixed dimensions (200px × 200px)
- Typography: Larger font sizes (h2: 30px, h3: 32px, p: 24px)
- Video dimensions: Fixed at 640px × 500px

### Tablet (601px - 1024px)
- Target devices: iPad, Android tablets, smaller laptops
- Navigation: Horizontal inline-block menu, slightly smaller padding
- Box layout: 45% width, floated left for two-column layout
- Profile image: Fixed at 400px width, centered
- Video: 100% width with auto height
- Typography: Medium sizes (h2: 30px, h3: 24px)

### Mobile (600px and below)
- Target devices: Smartphones
- Navigation: Vertical stacked menu, full-width buttons
- Box layout: 90% width, stacked vertically
- Profile image: 100% width with max-width of 300px
- Video: 100% width with auto height
- Typography: Smaller sizes (h1: 25px, h2: 25px, h3: 20px)
- Form inputs: Full-width for better mobile usability

## Color Scheme
- Dark Blue: `#1A1A2E` - Main text and footer
- Navy: `#16213E` - Header background
- Deep Blue: `#0F3460` - Navigation buttons and box gradients
- Accent Red: `#E94560` - Hover effects
- Light Gray: `#F1F1F1` - Background and text on dark sections

## Gradients Used
- Body Background: `linear-gradient(bottom, #F1F1F1 0%, #E8E8E8 100%)`
- Header Background: `linear-gradient(45deg, #16213E 0%, #0F3460 100%)`
- Box Elements: `radial-gradient(center, ellipse cover, #F1F1F1 0%, #0F3460 100%)`

## Testing and Validation
- Passed with 0 errors


## Responsive Adjustments & Solutions
- Navigation menu: `display: inline-block` for desktop, `display: block` for mobile
- Boxes: Fixed 200px for desktop, 45% for tablet, 90% stacked for mobile
- Profile image: Floated right on desktop, centered and scaled on tablet/mobile
- Video: Fixed on desktop, responsive width and auto height on tablet/mobile
- Form inputs: Set to 100% width on all viewports
- Typography: Scaled for readability across devices
- Footer: Cleared floats and positioned relative

## File Structure
portfolio-site/
│
├── index.html
├── about.html
├── projects.html
├── contact.html
├── README.md
│
├── css/
│ ├── style.css # Desktop styles
│ ├── tablet.css # Tablet styles
│ └── mobile.css # Mobile styles
│
├── images/
│ ├── profilephoto.png
│ └── previewimage.jpg
│
└── video/
└── realvidfinal.mp4

## Technologies Used
- HTML5: semantic markup, video, forms
- CSS3: media queries, gradients, transitions
- Responsive design: mobile-first approach

## Accessibility Features
- Semantic HTML5 elements
- Alt text for images
- Proper form labels
- Sufficient color contrast
- Touch-friendly button sizes on mobile

## Contact
**Dawood Khalid**  
Email: dawood.khalid@ontariotechu.net  
Program: Networking and IT Security, Ontario Tech University

© 2025 Dawood. All rights reserved.


