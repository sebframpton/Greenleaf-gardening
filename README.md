# GreenLeaf Gardening & Landscaping — Software Prototype

An independent front-end software prototype and technical demonstration showcasing a responsive web interface for a local gardening and landscaping service in Perth, WA.

> **Prototype & Sandbox Notice**: This repository and its associated live preview are operated strictly as a non-commercial software demonstration and UI/UX prototype. All business details, service packages, pricing estimates, customer testimonials, and contact information depicted in the application are fictional. Do not submit real sensitive or confidential personal data into any forms.

---

## Features & Architecture

- **Single-Page Responsive Layout**: Built with semantic HTML5, Tailwind CSS, and vanilla JavaScript.
- **Interactive Quote Request Flow**: Client-side modal form with validation and instant confirmation state (ephemeral session state; no backend persistence).
- **Project Showcase & Lightbox**: Expandable 8-project gallery grid (`View More Projects` toggle) paired with a full-screen image lightbox modal.
- **Unified Legal & Sandbox Notice Modal**: Dark-mode modal accessible from the footer (`Privacy Policy` and `Terms & Conditions`) detailing sandbox data handling and "as-is" software terms.
- **Search Engine Indexing Protection**: Configured with `<meta name="robots" content="noindex, nofollow" />` to prevent public preview URLs from being indexed by search engines.

---

## Tech Stack

- **Markup & Styling**: HTML5, [Tailwind CSS](https://tailwindcss.com/) (via CDN with custom brand design tokens)
- **Typography**: [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) (Headings) & [Inter](https://fonts.google.com/specimen/Inter) (Body)
- **Interactivity**: Vanilla JavaScript (ES6+)
- **Deployment**: Configured for zero-build static hosting on [Vercel](https://vercel.com/) via `vercel.json`

---

## Local Development

Because this prototype is a self-contained static application, no build step or package installation is required to run it locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sebframpton/Greenleaf-gardening.git
   cd Greenleaf-gardening
   ```
2. **Open in browser**:
   - Open `greenleaf_gardening_landscaping_website.html` directly in any modern browser, or
   - Serve the directory with a local static server (e.g., VS Code Live Server or `npx serve .`).

---

## Vercel Preview Deployment

This repository includes a [`vercel.json`](./vercel.json) rewrite rule that maps the root path (`/`) directly to `/greenleaf_gardening_landscaping_website.html`:

1. Push this repository to GitHub.
2. Import the project in the [Vercel Dashboard](https://vercel.com/new) with the **Framework Preset** set to `Other`.
3. No environment variables are required for the static prototype (see [`.env.example`](./.env.example) for optional future placeholders).

---

## License & Intellectual Property

The custom source code, UI design, and architecture of this project remain the intellectual property of the developer, provided "as-is" for evaluation and demonstration purposes without warranties of any kind.

