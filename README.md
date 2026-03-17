# Domain Portfolio Pages

[![Deploy with Cloudflare Pages](https://static.cloudflare.com/pages/button.svg)](https://deploy.workers.cloudflare.com/?url=https://github.com/your-username/your-repo-name)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A powerful, config-driven system to automatically generate and manage a professional portfolio homepage and an unlimited number of individual landing pages for your domains and digital assets.

This project is built with vanilla JavaScript and is deeply optimized for performance, SEO, and seamless deployment on **Cloudflare Pages**. It allows you to manage your entire online presence by editing a single `config.js` file, making it the ultimate tool for domain investors, indie hackers, and digital creators.

**Portfolio Demo:** https://portfolio.domainpickup.com/

## ✨ Core Features

- **Multi-Domain Intelligent Routing**: Use one codebase to serve a main portfolio site and countless unique landing pages on different custom domains.
- **Dual-Mode Rendering Engine**: Automatically displays a beautiful portfolio homepage on your main domain and detailed, conversion-focused sales pages on your asset domains.
- **Deeply SEO-Optimized**: Built with a "static-first" approach, ensuring all content is perfectly visible to search engine crawlers.
- **Highly Customizable**: Easily define custom titles, logos, images, themes, prices, currencies, and contact info for each individual asset via a central config file.
- **Zero Dependencies & Zero Build Steps**: Written in pure, vanilla JavaScript. No frameworks, no `npm install`, no complications. Just edit and deploy.

## 🚀 Deployment with Cloudflare Pages (Recommended)

This project is designed to work perfectly with Cloudflare Pages.

1. **Fork this repository** to your own GitHub account.
2. **Configure your portfolio:**
   - Edit the `config.js` file in your forked repository. Define your main portfolio in `PORTFOLIO_CONFIG` and add all your assets to `ALL_DOMAIN_CONFIGS`.
   - (Optional) Upload any images to the `assets/img/` directory and reference them in `config.js`.
3. **Deploy to Cloudflare Pages:**
   - Log in to your Cloudflare dashboard and go to **Workers & Pages**.
   - Click **Create application** > **Pages** > **Connect to Git**.
   - Select your forked repository.
   - In the "Build settings", you can leave everything as default. No build command or output directory is needed.
   - Click **Save and Deploy**.
4. **Add Custom Domains:**
   - Once deployed, go to your new Pages project's settings and click on the **Custom domains** tab.
   - Add your main portfolio domain and all your asset domains/subdomains. Cloudflare will guide you through the verification process.

That's it! Your entire portfolio is now live on Cloudflare's global edge network, and any future changes you push to the `main` branch of your repository will trigger an automatic redeployment.

## ⚙️ Configuration

All customization happens inside `config.js`. The file is self-documented and allows you to control every aspect of your project.

- `PORTFOLIO_CONFIG`: Defines the content and appearance of your main homepage.
- `ALL_DOMAIN_CONFIGS`: Acts as the database for all your individual assets. Each key is the domain/subdomain that triggers the rendering of a specific page.


## 🎨 Theme Gallery — 24 Built-in Themes

Each theme is a complete visual identity with its own colors, typography, card styles, and effects. Preview every theme live:

### Classic Themes (1–12) — Gradient-based

| # | Theme | Style | Live Demo |
|---|-------|-------|-----------|
| 1 | **Tech** | Purple → Violet gradient | [1.portfolio.domainpickup.com](https://1.portfolio.domainpickup.com) |
| 2 | **Finance** | Teal → Dark Green gradient | [2.portfolio.domainpickup.com](https://2.portfolio.domainpickup.com) |
| 3 | **Creative** | Pink → Orange gradient | [3.portfolio.domainpickup.com](https://3.portfolio.domainpickup.com) |
| 4 | **Minimal** | Black & White, clean | [4.portfolio.domainpickup.com](https://4.portfolio.domainpickup.com) |
| 5 | **Crypto** | Dark + Neon Cyan accents | [5.portfolio.domainpickup.com](https://5.portfolio.domainpickup.com) |
| 6 | **Corporate** | Navy → Deep Blue gradient | [6.portfolio.domainpickup.com](https://6.portfolio.domainpickup.com) |
| 7 | **Luxury** | Gold → Black gradient | [7.portfolio.domainpickup.com](https://7.portfolio.domainpickup.com) |
| 8 | **Ocean** | Blue → Cyan gradient | [8.portfolio.domainpickup.com](https://8.portfolio.domainpickup.com) |
| 9 | **Sunset** | Red → Yellow gradient | [9.portfolio.domainpickup.com](https://9.portfolio.domainpickup.com) |
| 10 | **Dark** | Charcoal → Black gradient | [10.portfolio.domainpickup.com](https://10.portfolio.domainpickup.com) |
| 11 | **Nature** | Forest Green → Sage gradient | [11.portfolio.domainpickup.com](https://11.portfolio.domainpickup.com) |
| 12 | **Royal** | Indigo → Dark Magenta gradient | [12.portfolio.domainpickup.com](https://12.portfolio.domainpickup.com) |

### Extended Themes (13–19) — Distinctive Styles

| # | Theme | Style | Live Demo |
|---|-------|-------|-----------|
| 13 | **Brutalist** | Raw typography, offset shadows, cream bg | [13.portfolio.domainpickup.com](https://13.portfolio.domainpickup.com) |
| 14 | **Glass** | Frosted glass cards, deep purple bg | [14.portfolio.domainpickup.com](https://14.portfolio.domainpickup.com) |
| 15 | **Editorial** | Elegant serif, warm paper bg | [15.portfolio.domainpickup.com](https://15.portfolio.domainpickup.com) |
| 16 | **Terminal** | Green-on-black, monospace, scanlines | [16.portfolio.domainpickup.com](https://16.portfolio.domainpickup.com) |
| 17 | **Wabi-Sabi** | Japanese minimalism, organic warmth | [17.portfolio.domainpickup.com](https://17.portfolio.domainpickup.com) |
| 18 | **Neumorph** | Soft 3D neumorphic cards, light bg | [18.portfolio.domainpickup.com](https://18.portfolio.domainpickup.com) |
| 19 | **Retro** | 80s arcade, neon pink/cyan, pixel font | [19.portfolio.domainpickup.com](https://19.portfolio.domainpickup.com) |

### More Themes (20–24) — Strong Personality

| # | Theme | Style | Live Demo |
|---|-------|-------|-----------|
| 20 | **Newspaper** | Classic print layout, red accents, serif | [20.portfolio.domainpickup.com](https://20.portfolio.domainpickup.com) |
| 21 | **Noir** | Film noir black + gold accents | [21.portfolio.domainpickup.com](https://21.portfolio.domainpickup.com) |
| 22 | **Candy** | Pastel pink → purple → blue gradient | [22.portfolio.domainpickup.com](https://22.portfolio.domainpickup.com) |
| 23 | **Blueprint** | Technical grid on deep blue, monospace | [23.portfolio.domainpickup.com](https://23.portfolio.domainpickup.com) |
| 24 | **Zen Garden** | Dark sage green, peaceful minimalism | [24.portfolio.domainpickup.com](https://24.portfolio.domainpickup.com) |

## ❤️ Supporting the Project

This project is offered completely free of charge under the MIT license. I believe in open-source and want to provide tools that help the community.

If you find this project useful, please consider showing your support in one of the following ways:

- **⭐ Star the repository on GitHub:** This is the easiest way to show your appreciation and helps increase the project's visibility.
- **🔗 Keep the footer link:** While the license allows you to remove it, I would be very grateful if you choose to keep the "Powered by" link in the footer. It's a small nod that helps others discover this tool.
- **Share it:** Tell your friends or colleagues about Domain Portfolio Pages!

Your support is greatly appreciated and motivates me to continue improving this project. Thank you!
