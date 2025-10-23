# Sulistyanto Service - Payment Information Website

A modern, intuitive payment information website built with AstroJS and Tailwind CSS.

## Features

- 🎨 Modern, clean UI/UX design
- 📱 Fully responsive for all devices
- 💳 QRIS payment integration
- 🏦 Bank account information with copy functionality
- ⚡ Fast static site generation
- 🔒 Secure and reliable

## Tech Stack

- **AstroJS** - Static site generator
- **Tailwind CSS** - Utility-first CSS framework
- **TypeScript** - Type safety
- **Inter Font** - Modern typography

## Development

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start development server:
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

### GitHub Pages (Recommended)

1. Push your code to a GitHub repository
2. Enable GitHub Pages in repository settings
3. The GitHub Actions workflow will automatically deploy your site

### Other Platforms

This static site can be deployed to any static hosting service:
- Vercel
- Netlify
- Cloudflare Pages
- AWS S3 + CloudFront

## Project Structure

```
src/
├── layouts/
│   └── Layout.astro      # Main layout component
├── pages/
│   └── index.astro       # Home page
└── styles/
    └── global.css        # Global styles with Tailwind
```

## Customization

- Update payment information in `src/pages/index.astro`
- Modify styling in the same file using Tailwind classes
- Add new pages by creating `.astro` files in `src/pages/`

## License

© Sulistyanto Service