# Brother Green | Urban Dance Management

## Overview
Brother Green is a specialized urban dance management platform designed for the dance community. It provides a sleek, modern web interface for managing dance-related activities, artists, and events. The application prioritizes a high-energy, urban aesthetic using dark themes and neon green accents.

## Project Outline
### Current State & Architecture
- Foundation: Vanilla HTML5, CSS3, and JavaScript.
- Styling: Leverages Tailwind CSS via CDN for rapid, responsive UI development.
- Design Language:
    - Theme: Dark mode by default (bg-[#121414]).
    - Accents: Neon Green/Yellow (#b1f800) for "glow" effects and calls to action.
    - Textures: Subtle asphalt texture overlays to reinforce the urban theme.
    - Typography: Uses 'Sora' and 'Hanken Grotesk' for a modern, clean look.
- Deployment: Configured for automatic deployment to GitHub Pages using GitHub Actions.

### Key Features
- Responsive Layout: Optimized for both desktop and mobile viewing.
- Custom UI Components: Hero sections with gradients, custom-styled cards, and interactive elements.
- Workflow: Automated CI/CD pipeline via .github/workflows/deploy.yml.

---

## Current Plan: GitHub Integration & Automatic Deployment

### Objective
Establish a solid connection with the GitHub repository and ensure the automated deployment pipeline is active and functional.

### Steps
1. Repository Synchronization:
    - Verified remote: https://github.com/steper2/brothergreen.git.
    - Stage all untracked assets (assets/bg-neon.png).
    - Create blueprint.md as the project's single source of truth.
2. Commit & Push:
    - Perform a comprehensive commit of the current workspace state.
    - Push to the main branch to trigger the GitHub Actions workflow.
3. Deployment Verification:
    - Monitor the GitHub Actions tab (manual check suggested to user) to ensure the Deploy to GitHub Pages workflow completes successfully.
