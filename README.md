# Astro Platform Starter - Fullstack Application

> **Modern fullstack web application leveraging Astro.js, Edge Functions, and Netlify infrastructure**

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://astro-platform-starter.netlify.app/)
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/netlify-templates/astro-platform-starter)

## 🚀 Overview

A production-ready fullstack starter demonstrating modern web architecture patterns:
- **Backend**: Netlify Edge Functions for serverless compute
- **Frontend**: Astro.js with component-based architecture
- **Infrastructure**: Netlify Core Primitives (CDN, Blob Store, Image optimization)
- **Styling**: Tailwind CSS

## 🛠️ Tech Stack

**Backend & Infrastructure**
- Netlify Edge Functions (serverless)
- Blob Store for data persistence
- Image CDN with optimization
- Edge computing capabilities

**Frontend**
- Astro.js (SSG/SSR framework)
- Tailwind CSS
- TypeScript support
- Component architecture

**DevOps**
- Automated CI/CD via Netlify
- Environment management
- CLI-based development workflow

## 💻 Development

### Prerequisites

| Requirement | Version |
| :---------- | :------ |
| [Node.js](https://nodejs.org/) | v18.14+ |
| [Netlify CLI](https://docs.netlify.com/cli/get-started/) | Latest |
| (optional) [nvm](https://github.com/nvm-sh/nvm) | - |

### Quick Start

1. **Clone & Install**
   ```bash
   git clone https://github.com/McMerger/astro-platform-starter.git
   cd astro-platform-starter
   npm install
   ```

2. **Install/Update Netlify CLI**
   ```bash
   npm install netlify-cli@latest -g
   ```

3. **Link to Netlify Site**
   ```bash
   netlify link
   ```
   
   This ensures local development matches production runtime.

4. **Start Development Server**
   ```bash
   netlify dev
   ```
   
   Access at `http://localhost:8888`

### Available Commands

| Command | Action |
| :------ | :----- |
| `npm install` | Install dependencies |
| `npm run dev` | Start Astro dev server at `localhost:4321` |
| `netlify dev` | Start with Edge Functions at `localhost:8888` |
| `npm run build` | Build production site to `./dist/` |
| `npm run preview` | Preview production build locally |
| `npm run astro --` | Run Astro CLI commands |

## 🎯 Features

- **Edge Functions**: Serverless backend logic at the edge
- **Blob Storage**: Persistent data layer
- **Image Optimization**: Automatic CDN optimization
- **TypeScript**: Full type safety
- **Responsive Design**: Mobile-first approach
- **Fast Builds**: Optimized build pipeline

## 📦 Project Structure

```
astro-platform-starter/
├── src/
│   ├── components/     # Reusable UI components
│   ├── layouts/        # Page layouts
│   └── pages/          # Route pages
├── netlify/
│   └── edge-functions/ # Serverless functions
├── public/             # Static assets
└── astro.config.mjs    # Astro configuration
```

## 🔗 Links

- [Live Demo](https://astro-platform-starter.netlify.app/)
- [Netlify Core Primitives](https://docs.netlify.com/core/overview/#develop)
- [Astro Documentation](https://docs.astro.build/)

## 📝 Status

✅ **Production Ready** - Deployed with CI/CD

---

*Built to demonstrate fullstack web development with modern edge computing and serverless patterns.*
