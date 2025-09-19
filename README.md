# Virtual Community - Landing Page

A modern, responsive landing page for Virtual Community, an open-world simulation platform for embodied multi-agent research.

## 🚀 About Virtual Community

Virtual Community addresses the limitations of current embodied AI platforms by integrating large-scale, real-world geospatial data with generative models to create interactive, scalable open-world scenes and socially grounded agent communities.

### Key Features

- **Scalable Simulation-Ready Scenes**: Automatic generation of 3D environments from real-world geospatial data
- **Scene-Grounded Agent Communities**: AI agents with realistic profiles and social relationship networks
- **Genesis Physics Engine**: Physically realistic simulations of multi-agent interactions
- **Research Challenges**: Community Planning and Community Robot challenges for advancing embodied AI

## 🛠️ Technology Stack

- **Framework**: [Astro](https://astro.build/) - Modern web framework for content-focused websites
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- **Language**: TypeScript for type safety
- **Font**: Inter font family for modern typography

## 🏗️ Project Structure

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Navigation.astro    # Fixed navigation bar
│   │   ├── Hero.astro          # Hero section with main CTA
│   │   ├── About.astro         # About Virtual Community
│   │   ├── Features.astro      # Key platform features
│   │   ├── Challenges.astro    # Research challenges
│   │   ├── Demo.astro          # Interactive demos
│   │   └── Footer.astro        # Site footer
│   ├── layouts/
│   │   └── Layout.astro        # Base layout with Tailwind CSS
│   ├── pages/
│   │   └── index.astro         # Main landing page
│   └── styles/
│       └── global.css          # Tailwind CSS imports
├── astro.config.mjs            # Astro configuration
└── package.json
```

## 🚀 Getting Started

1. **Install dependencies**:

   ```bash
   npm install
   ```

2. **Start the development server**:

   ```bash
   npm run dev
   ```

3. **Open your browser** and visit `http://localhost:4321`

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run astro` - Run Astro CLI commands

## 🚀 Deployment

This project is configured for automatic deployment to GitHub Pages.

### GitHub Pages Setup

The site is configured to deploy to: `https://weebao.github.io/vico-web`

**Automatic Deployment:**

- Pushes to the `main` branch automatically trigger deployment
- GitHub Actions workflow builds and deploys the site
- No manual intervention required

**Manual Deployment:**

- Go to the Actions tab in your GitHub repository
- Run the "Deploy to GitHub Pages" workflow manually

**Requirements:**

- Repository must have GitHub Pages enabled
- Source should be set to "GitHub Actions" in repository settings
- The workflow file is located at `.github/workflows/deploy.yml`

### Local Production Build

To test the production build locally:

```bash
npm run build
npm run preview
```

## 🚀 Deployment

This project is configured for automatic deployment to GitHub Pages.

### GitHub Pages Setup

The site is configured to deploy to: `https://weebao.github.io/vico-web`

**Automatic Deployment:**
- Pushes to the `main` branch automatically trigger deployment
- GitHub Actions workflow builds and deploys the site
- No manual intervention required

**Manual Deployment:**
- Go to the Actions tab in your GitHub repository
- Run the "Deploy to GitHub Pages" workflow manually

**Requirements:**
- Repository must have GitHub Pages enabled
- Source should be set to "GitHub Actions" in repository settings
- The workflow file is located at `.github/workflows/deploy.yml`

### Local Production Build

To test the production build locally:

```bash
npm run build
npm run preview
```

## 🎨 Design System

### Colors

- **Primary**: Blue (400, 500, 600)
- **Secondary**: Purple (400, 500, 600)
- **Accent**: Cyan (400)
- **Background**: Gray (950, 900)
- **Text**: White, Gray (300, 400)

### Typography

- **Font Family**: Inter
- **Headings**: Bold weights (600, 700)
- **Body**: Regular weight (400)

### Components

- Modern glassmorphism effects
- Gradient backgrounds and text
- Subtle animations and hover states
- Responsive grid layouts
- Accessible navigation

## 🔬 Research Information

Virtual Community enables:

- Large-scale 3D environments from real-world geospatial data
- Automatic scene annotation and object placement
- Multi-agent communities with social relationships
- Physics-based simulation using Genesis engine
- Novel research challenges in embodied AI

## 📄 License

This project is part of the Virtual Community research initiative. Please refer to the research paper and official documentation for usage guidelines.

## 🤝 Contributing

This landing page represents ongoing research in embodied AI. For research collaborations or technical contributions, please refer to the official Virtual Community documentation.
