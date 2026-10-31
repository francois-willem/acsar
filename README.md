# ACSAR

Static Astro website for Advanced Climate Systems and Refrigeration, serving Malmesbury, Cape Town and surrounding areas.

## Local development

- `npm install`
- `npm run dev`
- `npm run build` generates the production site in `dist/`.
- `npm run preview` previews the production build.

## Content

Pages live in `src/pages/`, the shared layout in `src/layouts/Layout.astro`, and styles in `src/styles/global.css`. Service content is in `src/pages/services/[service].astro`.

Contact: WhatsApp +27 67 387 4969 and acsarhvac@gmail.com. No contact form backend is required. The hero is an original vector illustration, not a photograph of ACSAR's work. The supplied ACSAR logo is used in the header and footer. Social posts are not presented as photographs of completed work.

## Publication on acsar.co.za

The domain purchase does not itself establish web hosting. With static web hosting available, upload the **contents** of `dist/` to the host's web document root. The site requires no Node runtime in production. Verify HTTPS, redirect www to the chosen non-www HTTPS domain, and configure the host to serve `404.html` for missing pages. DNS and hosting have not been changed by this project.

## SEO

Includes unique titles and descriptions, canonical links, crawlable static service pages, semantic headings, HVACBusiness JSON-LD, robots.txt and sitemap.xml. No invented address, hours, reviews or qualifications are included. LocalBusiness rich-result eligibility needs additional verified business details; the current markup does not promise rich results. Replace the SVG social image with a 1200×630 PNG/JPEG before launch for wider social-platform support.

Before launch, verify service descriptions and coverage, supply real project photographs if available, and confirm any public address and opening hours. After launch, connect Google Search Console, submit `https://acsar.co.za/sitemap.xml`, and establish/verify the Google Business Profile with consistent contact details. Search ranking is not guaranteed.

Official references: https://docs.astro.build/en/guides/deploy/ and https://developers.google.com/search/docs/appearance/structured-data/local-business
