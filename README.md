# EverETH Landing Page

A modern, responsive landing page for a cryptocurrency or blockchain product, built with React, TypeScript, and styled-components. This project is designed to showcase a crypto brand with a premium hero section, feature highlights, roadmap, FAQ, and conversion-focused CTAs.

## Overview

EverETH is structured as a single-page marketing site with a strong visual identity and flexible content-driven sections. It is ideal for startups, token launches, DeFi products, or blockchain ventures that need a polished landing page quickly.

### Highlights

- Modern hero section with clear value proposition
- Responsive layout optimized for desktop and mobile
- Section-based marketing architecture for product, roadmap, and FAQ
- Styled-components for component-level design control
- Multilingual support using i18next
- Routing-ready structure for future page expansion

## Tech Stack

- React 17
- TypeScript
- Create React App
- Styled Components
- Ant Design
- React Router
- i18next
- Axios

## Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- Node.js 14 or later
- npm or yarn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/crypto-landing-master.git
   cd crypto-landing-master
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

4. Open the app in your browser:

   ```text
   http://localhost:3000
   ```

## Available Scripts

```bash
npm start
```
Runs the app in development mode.

```bash
npm run build
```
Creates a production build for deployment.

```bash
npm test
```
Starts the test runner in interactive watch mode.

```bash
npm run eject
```
Ejects the app configuration from Create React App. Use with caution.

## Project Structure

```text
crypto-landing-master/
├── public/
│   ├── fonts/
│   ├── img/
│   ├── index.html
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── common/
│   ├── components/
│   ├── content/
│   ├── locales/
│   ├── pages/
│   ├── router/
│   ├── styles/
│   ├── index.tsx
│   ├── translation.ts
│   └── ...
├── package.json
├── tsconfig.json
├── README.md
└── .gitignore
```

## Customization

### Content

The main marketing text is stored in the `src/content` folder. Update the JSON files there to change:

- Hero copy
- Product messaging
- Mission statement
- Roadmap content
- FAQ text
- Contact details

### Localization

Translations are stored in `src/locales/`. Add or update language files in the existing structure to support additional locales.

### Styling

The design system is primarily controlled through styled-components and the theme-related styling files under `src/styles` and component-specific style modules.

## Deployment

After making the necessary changes, build the project for production:

```bash
npm run build
```

The generated static assets will be placed in the `build/` directory and can be deployed to any static hosting provider such as Vercel, Netlify, or Firebase Hosting.

## Notes

This project is a front-end landing page template and can be adapted for a real product launch, investor presentation, or marketing campaign. You can extend it with real project data, wallet integrations, or additional pages as needed.

## License

This project does not currently include a license file. If you are using it for personal or commercial work, confirm the appropriate licensing terms before publishing or distributing it.
