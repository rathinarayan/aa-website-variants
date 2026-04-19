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

## The eight variants

### 01 · editorial-founder
The safe bet. Carries v3's brand spine forward. Dark navy hero, warm cream body, Instrument Serif italic accents on key phrases. Founder voice. Recommended if we want maximum continuity with AA's current editorial identity.

### 02 · martell-translated
The bolder read. Near-black hero, Space Grotesk, Geist Mono tags, strong contrast, numbers-forward hero. Martell-style "not a dashboard, an outcome" framing translated for Australian B2B. Recommended if we want to signal AA is different from the typical Melbourne agency.

### 03 · service-first-clean
The minimalist read. White canvas, one-sentence hero, three service cards answer "which one sounds like you?" immediately. Grade 6 language. Recommended if the site needs to convert owners who will not stay on a page longer than 90 seconds.

### 04 · data-forward (Recommended for team review)
The strongest variant for conversion. Built on real AA data. Three shifts from 01-03:
- **Decision-maker data elevated to a hero pillar.** 42 roles, 12 functions, 3 verification sources. "We do not buy databases. We build them." Most agencies lease a list and spray a template — AA's edge is that every contact is verified before the first message goes out.
- **Pay-on-results commercial with skin-in-the-game on tools.** Client pays only when a lead converts. Client covers third-party tool costs (inbox warmup, LinkedIn seats, AI voice minutes, CRM seats). AA carries outcome risk, client carries tooling cost. Fair on both sides.
- **Twelve B2B niches as the case studies section**, sourced from AA's real active and historical engagement book (79 verified clients). Each niche block has a two-line description of the decision-makers AA targets and the outcomes. Business Services and Operations featured (29 active clients, AA's largest niche).

Scale claim updated to the defensible version: **79+ Australian B2B clients across 12 industries since 2021**. See variant README for the decision on keeping vs dropping the "thousands" language elsewhere.

### 05 · human-first (Most polished, current front-runner)
The most complete variant. Eight shifts from 04:
- **Three hero variations stacked** for team review (results-led, pain-led, proof-led). Pick one at launch.
- **Human SDR pulled forward to section 01.** The team is the foundation. AI multiplies what they do.
- **AI is no longer confusing.** A dedicated "Two different AIs" explainer separates AI Outbound (bundled with SDR) from AI Solutions (separate engagement).
- **"Hundreds of Australian businesses since 2021"** as the scale claim (79+ active, lifetime defensibly in the hundreds).
- **20 B2B niches** as the case studies grid (up from 12 in v4). Added SaaS, Legal, Construction, Logistics, Energy, Travel, Media, Events.
- **Collaboration, not an agency** as a dedicated section. Partnership principles: your wins are our wins, shared goals, skin in the game both sides, one Slack.
- **Authentic founders' awards strip** — BRW Fast Starters, Deloitte Technology Fast 50, Deloitte Fast 50 Finalist, Ernst & Young, Fast 100, Fast Starters. Real recognition received by the founding team.
- **Client video testimonials section** — six placeholder cards ready to hold the real videos migrated from the current automateaccelerator.com.

This is the variant to walk the team through first.

### 06 · proof-layer (v5 + credibility blocks)
Exactly v5 with two additions, nothing else moved:
- **Authentic founders' awards strip** after the team pillar — BRW Fast Starters, Deloitte Technology Fast 50, Deloitte Fast 50 Finalist, Ernst & Young, Fast 100, Fast Starters.
- **Six-card client video testimonials section** between Industries and Principles, placeholder slots ready for migrating the real videos from the current automateaccelerator.com.

Pick v6 when trust needs to work harder on the page. Pick v5 when you want the same architecture leaner.

### 07 · multipage (First multi-page variant, recommended for team review)
First variant that breaks the long-scroll format. Six dedicated pages built from first principles to fix the AI story:
- **Home** (`index.html`) — overarching pitch, conversion-focused, under 2,500 words
- **Services** (`services.html`) — two products: Growth engine + AI Solutions
- **AI** (`ai.html`) — the page that kills the AI confusion. Opens with "AI lives in two places at AA. Inside our Growth engine, where it multiplies the SDR team. And as AI Solutions, standalone. That is the whole story."
- **Data** (`data.html`) — AA's technical edge as a full page (42 roles, 12 functions, 3 sources, workflow, them-vs-us)
- **Case Studies** (`case-studies.html`) — featured case + 20-niche playbook + 6 video slots + authentic founders' awards
- **Our Team** (`team.html`) — founders, Melbourne + AA-owned India, partnership framing

**Key architectural decision:** AI is a capability layer inside Growth, plus a standalone engagement (AI Solutions). No third AI service bucket. No AI Outbound sold separately. This is the answer to Narayan's repeated question "how are you blending AI?" across v1-v6.

StoryBrand spine threaded invisibly across all six pages. Reader lands on any page and still feels the arc.

To preview: `open index.html` in the 07-multipage folder.

### 08 · icp-workshop (v07 + Data/ICP Workshop positioning)
Exactly v07 with one deliberate change: the Data page worked example becomes a proper structured ICP card, and the **Data and ICP Workshop** is positioned as the human-led ritual that starts every engagement. Three-step workshop process (Discovery, Codify, Approve and extract), structured ICP card with labelled fields (inclusion, exclusion, hot signal, cold signal), volume target badge. Also referenced on Home and Services so the Workshop appears wherever the Growth engine is introduced.

To preview: `open data.html` in the 08-icp-workshop folder.

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
