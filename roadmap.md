# Strike Force MVP - Development Roadmap

This document outlines the plan for building the Strike Force MVP website, using the existing `landing-page` as inspiration for the technical setup. The content will be based on the final version `copy-target-v5-full.md`.

## Phase 1: Project Setup & Foundation
- [x] **Task 1.1:** Create the project directory structure: `assets/css`, `assets/js`, `assets/images`.
- [x] **Task 1.2:** Create the main HTML files: `index.html`, `process.html`, `team.html`, `contact.html`.
- [x] **Task 1.3:** Create the main stylesheet `assets/css/style.css` which will import other CSS files.
- [x] **Task 1.4:** Create CSS config files for colors and fonts (`assets/css/config/colors.css`, `assets/css/config/fonts.css`).
    - **Colors**: Define primary colors: black (`#0A0A0A`), off-white (`#FFFFFF`), and action-red (`#FF3333`).
    - **Fonts**: Import 'Inter' for body text and 'Fira Code' for code blocks from Google Fonts.
- [x] **Task 1.5:** Add HTML boilerplate to all pages, including Tailwind CSS CDN and custom stylesheet link.

## Phase 2: Common Components
- [x] **Task 2.1:** Build the site `Header` (Navigation) component.
- [x] **Task 2.2:** Build the site `Footer` component.
- [x] **Task 2.3:** Copy the Header and Footer into all HTML files.
- [x] **Task 2.4:** Style common elements (buttons, cards, terminal) according to the brand aesthetic.

## Phase 3: Page Content & Layout
- [x] **Task 3.1:** Build the **Homepage** (`index.html`)
    - [x] Hero section with Terminal
    - [x] Statistics
    - [x] "Votre méthode" section (Error cards)
    - [x] "Notre Équipage" section
    - [x] Pricing section (Proof Pack & PMF Pack)
    - [x] "Proof Pack" 6-Week Timeline
    - [x] Equity Partnership section
    - [x] Final CTA
- [x] **Task 3.2:** Build the **Process Page** (`process.html`)
    - [x] Detailed 3-Phase Timeline
    - [x] Final CTA
- [x] **Task 3.3:** Build the **Team Page** (`team.html`)
    - [x] Crew Introduction
    - [x] Individual Member cards
    - [x] Final CTA
- [x] **Task 3.4:** Build the **Contact Page** (`contact.html`)
    - [x] Contact Form
    - [x] Alternate contact methods (Phone, Email, Calendly)

## Phase 4: Finalization
- [ ] **Task 4.1:** Review and test for responsiveness across devices.
- [ ] **Task 4.2:** Final code cleanup and optimization.
- [ ] **Task 4.3:** Prepare for deployment.
