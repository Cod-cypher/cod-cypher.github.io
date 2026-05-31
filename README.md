# Waqar's Portfolio - Astro + Tailwind CSS

A modern, performant portfolio website built with Astro and Tailwind CSS, featuring reusable components and optimized for GitHub Pages.

## 🚀 Features

- **Static Site Generation** - Lightning-fast performance with Astro
- **Reusable Components** - Modular architecture with shared layouts, navigation, and footer
- **Dark Mode** - Persistent theme preference across pages
- **SEO Optimized** - Comprehensive meta tags, Open Graph, and structured data
- **Blog Ready** - Custom blog layout with progress bar and optimized typography
- **Responsive Design** - Mobile-first approach with Tailwind CSS
- **Analytics** - Integrated Google Analytics and Microsoft Clarity

## 📁 Project Structure

```
portfolio/
├── src/
│   ├── components/
│   │   ├── Footer.astro        # Reusable footer component
│   │   └── Navigation.astro    # Navigation with theme toggle
│   ├── layouts/
│   │   ├── BaseLayout.astro    # Main layout wrapper
│   │   └── BlogLayout.astro    # Blog post layout
│   └── pages/
│       ├── index.astro         # Homepage
│       └── how-i-built-this-website-in-30-minutes-using-gemini.astro
├── public/
│   ├── favicon.svg
│   ├── robots.txt
│   └── CNAME
└── astro.config.mjs
```

## 🛠️ Tech Stack

- **[Astro](https://astro.build)** - Static site generator
- **[Tailwind CSS](https://tailwindcss.com)** - Utility-first CSS framework
- **[TypeScript](https://www.typescriptlang.org)** - Type safety

## 📦 Installation

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 🎨 Development

The dev server runs on `http://localhost:4321`

To add new blog posts:
1. Create a new `.astro` file in `src/pages/`
2. Use the `BlogLayout` component
3. Update the homepage to link to your new post

## 🚢 Deployment

This site is configured for GitHub Pages deployment. The build outputs to `/dist` directory.

```bash
npm run build
```

The static files in `/dist` can be deployed to any static hosting service.

## 🌐 SEO

- Sitemap index is auto-generated in `dist/sitemap-index.xml`
- `robots.txt` configured for search engine crawlers
- Meta tags and Open Graph data on all pages
- Semantic HTML structure

## 📝 License

This project is open source and available under the MIT License.

## 👤 Author

**Waqar**
- Website: [waqar-tech.com](https://waqar-tech.com)
- LinkedIn: [waqar-shabbir](https://www.linkedin.com/in/waqar-shabbir-022653230/)
