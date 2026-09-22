# Ahsan Shahzad Hassan — Portfolio Website (V4)

A responsive, static portfolio site for project-based freelance work. Open `index.html` in a browser to preview; no build step, accounts, or API keys are needed.

## Before you deploy (5 minutes)

1. **Screenshots (recommended).** Three project images currently load from GitHub as a fallback. For reliability, download these and save them in `assets/` with exactly these names:
   - `assets/farmflow-dashboard.png` from `https://raw.githubusercontent.com/mediads786/FarmFlow/main/docs/screenshots/dashboard.png`
   - `assets/ecommerce-dashboard.png` from `https://raw.githubusercontent.com/mediads786/ecommerce-ops-control-center/main/public/screenshots/dashboard.png`
   - `assets/friofix-dashboard.png` from `https://raw.githubusercontent.com/mediads786/service-triage-copilot/main/docs/images/dashboard.png`

   If a local file is missing, the site automatically falls back to the GitHub image, so nothing breaks either way.
2. **Photo (optional).** Save a professional photo as `assets/ahsan.jpg`. It appears in the About section. If the file is missing, the site shows the "AH." monogram instead.
3. Check all four demo links and the email links on desktop and mobile after deploying.

## Deploy with GitHub + Vercel

1. Create a **new** GitHub repository for this portfolio, separate from the four application repositories.
2. Upload the contents of this folder to the repository root (`index.html`, `styles.css`, `script.js`, `assets/`, `README.md`).
3. In Vercel, import the repository, choose **Other** as the framework preset if prompted, leave the root directory as `.`, and do not set a build command.
4. Add the Vercel URL to LinkedIn and your CV once you have confirmed it works.

## Content boundaries

- The four applications are portfolio projects. FarmFlow, E-commerce, and FrioFix public demonstrations are read-only; ProcessLens is a live workflow-analysis application. Do not describe them as externally commissioned client deliveries.
- No visitor metrics, testimonials, pricing, or tracking are included. The case study describes what changed without a percentage; add a measured figure only after timing it.
- The CV is not linked on the site.

## V4 changes

- Hero rewritten in first person; the abstract "Understand / Improve / Build" card is replaced with the real FarmFlow before-and-after (seven entries per animal became one).
- New FarmFlow case study section (problem, what I built, what changed).
- Services rewritten in plain language, with a three-step "how a project works" list.
- About rewritten in a personal voice; optional photo slot added.
- Decorative numbering, slogans, and "scroll to explore" removed; repeated words reduced.
- Project screenshots load locally first with a GitHub fallback.
- Monogram changed from AH to ASH.

## Files

```text
index.html                  Content and layout
styles.css                  Responsive design
script.js                   Mobile navigation and footer year
assets/favicon.svg          Site icon
assets/processlens-overview.jpg
assets/ahsan.jpg            (optional, add your photo)
assets/*-dashboard.png      (recommended, add the three screenshots)
README.md
```
