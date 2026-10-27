# Affordable Dryer Vent & Gutter Specialists — website redesign

11 preserved URL slugs, one real HTML document for each route. Each route is a folder containing `index.html`, so `/about`, `/gutter-products`, etc. work as clean URLs when hosted on Netlify or Vercel using the bundled `_redirects` / `vercel.json`. All links work locally when you open `index.html` directly too.

## Use
- Offline: open `index.html`, or use the separate `affordabledvgc-offline-preview.html` file for a complete one-file navigable preview with embedded images.
- Local server: run `python -m http.server 8080` in this folder, then visit `http://localhost:8080`.
- Deployment: drag the entire folder into Netlify, or deploy via Vercel/static hosting. Connect the custom domain only after approval.

## Leads — IMPORTANT
Forms are valid HTML forms with Netlify Forms markup and will submit requests **only when deployed to Netlify with Forms enabled**. The home and service/contact pages each have separate lead forms (`lead-home`, etc.). On the offline preview and local files, submit opens a drafted email addressed to `affordabledvgc@gmail.com`; the visitor must click Send in their mail application. This is an honest fallback, **not guaranteed form delivery**. On non-Netlify production hosts, form POSTs will fail visibly until a secure form endpoint is connected. Configure spam prevention and test an actual submission before launch. Do not treat mockup submissions as captured leads.

## Notes
- Source business hours and email from the blueprint crawl (Mon–Sun 8:00 am–8:00 pm; affordabledvgc@gmail.com), not invented mockup values. Confirm before publishing.
- Rating 4.9 and 288 reviews from the Oct 2026 brand/SEO crawl; verify on deployment. Review quotes are sourced from the original site's copy.
- Before/after sliders compare **different jobs** from the supplied photo library; these are labeled illustrative, not falsely represented as the same job.
- Every photo is from the supplied site brand kit, optimized to WebP; some of the provided site assets are pre-existing stock or vendor product shots, as noted in PHOTO-SOURCE-INDEX.md. No AI-generated worker or owner image is represented as real.
- H1 exactly one per original route. Original title/meta descriptions retained in each file. JSON-LD LocalBusiness, AggregateRating, and on Reviews real Review content. FAQ originally noindex was made indexable per the SEO improvement requirement.
- Original rejected routes `/build-your-own-insite4` and Hibu filler blog are intentionally absent.
- No sticky/fixed header. Animation respects reduced-motion preferences. Real gallery, compare sliders, responsive navigation, and click-to-call/text.
- Forms, legal pages, accessibility, and search appearance should be QA checked before launching.
