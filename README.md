# Portfolio Site v2

A modern, minimalist portfolio website built with Astro, featuring a clean academic design with unique interactive elements.

## Features

- 🎨 Modern, minimalist design with academic aesthetic
- 🌓 Light/Dark theme toggle
- 📱 Fully responsive
- 📄 Publications section with expandable details
- 🚀 Projects showcase
- 📅 Interactive resume timeline with company logos
- 🖼️ Photo gallery with lightbox
- 📥 Resume PDF download
- ⚡ Interactive network graph background (optional)

## Tech Stack

- [Astro](https://astro.build/) - Static site generator
- TypeScript - Type safety
- CSS Variables - Theme system
- Canvas API - Interactive network graph

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Build for production:
```bash
npm run build
```

4. Preview production build:
```bash
npm run preview
```

## Deployment

This site is configured for deployment on Vercel. Simply connect your GitHub repository to Vercel and it will automatically deploy.

### Manual Deployment

1. Build the site:
```bash
npm run build
```

2. The `dist/` folder contains the static site ready for deployment.

## Project Structure

```
/
├── public/
│   ├── images/          # Images and logos
│   └── favicon.svg
├── src/
│   ├── components/      # Reusable components
│   │   ├── Bio.astro
│   │   ├── Header.astro
│   │   ├── NetworkGraph.astro
│   │   ├── Projects.astro
│   │   ├── Publications.astro
│   │   └── Timeline.astro
│   ├── layouts/         # Page layouts
│   │   └── BaseLayout.astro
│   └── pages/          # Route pages
│       ├── index.astro
│       ├── gallery.astro
│       └── resume.astro
├── astro.config.mjs
├── package.json
└── vercel.json
```

## Customization

### Adding Publications

Edit `src/components/Publications.astro` and add to the `publications` array.

### Adding Projects

Edit `src/components/Projects.astro` and add to the `projects` array.

### Adding Resume PDF

Place your resume PDF file in the `public/` directory as `resume.pdf`.

### Updating Timeline

Edit `src/components/Timeline.astro` and modify the `timelineItems` array.

## License

MIT

