# Ahsan Shahzad Hassan — Portfolio

A static portfolio website for project-based freelance work: selected projects, services, and contact details. No build step, accounts, or API keys are needed.

## Structure

```text
index.html      Page content and layout
styles.css      Styling and responsive design
script.js       Mobile navigation and footer year
assets/         Images and icons
```

## Running locally

Open `index.html` directly in a browser, or serve the folder with any static file server.

## Deployment

This site is a static site and can be deployed with any static hosting provider (e.g. Vercel, Netlify, GitHub Pages). No build command or output directory is required.

## Contact

For inquiries, use the contact details on the site.

## Order Gateway — n8n + PostgreSQL

The selected-work entry links to [the public project repository](https://github.com/mediads786/order-gateway-n8n) and its [verified QA report](https://github.com/mediads786/order-gateway-n8n/blob/main/docs/QA-TEST-REPORT.md). It describes durable order intake, duplicate prevention, recoverable ERP delivery and operational alerts. The four pre-existing portfolio project cards are preserved.

The three evidence images in `assets/` contain genuine screenshot crops, captured or inspected on 13 October 2026:

- `order-gateway-n8n-workflows.jpg`: arranged screenshots of the existing Module 01 intake and Module 02 default mock-delivery workflow canvases.
- `order-gateway-n8n-execution-1131.jpg`: native saved execution #1131, successful Shopify intake on 12 October 2026; no execution was rerun for the capture.
- `order-gateway-n8n-outcome.jpg`: the retained Shopify #1018 screenshot paired with native saved Odoo readback crops and the success status of execution #1132. The readback shows quotation S00048, draft state and USD amounts. Odoo was stopped during capture, so its quotation interface was not captured or reconstructed.

The flattened JPEG evidence sheets contain only the privacy-safe screenshot crops. Captions and arrangement were added; workflow nodes, execution statuses and result values were not fabricated. Customer information, credentials, tokens and request payloads are excluded. The default worker uses mock ERP; the real Odoo draft test and signed replay are separate verified evidence. Remaining limitations are recorded in the linked QA report.


## Capability organization and Order Gateway API

The homepage contains six projects, with All Projects selected by default. Filters reflect business capabilities and allow genuine overlap: both Order Gateway implementations and E-commerce appear under Systems and Automation; FrioFix and FarmFlow appear under Systems; ProcessLens appears under Analysis. Display order is API, n8n, E-commerce, FrioFix, FarmFlow, ProcessLens. Every prior project remains available.

Both Order Gateway implementations have separate cross-linked case studies under `projects/`. The existing n8n screenshots and verified evidence are retained on its detail page. The API card uses the current styled interface, not the earlier unstyled GIF.

The new API recording is a 42-second edit of actual captures from 13 October 2026. It combines a two-order local mock demo (normal delivery, replay, three HTTP 500 retries, recovery on attempt 4) and a separate signed synthetic Shopify fixture sent through the existing public tunnel (acceptance, first-attempt delivery and same-ID replay). It does not claim a real Shopify-emitted order or live Odoo operations in this recording. One tunnel response exceeded the capture script's fault-stage timing window; the fixture delivered on attempt 1, and the edit labels that separately from mock recovery.

Public media: `order-gateway-api-card.jpg`, `order-gateway-api-current-demo.mp4`, and `order-gateway-api-current-demo.gif`. Customer fields are concealed; authentication was completed before capture. No API/n8n business logic, secrets, subscriptions, database volumes or frontend design were changed. Three synthetic orders were added and retained. Fingerprints verified every pre-existing row in all ten business tables remained unchanged. Historical Odoo and CI evidence is linked with its original scope.

The project arrangement and media were reviewed and approved for publication on 13 October 2026.


## Gallery layout

The six-project homepage keeps its capability filters and two desktop columns. Cards now show only category, title, a short business outcome and Explore Project. Preview aspect ratio is 2.6:1 (about 38% less image height than the former 1.63:1 cards). Desktop gaps are 36px horizontally and 56px vertically, with 28px internal padding. Tablet and phone layouts use one column and proportionate spacing.

All six projects have detail pages. Existing descriptions, technology stacks, demonstration boundaries and external links are retained there. The two Order Gateway case studies preserve their QA/media and reciprocal implementation links. The supporting automation screenshots remain on `projects/automation-examples.html`, and the low-stock example also appears on the E-commerce detail page. No technical content or project was removed.

The n8n homepage preview uses the existing genuine intake-canvas capture, contained within the same preview frame to avoid cutting through the workflow. The full intake/delivery evidence sheet remains on its detail page. Rendered checks at 1440px desktop, 834px tablet and 390px phone confirmed equal card heights, functioning filters and no horizontal overflow. Desktop measurements were 36px column gap, 56px row gap, 28px padding and approximately 222px previews.
