# Portfolio Website - Jordi Rodríguez

A modern, responsive portfolio website showcasing web development projects and skills. Built with Astro for optimal performance.

## Project Analysis

### User Persona

**Name:** Sarah Martinez  
**Age:** 28  
**Occupation:** Tech Recruiter / HR Manager at a Software Company  
**Location:** Madrid, Spain  
**Tech Knowledge:** Basic understanding of web technologies  

**Goals:**
- Quickly assess candidate's technical skills and experience
- View portfolio projects and code quality
- Contact the developer easily
- Understand the developer's expertise level

**Pain Points:**
- Limited time to review portfolios
- Needs clear, concise information
- Wants to see real project examples
- Prefers mobile-friendly websites

**Behaviors:**
- Reviews portfolios on mobile during commute
- Skims through sections quickly
- Looks for GitHub links and live demos
- Values professional presentation

**Needs:**
- Easy navigation and clear sections
- Visual project showcases
- Contact information readily available
- Professional yet modern design

---

### Information Architecture

The website follows a linear, single-page architecture optimized for storytelling and user engagement. The information is distributed across five main sections, each serving a specific purpose in the user journey.

**Hero Section:** The landing area immediately introduces the developer's identity with a bold diagonal split design. The left side features the personal introduction with name, role, and a brief description, while the right side displays interactive elements like tech stack badges, floating code blocks, and a profile card. This creates visual interest while establishing credibility.

**About Section:** Positioned after the hero, this section provides context about the developer's background, experience, and passion for development. It includes three key cards (Story, Focus, Passion) that humanize the profile, followed by statistics that quantify achievements (50+ projects, 1+ years experience, etc.).

**Skills Section:** The technical expertise is organized into categories (Frontend, Backend, Tools) with visual progress bars indicating proficiency levels. This allows recruiters and clients to quickly assess technical capabilities without overwhelming detail.

**Projects Section:** The portfolio's core content features four featured projects inspired by major platforms (Netflix, YouTube, Spotify, Airbnb). Each project card includes category, title, description, tech stack tags, and links to demo/repository. The featured project (Netflix Clone) spans two columns for emphasis.

**Contact Section:** The final section combines contact information cards (Email, Phone, Location, LinkedIn) with a functional contact form and social media links. This dual approach ensures accessibility regardless of user preference.

The architecture prioritizes progressive disclosure—essential information is immediately visible, while detailed content is organized hierarchically. Navigation is facilitated through anchor links in the navigation bar and call-to-action buttons, creating a smooth scrolling experience.

---

### Visual Design

The visual design of this portfolio prioritizes modernity, professionalism, and visual hierarchy through strategic use of color, typography, and layout principles.

**Color Palette:** The design employs a sophisticated gradient system combining deep blues and purples for the hero section (#1a1a2e, #16213e, #0f3460) with light grays for contrast (#f8fafc, #e2e8f0). Accent colors include vibrant gradients (#ff6b6b to #4ecdc4) used strategically for CTAs, highlights, and text gradients. This creates visual interest while maintaining readability and professional appearance.

**Typography:** Large, bold headings (2.5rem-3.5rem) establish clear hierarchy, with the hero title featuring an animated gradient text effect that draws attention. Body text uses comfortable line heights (1.5-1.6) for optimal readability. Monospace fonts are reserved for code blocks, maintaining authenticity and developer aesthetic.

**Layout & Composition:** The hero section features an innovative diagonal split design using CSS clip-path, creating a dynamic visual that breaks traditional grid layouts. This 60/40 split allows the dark left section to contain the main content while the light right section showcases interactive elements. Cards throughout the site use glassmorphism effects (backdrop-filter blur, semi-transparent backgrounds) adding depth and modern appeal.

**Interactive Elements:** Hover states are consistently applied with subtle transforms (translateY, scale), shadow enhancements, and color transitions. Floating animations on tech badges, code blocks, and background shapes create a sense of movement without being distracting. The design maintains accessibility with proper contrast ratios and focus states.

**Responsive Strategy:** The design adapts through three breakpoints (1024px, 768px, 480px), transitioning from the diagonal split to vertical stacking on mobile devices. Complex elements like floating code blocks are hidden on smaller screens, prioritizing content over decoration. Touch-friendly button sizes and spacing ensure usability across all devices.

---

## Design Resources

---

## Technologies Used

- **Framework:** Astro
- **Styling:** CSS3 with custom animations
- **Deployment:** Vercel

## Project Structure

```
src/
├── components/
│   ├── Hero.astro
│   ├── About.astro
│   ├── Skills.astro
│   ├── Projects.astro
│   └── Contact.astro
├── layouts/
│   └── Layout.astro
├── pages/
│   └── index.astro
└── styles/
    └── global.css
```

## Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

---

## License

This project is private and proprietary.

## Figma
https://www.figma.com/design/d9x4TZuILV9WTAJQBfKw8T/Untitled?node-id=0-1&t=x8EVJx9S9PZcBzu3-1

## Link web
https://portfoli-virid.vercel.app/

