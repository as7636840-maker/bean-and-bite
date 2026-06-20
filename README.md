# Bean & Bite — Landing Page ☕

A modern, high-converting, fully responsive landing page for **Bean & Bite**, a premium coffee shop and café brand. Built with conversion rate optimization (CRO) best practices to drive online orders and app downloads.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Yes-success)
![License](https://img.shields.io/badge/license-MIT-blue)

## Live Preview

Open `index.html` directly in any browser — no build step, no dependencies, no install required.

## Features

- 🎨 Premium coffee-shop aesthetic — coffee brown, dark coffee, warm beige, cream, and a gold accent
- 🌍 Arabic (RTL) content, set in Cairo
- 📱 Fully responsive — desktop, tablet, and mobile
- ⚡ Vanilla HTML5 / CSS3 / JS — no frameworks, single self-contained file
- ✨ Scroll-reveal animations, hover micro-interactions, floating hero visuals
- 🛒 Interactive "Add to Cart" buttons with toast feedback
- 📲 Sticky mobile order bar + App Store / Google Play download CTA
- ♿ Semantic HTML, visible focus states, `prefers-reduced-motion` support
- 🔍 SEO-friendly structure with meta tags and lazy-loaded images

## Sections

| # | Section | Description |
|---|---------|--------------|
| 1 | Hero | Headline, subheadline, and primary "Order Online" CTA |
| 2 | Best Sellers | Featured product cards (Iced Spanish Latte, Dark Chocolate Cake, Modern Tuna Sandwich) |
| 3 | Why Us | Specialty coffee, fast prep, quality-preserving delivery |
| 4 | Testimonials | Customer reviews — swipeable carousel on mobile |
| 5 | App Download CTA | App Store / Google Play buttons |
| 6 | Footer | Social links, working hours, legal links, copyright |

## Tech Stack

- **HTML5** — semantic markup (`header`, `main`, `section`, `footer`, `article`)
- **CSS3** — custom properties, CSS Grid/Flexbox, animations, no external framework
- **JavaScript (vanilla)** — IntersectionObserver for scroll reveals, cart interactions, mobile nav, testimonial slider
- **Google Fonts** — Cairo

## Getting Started

```bash
git clone https://github.com/your-username/bean-and-bite-landing.git
cd bean-and-bite-landing
open index.html   # or just double-click the file
```

No build tools, no `npm install` — it just works.

## Customization

| What | Where |
|------|-------|
| Product images | Replace the Unsplash placeholder `src` URLs in the Best Sellers and App CTA sections |
| Logo | Swap the inline SVG coffee-cup mark in the navbar/footer with your brand logo |
| App Store / Google Play links | Update the `href="#"` values in the App Download section |
| Social media links | Update the `href="#"` values in the footer's social icons |
| Colors | Edit the CSS custom properties at the top of the `<style>` block (`--coffee`, `--coffee-dark`, `--beige`, `--cream`, `--gold`, etc.) |
| Copy / pricing | Edit directly in the HTML — all content is in Arabic and easy to locate by section |

## Browser Support

Works in all modern evergreen browsers (Chrome, Firefox, Safari, Edge). Gracefully degrades for older browsers without `IntersectionObserver` support.

## License

MIT — free to use and modify for your own projects.

## Credits

Placeholder imagery sourced from [Unsplash](https://unsplash.com). Replace with licensed product photography before production use.
