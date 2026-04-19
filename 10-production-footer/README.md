# Variant 10 · production-footer

v09 with two targeted fixes that make the site feel like a real production website when deployed.

## What changed from v09

1. **Full production footer across all seven pages.** The old 4-column "Explore / Proof / Reach us" footer is replaced with a 4-column + bottom-bar layout:
   - **Brand block** — logo, tagline ("B2B growth partner for Australian businesses. Human-led, AI-powered."), one-company-two-offices line, LinkedIn and email social icons
   - **Sitemap column** — Home, Services, The Workshop, AI, Data, Case Studies, Our Team (every page linked from every page)
   - **Work with us column** — Growth engine, AI Solutions, The Workshop, Book a discovery call, Client results
   - **Reach us column** — info@automateaccelerator.com, Melbourne address, India operations
   - **Bottom bar** — © 2026 Automate Accelerator, "Partners not a vendor", hundreds-of-businesses line, Privacy / Terms / Contact links

2. **Mobile nav fix.** Previous CSS hid most nav items on narrow viewports using `display:none`. v10 replaces that with `flex-wrap:wrap` so every nav item stays visible, just wraps to two rows on small screens. The Book-a-call CTA stays pinned to the right with `margin-left:auto`.

## Live URLs

- Landing page: **https://aa-site-variants.vercel.app**
- v10 home: **https://aa-site-variants.vercel.app/10-production-footer/**
- v10 Workshop: **https://aa-site-variants.vercel.app/10-production-footer/workshop.html**

## Why this is the production-ready variant

Every variant from v01 to v09 was a positioning experiment. v10 is the first variant that looks and behaves like a real production website:

- Every nav link works on every page, on every viewport (desktop, tablet, mobile)
- Every page has a comprehensive footer that anchors trust
- No "variant X · xxx" meta-references anywhere in the footer
- Legal stub links (Privacy, Terms, Contact) in place, ready to wire up real pages
- Social icons (LinkedIn, email) in place, ready to swap in brand-specific links

## What still needs humans before launch

1. Real LinkedIn company URL in the footer social block (currently placeholder `/company/automate-accelerator`)
2. Real Privacy, Terms, Contact pages behind the footer bottom-bar links
3. Phone number or main office phone if there is one
4. Real ABN or business number
5. Real client video testimonials migrated from the current automateaccelerator.com
6. Real award logo PNGs to replace the styled text tokens on Case Studies and Team pages
7. Real founder bios and headshots (Narayan, Wasim)
8. Melvin's exact title

## Pages

All seven pages carry the new footer + new mobile nav:

1. `index.html` — Home
2. `services.html` — Services
3. `workshop.html` — The Workshop
4. `ai.html` — AI explainer
5. `data.html` — Data
6. `case-studies.html` — Case Studies
7. `team.html` — Our Team

## Run locally

```bash
open index.html
```

Or visit the Vercel URL above.
