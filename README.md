Portfolio Website Design Specification
Professional Software Engineering Portfolio Website
Document purpose	Software engineering design specification for a personal virtual CV and portfolio website
Deployment platform	Netlify
Technology stack	HTML5, CSS3 and JavaScript

1. Project Overview
The Professional Software Engineering Portfolio Website is a single-page personal portfolio that presents academic achievements, technical skills, employment experience, certifications, selected projects, and professional contact information. It complements the author's curriculum vitae by providing an accessible, interactive overview for recruiters, lecturers and prospective employers.
The website is implemented as a static front-end application using HTML5, CSS3 and JavaScript. It applies responsive design, semantic HTML, reusable interface components and accessibility-aware navigation. The completed website is deployed on Netlify through a public URL.


2. Project Purpose
The purpose of the website is to:
•	Establish a professional online presence that supports internship and graduate software engineering applications.
•	Showcase selected software engineering projects, technical competencies and academic development.
•	Demonstrate practical front-end development capability through a responsive, maintainable website.
•	Provide direct access to the downloadable CV, GitHub profile, LinkedIn profile and professional contact details.
•	Provide a central, easily updated location for professional information and future portfolio work.


3. Target Audience
The website is intended for the following audiences:
•	Software engineering and IT recruiters
•	Potential employers and internship coordinators
•	University lecturers and assessors
•	Professional networking contacts and North-West University alumni
•	Fellow students and project collaborators


4. Functional Requirements
The portfolio website shall provide the following functions.
Home
•	Display a concise professional introduction, career focus and call-to-action buttons.
•	Allow users to navigate to the projects section and download the CV.
About
•	Present a professional biography, career objective and high-level profile information.
Skills
•	Present programming languages, web technologies, database technologies and development tools in grouped skill cards.
Education
•	Present the current Bachelor of Information Technology (Extended Programme) and relevant academic focus areas.
Experience
•	Present employment experience, including Student Assistant and General Assistant responsibilities, in clear, scannable cards.
Projects
•	Present the Lerato Orphanage Management System as a featured project with screenshots, technologies, key features, contribution, challenges, lessons learned and a repository link.
Certifications
•	Present completed technical and professional-development certificates.
Contact
•	Provide direct email, GitHub and LinkedIn links and a downloadable CV.
Navigation
•	Provide sticky desktop navigation and a JavaScript-controlled mobile menu that supports anchor navigation to every major section.


5. Non-Functional Requirements
The portfolio website shall meet the following quality requirements.
Performance
•	Load efficiently by using a lightweight static-site architecture and optimised local resources.
•	Use lazy loading for non-critical project screenshots where appropriate.
Responsiveness
•	Display correctly on desktop, laptop, tablet and smartphone screen sizes.
•	Adapt navigation, card layouts, images and call-to-action elements at defined responsive breakpoints.
Browser Compatibility
•	Function correctly in current versions of Google Chrome, Microsoft Edge, Mozilla Firefox and Safari.
•	Use standards-based HTML, CSS and JavaScript features supported by current major browsers.
Usability
•	Provide clear navigation, readable text, consistent visual hierarchy and direct access to key professional links.
Accessibility
•	Use semantic HTML landmarks, descriptive alternative text, sufficient contrast and accessible navigation controls.
•	Maintain accurate aria-label, aria-controls and aria-expanded attributes for the mobile navigation control.
Maintainability
•	Separate HTML, CSS and JavaScript into dedicated files.
•	Use meaningful names, CSS custom properties, reusable card and tag components, consistent formatting and comments.
Reliability
•	Ensure that navigation links, downloads, external profile links and repository links function correctly.
•	Prevent broken asset paths and ensure the CV remains available from the documents directory.
Security and Privacy
•	Avoid publishing unnecessary personal information.
•	Use rel="noopener noreferrer" for external links opened in a new tab.
•	Validate and sanitise any future user input before processing it.
Consistency
•	Apply a consistent navy, slate-blue, white and light-grey visual system, alongside reusable typography, spacing, card and tag treatments.


6. Website Structure
The website is implemented as a single-page portfolio with the following sections:
•	Home
•	About
•	Skills
•	Education
•	Experience
•	Projects
•	Certifications
•	Contact
•	Download CV
Anchor-based navigation and smooth scrolling provide a direct path between sections while preserving a simple, linear reading experience.


7. Navigation Structure
Home
|- About
|- Skills
|- Education
|- Experience
|- Projects
|- Certifications
|- Contact
`- Download CV
The main navigation remains visible on desktop screens. At tablet and mobile breakpoints, it is replaced by an accessible hamburger control that opens and closes the menu using JavaScript.

8. Folder Structure
portfolio-website/
|- index.html
|- css/
|  `- style.css
|- js/
|  `- script.js
|- images/
|  |- profile.jpg
|  |- lerato-login.png
|  `- lerato-dashboard.png
|- documents/
|  `- CV.pdf
`- README.md

This structure separates content, presentation, behaviour, images and downloadable documents to support maintainability and straightforward deployment on Netlify.


9. Colour Palette
The portfolio uses a restrained professional palette that matches the visual identity established across the CV, LinkedIn profile and GitHub profile.
Element	Colour	Use
Primary	Navy Blue (#19376D)	Navigation, headings and primary interface elements
Accent	Slate Blue (#4B6CB7)	Secondary emphasis, links and visual accents
Background	White (#FFFFFF)	Primary content surface
Secondary Background	Light Grey (#F5F7FA)	Alternating sections and subtle visual separation
Text	Dark Grey (#2D3748)	Body copy and readable supporting information


10. Typography
The website uses a clear typography hierarchy to support readability and scanning across devices.
Role	    Font	            Purpose
Headings	Poppins	            Professional headings, section titles and card headings
Body text	Inter	            Readable paragraphs, descriptions and navigation text
Fallback	System sans-serif	Reliable display if external web fonts are unavailable


11. Design Principles
The following principles guide design and implementation decisions:
•	Professional and restrained visual presentation rather than decorative or distracting effects.
•	Clear visual hierarchy that prioritises name, career focus, skills, project evidence and contact details.
•	Consistent branding across the portfolio, CV, LinkedIn profile and GitHub profile.
•	Simple, discoverable navigation and a user-centred reading flow.
•	Responsive, accessible and maintainable implementation.
•	Reusable components for cards, headings, tags, buttons and content containers.


12. User Interface Components
Navigation Bar
•	Personal initials/logo
•	Section links
•	Download CV action
•	Mobile hamburger control
Hero Section
•	Professional profile image
•	Name and career title
•	Availability statement
•	Brief professional introduction
•	Project and CV call-to-action buttons
Skills Section
•	Category-based skill cards for programming languages, web development, databases and development tools
Education and Experience
•	Reusable information cards, date badges and relevant tags
Projects Section
•	Featured project overview
•	Application screenshots
•	Project details
•	Technology tags
•	Key features
•	Contribution, challenges and learning outcomes
•	Repository link
Certifications Section
•	Certification cards with issuing organisation, description and relevant tags
Contact and Footer
•	Email, GitHub, LinkedIn and CV links
•	Quick navigation links
•	Professional footer information


13. Planned Features
Version 1 Scope
•	Responsive single-page portfolio layout
•	Sticky navigation and accessible mobile menu
•	Smooth scrolling between sections
•	Professional hero, about, skills, education, experience, projects, certifications and contact sections
•	Featured project case study with screenshots
•	Downloadable CV
•	External GitHub and LinkedIn links
•	Subtle hover transitions and responsive card layouts
Potential Future Enhancements
•	Additional project case studies
•	Dark mode
•	Dedicated project pages
•	A short technical blog
•	Expanded certification gallery
•	Further accessibility and performance refinements


14. Technology Stack
Front-End
•	HTML5 for semantic structure
•	CSS3 for visual styling, Flexbox, Grid, custom properties and responsive breakpoints
•	Vanilla JavaScript for mobile navigation behaviour and accessibility state management
Development Tools
•	Visual Studio Code
•	Git
•	GitHub
•	W3C HTML Validator
•	W3C CSS Validator
Deployment
•	Netlify for static-site deployment and public portfolio hosting.


15. Conclusion
The Professional Software Engineering Portfolio Website provides a coherent online representation of the author's skills, education, experience, certifications and project work. It combines professional content with standards-based front-end development practices, including responsive design, semantic HTML, reusable CSS components, accessible navigation and clear repository documentation.
The website is deployed through Netlify and can be maintained as a living portfolio. Future projects, certifications and experience can be added without requiring a redesign because the site uses a consistent, modular structure. This makes the portfolio appropriate for academic assessment as well as internship, graduate and entry-level software engineering applications.
