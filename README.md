# PROJECT DR J — Website starter

A responsive six-page dark-premium professional dental platform.

## Pages
- `index.html` — Home
- `about.html` — Professional profile and CV information
- `queries.html` — Dental education hub and question submission
- `connect.html` — Patient, professional and business enquiries
- `store.html` — Dental and educational product catalogue with a local enquiry cart
- `vision.html` — Projects, professional initiatives and entrepreneurship

## Run locally
From this folder:

```bash
python3 -m http.server 3000
```

Open http://localhost:3000. You can also use `npx serve .`.

## Before publishing — required checklist
1. Replace `ADD-YOUR-EMAIL@example.com` in `queries.html`, `connect.html` and `store.html` with the correct monitored professional/business email address.
2. Verify every qualification, licence, title, date, employer, clinical metric and professional claim on `about.html`. The page intentionally flags details that require confirmation.
3. Add your real YouTube channel and Instagram profile links and embed approved videos on `queries.html`.
4. Add current clinic address, booking contact and approved patient contact information on `connect.html`.
5. Replace store category placeholders with actual products, verified descriptions, prices, images, stock, delivery/returns terms and required UAE regulatory approvals.
6. The store is currently a product-enquiry catalogue only. It does not accept payments, confirm orders, calculate shipping or manage inventory. Connect a secure commerce backend and UAE-compatible payment provider before selling.
7. The enquiry forms currently use a `mailto:` hand-off. They are not secure database forms and should not collect patient records or sensitive health information. Connect a secure form backend and publish an appropriate privacy notice before launch.
8. Add your final privacy policy, terms, cookie/analytics disclosures, store returns policy and business/legal details as applicable.
9. Test all pages on mobile, check all links and add a custom domain in Vercel after deployment.

## Deploy to Vercel
Import the project folder/repository into Vercel as a static site. No build command is required; set the output directory to `.`. The included `vercel.json` supports clean deployment of the static files.

## Important
This is a complete front-end website foundation, not a fully operational clinical portal or transactional e-commerce system. Do not represent appointment requests as confirmed bookings or educational content as personalised medical advice.
