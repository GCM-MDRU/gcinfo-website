# GAYATRI COMMUNICATIONS website

Static website designed for free hosting with GitHub Pages or Cloudflare Pages.

## Files
- `index.html`: home page
- `services.html`: separate Internet-only and Internet + Cable TV plans
- `about-us.html`, `contact-us.html`: business information and contact form
- `privacy-policy.html`, `terms-and-conditions.html`, `refund-policy.html`: policy pages
- `styles.css`, `script.js`: responsive styling and menu/contact-form behavior
- `hero-tech.webp`, `logo.png`, `logo-small.png`: images

## Important links configured
- My Account / Online Payment: https://myaccount.gcinfo.in
- New Connection: https://myaccount.gcinfo.in/book-connection
- LCO Portal: https://sms.vdigital.co.in/login
- WhatsApp: +91 83746 16795
- Email: gcinfo009@gmail.com

## Contact form behavior
The form has two free, no-backend options: WhatsApp opens a prepared message; Email opens a prefilled email draft in the visitor's email app. The visitor must press Send. This static site does not store or automatically deliver form submissions.

## Deploy on Cloudflare Pages
1. Extract the ZIP and upload the files to a GitHub repository (place `index.html` at the repository root).
2. In Cloudflare, create a Pages project connected to the repository.
3. For a plain static HTML site, leave build command blank and use `/` as the output directory.
4. Deploy and test the generated Pages URL before connecting `gcinfo.in`.
5. Connect only the website domain; do not change existing portal DNS records for `myaccount.gcinfo.in` or `portal.gcinfo.in`.

## Before going live
- Check all business details and prices. Prices shown are monthly and exclusive of GST.
- Confirm service offers and current plan availability.
- Test external portals and contact methods.
- Configure HTTPS in Cloudflare Pages/domain settings.
- For the email form, an email app must be configured on the visitor's device. If you need submissions delivered without the visitor's email app, a form service/backend is required.
