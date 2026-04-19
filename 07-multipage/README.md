# Variant 07 · multipage

The first multi-page variant. Six dedicated pages, each with a single purpose. Built on the first-principles AI architecture that fixes the story the earlier variants muddled.

## The first-principles decision

**AI is a capability layer. Not a parallel service line.**

- AA has ONE growth product: the human SDR engine with AI baked in. Data AI, Creative AI, Multi-channel AI, Voice AI. All bundled inside one engagement, priced as one thing.
- AA has ONE standalone AI engagement: AI Solutions. AI built inside the client's own operations. Separate team (solution architects, developers), separate engagement, separate buyer.
- No third "AI service" bucket in the middle. No AI Outbound sold separately. No confusion.

This architecture is stated on the AI page in one sentence: *"AI lives in two places at AA. Inside our Growth engine, where it multiplies what the SDR team can do. And as a standalone engagement called AI Solutions, where we build AI inside your own operations. That is the whole story."*

Every page reflects it.

## The six pages

1. **Home** (`index.html`) — overarching pitch, under 2,500 words, one clear CTA every two scrolls. Hero plants the AI story ("Human SDRs. AI where it multiplies.") before the reader goes deeper.
2. **Services** (`services.html`) — the commercial page. Two products: Growth engine (with AI inside) and AI Solutions (standalone). Each has who-it-is-for, what-you-get, how-you-engage columns.
3. **AI** (`ai.html`) — the page that kills the AI confusion. Opens with the one-sentence answer. Shows the two layers side by side. Includes a "what we do NOT do" block and a six-item FAQ.
4. **Data** (`data.html`) — AA's technical edge as a standalone page. Hero stats (42 / 12 / 3), a four-step workflow, a them-vs-us contrast block, a worked example of a data brief.
5. **Case Studies** (`case-studies.html`) — featured case, twenty-niche playbook, six video testimonial slots, authentic founders' awards strip. All proof in one page.
6. **Our Team** (`team.html`) — founders (Narayan, Wasim), Melbourne account management, AA-owned India operations, partnership framing, awards repeated.

## StoryBrand spine (invisible to the reader)

Every page carries a StoryBrand role. The reader never sees the framework.

- **Home** walks the full StoryBrand arc: Hero + Want + Problem + Guide + Plan + CTA + Success + Failure avoided.
- **Services** expands the Plan.
- **AI** is the Guide's mechanism explained.
- **Data** is the Guide's credentials.
- **Case Studies** is the Success proof.
- **Our Team** is the Guide humanised.

Whichever page a visitor lands on, there is a next-step CTA that funnels them toward the Discovery call.

## What carries from v5/v6

- Brand palette (orange #F47920, purple #412F8F, ink, paper, cream)
- Typography (Inter body, Instrument Serif italic accents)
- "Hundreds of Australian B2B businesses since 2021"
- Human SDR as the foundation
- "No contracts. Performance-based. Proof, not promises." as the commercial promise
- Pay only when leads convert + client covers third-party tool costs
- Collaboration-not-agency partnership framing
- 20 B2B niches (all of them on the Case Studies page)
- Six client video testimonial placeholders
- Authentic founders' awards strip
- Melbourne mentioned only where it earns its place (Team page, transparency lines, footer)

## What changes from v5/v6

- Split from one long-scroll into six purpose-built pages
- AI story restructured into the "two layers, nothing in between" architecture
- Services is "two products" rather than "three service lines"
- Data gets a full page instead of a sidebar
- Our Team gets a full page instead of a small block
- Home is deliberately lean (conversion) rather than encyclopaedic

## File structure

```
07-multipage/
├── index.html          Home
├── services.html       Services (Growth + AI Solutions)
├── ai.html             AI (the architecture explainer)
├── data.html           Data (the technical edge)
├── case-studies.html   Case Studies + videos + awards
├── team.html           Our Team (founders + operations)
├── styles.css          Shared design system (all pages)
└── README.md           This file
```

## Open items before launch

1. **Real video testimonials** — migrate six from the current automateaccelerator.com and drop them into the Case Studies slots
2. **Real award logo PNGs** — replace styled text tokens on the Case Studies page
3. **Founders bios** — placeholder paragraphs for Narayan and Wasim on the Team page need real copy
4. **Melvin's exact title** — on the Team page, India operations card
5. **Real headshots** — for Narayan, Wasim, Melbourne AM, India operations lead
6. **Named Case Studies** — replace the placeholder niche descriptions with real client names where permission is on file

## Run locally

```bash
# Open any page in the default browser
open index.html
```

All pages share the same nav and footer so navigation works cleanly locally.

## Where v07 sits in the set

- v01 editorial-founder · v02 martell-translated · v03 service-first-clean · v04 data-forward · v05 human-first · v06 proof-layer — all one-page long-scroll variants, frozen for comparison.
- v07 multipage — first multi-page variant, built from first principles to fix the AI story.

If v07 lands with the team, the build proceeds from here. If it does not, v05 or v06 are the one-page fallback spines.
