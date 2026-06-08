# Studio Verve — Portfolio Website

A single-file portfolio website for Studio Verve, a WordPress branding + SEO studio.

## What's included

One file: `studio-verve.html`

Four pages navigable via the top nav:
- **Home** — hero, marquee ticker, services preview, work grid, why section
- **Services** — detailed service blocks, process timeline, pricing cards
- **Work** — filterable portfolio grid, testimonials
- **About** — studio story, values, tools, "currently" block
- **Contact** — inquiry form, FAQ accordion, availability tracker

## Tech

- Tailwind CSS (CDN)
- Vanilla JS
- Google Fonts: Cormorant Garamond + Syne
- No frameworks, no build step, no dependencies

## To customize

1. **Name & email** — search for `hello@studioverve.com` and replace with your email
2. **Project images** — the colored gradient swatches in the Work section are placeholders. Replace the `background: linear-gradient(...)` on each `.work-swatch` div with `background-image: url('your-image.jpg'); background-size: cover;`
3. **Project names & tags** — update the `.work-name` and `.work-tag` text in the Work section
4. **Testimonials** — edit the quote text and client names in the Work page
5. **Availability** — update the "spots filled" progress bar width and text in the Contact page
6. **Social links** — find the three `<a href="#">` social links in the Contact page and add your real URLs
7. **Currently block** — update the reading/obsessed/building/listening items in the About page

## To deploy

Just upload `studio-verve.html` to any static host:
- Vercel — drag and drop in the dashboard
- Netlify — same
- GitHub Pages — push to a repo and enable Pages in settings

No build process needed.

## To split into separate pages

If you want separate files (index.html, work.html, etc.), copy the file, delete the pages you don't need, and update the nav `onclick` calls to use `href` links instead.
