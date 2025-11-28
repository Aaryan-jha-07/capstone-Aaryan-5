# capstone-Aaryan-5
#Learn it - Curate Your Knowledge
Learn it is a modern, responsive landing page designed for an educational platform that focuses on curated learning paths. This project demonstrates high-end front-end design techniques using a "Dark Mode" aesthetic, advanced CSS animations, and a glassmorphism UI.

# Features
Modern Aesthetic: A sleek dark theme using a curated color palette (--bg-dark, --accent-lime, --accent-purple).

Responsive Design: Fully fluid layout using CSS Grid and Flexbox, with breakpoints for tablets (1024px) and mobile devices (760px).

Advanced CSS Animations:

Morphing SVG-style blobs using border-radius manipulation.

Smooth hover transitions for cards and navigation links.

Parallax-style image scaling on hover.

Glassmorphism: Frosted glass effects on the sticky navigation header.

Typography: Integration of Google Fonts (Playfair Display for headings and Space Grotesk for body text) for a sophisticated editorial look.

Minimalist Form: A clean, underline-style input form for user registration.

#Tech Stack
HTML5: Semantic markup structure.

CSS3:

CSS Variables (Custom Properties)

CSS Grid & Flexbox

Keyframe Animations

Media Queries

No Frameworks: Built entirely with vanilla HTML and CSS (no Bootstrap or Tailwind required).

#Project Structure
To run this project correctly, your directory should look like this (you will need to provide the image assets):

Plaintext
/project-folder
│
├── trial.html          # Main HTML file containing structure and styles
├── webdev.jpg          # Image for Web Development card
├── graphic.jpg         # Image for Graphic Design card
├── business.jpg        # Image for Business Analytics card
├── facebook.jpg        # Icon for Facebook
└── instagram.jpeg      # Icon for Instagram
Note: The CSS is currently embedded within the <head> of the trial.html file. For larger projects, it is recommended to move the content between the <style> tags into a separate style.css file.
#How to Run
Download the trial.html file.

Add Images: Place images named webdev.jpg, graphic.jpg, business.jpg, facebook.jpg, and instagram.jpeg in the same folder to ensure the visual elements load correctly.

Open: Double-click trial.html to open it in any modern web browser (Chrome, Firefox, Safari, Edge).
# Color Palette
The design relies on a specific set of CSS variables defined in the :root:

Background: #0f0f11 (Deep Dark)

Card Background: #1a1a1e

Text: #e0e0e0 (Off-white)

Accents:

Lime: #ccff00

Purple: #b983ff

# Sections
Hero: Features a headline with text-stroke effects and a pure CSS morphing blob animation.

Curated Paths (Courses): A 3-column grid displaying course cards with zoom-on-hover effects.

Reviews: A horizontal scrolling section featuring testimonials.

Contact: A minimal form for users to select their discipline (Web Architecture, Visual Synthesis, Data Insight).
