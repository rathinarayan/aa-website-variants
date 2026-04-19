# AA Site Variants · 19 April 2026

Three working static sites, each one a different bet on how to position the new AA website. Single long-scroll page per variant covering Home, AI pipeline, AI Solutions, Case Studies, Commercial Principles, and Finale CTA.

## Commercial positioning (shared across all three)

**No contracts. Performance-based. Proof, not promises.**

- No long contracts, ever
- Performance fee where the outcome is clean
- All-inclusive monthly, ex GST
- Your exact number in writing within 24 hours
- One team, one account manager, no handoffs

## Case studies (shared across all three)

Six placeholder stories across different industries: professional services, SaaS, trades, healthcare, logistics, manufacturing. Each card has a tag, a headline, a metric, and a "read the story" link that goes nowhere until the team drops real stories in.

**Before publish:** replace placeholder copy with real engagement stories, real numbers, and real client names where we have permission. Swap the featured case to the single strongest story.

## The three variants

### 01 · editorial-founder
The safe bet. Carries v3's brand spine forward. Dark navy hero, warm cream body, Instrument Serif italic accents on key phrases. Founder voice. Recommended if we want maximum continuity with AA's current editorial identity.

### 02 · martell-translated
The bolder read. Near-black hero, Space Grotesk, Geist Mono tags, strong contrast, numbers-forward hero. Martell-style "not a dashboard, an outcome" framing translated for Australian B2B. Recommended if we want to signal AA is different from the typical Melbourne agency.

### 03 · service-first-clean
The minimalist read. White canvas, one-sentence hero, three service cards answer "which one sounds like you?" immediately. Grade 6 language. Recommended if the site needs to convert owners who will not stay on a page longer than 90 seconds.

## Preview

From this folder:

```bash
python3 -m http.server 8000
```

Then open:
- http://localhost:8000/01-editorial-founder/
- http://localhost:8000/02-martell-translated/
- http://localhost:8000/03-service-first-clean/

## Version control

Each edit committed to git. To see the history:

```bash
git log --oneline
git diff HEAD~1 HEAD
```

To compare two variants side by side in diff form:

```bash
git diff --no-index 01-editorial-founder/index.html 02-martell-translated/index.html
```

## Team review workflow

1. Walk the team through each variant in order (01, 02, 03).
2. Strongest hero vs strongest case studies vs strongest commercial block — note preferences per section, not per variant.
3. Merge the winning blocks into a final site rather than picking one variant outright. The repo structure supports it.
4. Logos, client names, audited numbers, and Melvin's title still to be added to all three before publish.

## Open items still to resolve

- Real case study content (named or anonymised, with audited numbers)
- Melvin's title in the transparency band
- Why / whether to keep a dedicated AI Solutions page or fold it into the single long-scroll
- Client logo strip (do we have rights, and from which clients)
- Production font: Gilroy once purchased, Inter stands in for now
