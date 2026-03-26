# Team VIII Profile

A modern, responsive team portfolio website showcasing Team VIII's members and their technical expertise.

## Technical Stack

### Frontend Technologies
- **HTML5** - Semantic markup and document structure
- **CSS3** - Styling and layout (via Tailwind CSS)
- **JavaScript (ES6+)** - Interactive functionality and mobile menu handling

### CSS Framework
- **Tailwind CSS v4.2.2** - Utility-first CSS framework for rapid UI development
  - Used for responsive design, color schemes, and component styling
  - Provides dark theme with gray-950 background and modern UI components

### Development Tools
- **Node.js** - JavaScript runtime and package management
- **npm** - Package manager for dependencies
- **@tailwindcss/cli v4.2.2** - Tailwind CSS command-line interface
- **Git** - Version control system

### Project Structure
```
profile8/
├── index.html          # Main HTML file with complete website structure
├── package.json        # Node.js dependencies and project metadata
├── package-lock.json   # Locked dependency versions
├── .gitignore          # Git ignore file (excludes node_modules)
├── src/
│   ├── input.css       # Tailwind CSS import directive
│   └── output.css      # Compiled Tailwind CSS styles
└── assets/
    └── img/            # Team member profile images
        ├── photo_5791825371199114882_y.jpg
        ├── wal.jpg
        ├── jo.jpg
        └── vee.jpg
```

## Features

### Responsive Design
- Mobile-first approach with hamburger menu for small screens
- Tablet and desktop layouts with grid-based team member cards
- Smooth transitions and hover effects throughout

### Interactive Elements
- Animated hamburger menu with smooth transitions
- Hover states on navigation links and team cards
- Online status indicators for team members

### Team Section
- Four team member cards with:
  - Profile images with colored borders
  - Names, roles, and descriptions
  - Technology skill tags
  - Online status indicators

### Color Scheme
- Dark theme with gray-950 background
- Accent colors: indigo, orange, cyan, and emerald for team members
- Consistent gray scale for borders and text hierarchy

## Development Workflow

1. **Styling**: Tailwind CSS is imported via `src/input.css` and compiled to `src/output.css`
2. **Images**: Team member photos stored in `assets/img/` directory
3. **Dependencies**: Managed through npm with Tailwind CSS as the primary dependency

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Build Tailwind CSS:
   ```bash
   npx tailwindcss -i ./src/input.css -o ./src/output.css
   ```

3. Open `index.html` in a web browser to view the website

## Team Members

- **Msughter Apera** - Full-Stack Engineer (Python, JavaScript, FastAPI, PostgreSQL)
- **Patrick Walshak** - Full-Stack Engineer (JavaScript, Python, FastAPI, TailwindCSS)
- **Joe Godwin** - Full-Stack Engineer (Python, JavaScript, FastAPI, MySQL)
- **Vincent Husseini** - Front-end Engineer (TypeScript, JavaScript, TailwindCSS, HTML/CSS)

## License

© 2026 Team VIII. All rights reserved.
