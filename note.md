Create a complete multi-page personal portfolio website using only HTML and CSS.

Project structure must be exactly:

/portfolio
│
├── index.html
├── about.html
├── projects.html
├── contact.html
│
├── /css
│   └── styles.css
│
├── /images
│
└── /assets


GENERAL REQUIREMENTS:
- Use clean, semantic HTML5 (header, nav, section, footer)
- Use a single shared CSS file: css/styles.css
- Fully responsive design (mobile-first)
- Use Flexbox and/or CSS Grid
- Modern, minimal, professional design
- No JavaScript
- Consistent spacing, typography, and color scheme
- Sticky navigation bar
- Smooth hover effects for buttons and links

-------------------------------------

GLOBAL DESIGN STYLE:
- Font: Use a clean Google Font (e.g., Poppins or Inter)
- Color palette:
  - Primary: #4CAF50 (can be adjusted)
  - Dark: #222
  - Light: #f9f9f9
  - Accent: #555
- Container max width: 1100px
- Use reusable classes: .container, .section, .btn, .card, .grid

-------------------------------------

NAVIGATION (on ALL pages):
- Logo/Name: "Hana"
- Menu links:
  - Home (index.html)
  - About (about.html)
  - Projects (projects.html)
  - Contact (contact.html)
- Highlight active page
- Mobile responsive menu (simple stacked layout, no JS)

-------------------------------------

INDEX.HTML (HOME PAGE):

Sections:
1. Hero Section:
   - Name: "Hana"
   - Title: "Web Developer"
   - Tagline: "I build clean and responsive websites"
   - Buttons:
     - "View Projects" → projects.html
     - "Contact Me" → contact.html

2. Short About Preview:
   - Placeholder text:
     "I am a web developer based in Addis Ababa specializing in modern web design."
   - Link to About page

3. Featured Projects (3 items):
   Each project includes:
   - Image (use placeholder: images/project1.jpg, etc.)
   - Title
   - Short description
   - Link to projects.html

4. Footer:
   - "© 2026 Hana. All rights reserved."
   - Social links placeholders:
     - GitHub: #
     - LinkedIn: #
     - Email: mailto:your@email.com

-------------------------------------

ABOUT.HTML:

Sections:
1. About Me:
   - Placeholder text:
     "Hello, I'm Hana, a passionate web developer from Addis Ababa..."
   - Add a profile image (images/profile.jpg)

2. Skills:
   - Categories:
     - Frontend: HTML, CSS, JavaScript
     - Tools: Git, Figma
     - Other: Responsive Design
   - Display as cards or tags

3. Experience (optional section):
   - Placeholder entries:
     - "Frontend Developer - Company Name (Year - Year)"
     - "Freelance Web Developer"

-------------------------------------

PROJECTS.HTML:

- Page title: "My Projects"

- Display at least 6 project cards in a grid layout

Each project card includes:
- Image (images/projectX.jpg)
- Project Title: "Project Name"
- Description: "Short description of the project..."
- Tech used: "HTML, CSS"
- Links:
  - Live Demo: #
  - GitHub Repo: #

-------------------------------------

CONTACT.HTML:

Sections:
1. Contact Info:
   - Email: your@email.com
   - Location: Addis Ababa, Ethiopia

2. Contact Form (HTML only, no backend):
   - Name (input)
   - Email (input)
   - Message (textarea)
   - Submit button

3. Social Links:
   - GitHub: #
   - LinkedIn: #

-------------------------------------

CSS (styles.css):

Include:
- CSS Reset or normalize basics
- Typography styles
- Layout system (.container, .grid)
- Buttons (.btn with hover effects)
- Cards (.card with shadow and padding)
- Responsive media queries:
  - 768px (tablet)
  - 1024px (desktop)

-------------------------------------

IMAGES:
- Use placeholders:
  - images/profile.jpg
  - images/project1.jpg
  - images/project2.jpg
  - etc.

-------------------------------------

IMPORTANT:
- Ensure all pages are visually consistent
- Use clean indentation and readable code
- Add comments in CSS for sections
- Make the design look modern and polished

-------------------------------------

OUTPUT:
- Generate ALL files with full code
- Clearly separate each file
- Include proper file paths for CSS and images