# Velvet Pour

A frontend practice project built with React, Vite, Tailwind CSS, and GSAP.

## Overview

This project is a single-page cocktail showcase created to practice responsive layout, animation, and visual storytelling in React. The UI is made up of section-based components with scroll-triggered motion, animated text, and media-heavy presentation.

## Features

- Animated hero section with video scrubbing
- Scroll-based GSAP reveals and parallax effects
- Responsive layout built with Tailwind CSS v4
- Sectioned landing page flow for cocktails, about, art, menu, and contact
- Interactive cocktail slider with previous and next navigation
- Static media experience using custom fonts, images, and video assets

## Tech Stack

- React 19
- Vite 7
- Tailwind CSS 4
- GSAP and `@gsap/react`
- `react-responsive`
- ESLint 9

## Getting Started

### Prerequisites

- Node.js 18+ recommended
- npm

### Install

```bash
npm install
```

### Run the development server

```bash
npm run dev
```

### Build for production

```bash
npm run build
```

### Preview the production build

```bash
npm run preview
```

### Lint the project

```bash
npm run lint
```

## Project Structure

```text
.
|- src/
|  |- components/
|  |- App.jsx
|  |- main.jsx
|  `- index.css
|- constants/
|- public/
|  |- fonts/
|  |- images/
|  `- videos/
|- index.html
|- package.json
`- vite.config.js
```

## Notes

- This is a frontend-only practice project with no backend or API integration
- No environment variables are currently required
- No automated test setup is included yet
- The visual experience depends on local image, font, and video assets in `public/`
- The repository currently includes both `package-lock.json` and `bun.lock`, but the documented workflow here uses npm

## Scripts

- `npm run dev` - start the Vite dev server
- `npm run build` - create a production build
- `npm run preview` - preview the production build locally
- `npm run lint` - run ESLint

## Practice Focus

This project is most useful as a reference for:

- Tailwind-based page composition
- GSAP timeline and scroll-trigger patterns
- Responsive React component structure
- Media-rich landing page experimentation
