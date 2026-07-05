# PM Portfolio Plan
*Based on analysis of anthonysaltarelli.com*

## 1. What makes the reference site work

**Structure (3-bucket model).** The site splits everything into three clear categories, which map exactly to how recruiters evaluate PMs:

1. **Work** — one page per employer, showing real shipped features (Grow Therapy, SageSpot, Squarespace, SeatGeek)
2. **Side Projects** — self-initiated apps that prove builder instincts (Braise, Chin Up!, etc.)
3. **Case Studies** — speculative product exercises on well-known companies (Uber Eats, PayPal) that show product thinking even without insider access

**Homepage flow** (single scrolling page):
1. Photo + one-line positioning statement: *"I'm Anthony, a Product Manager obsessed with design, user experience, and growth"*
2. Experience timeline — company → title → years, each linking to a detail page
3. Optional offer/CTA section (his coaching business)
4. About me — narrative bio: origin story → career arc → current role → mission → interests
5. Work cards → Side Project cards → Case Study cards, each with a 1–2 sentence blurb and a "View" link
6. Footer with full sitemap + social links (LinkedIn, YouTube, Medium, Instagram, TikTok)

**Detail page template** (e.g., /grow-therapy):
- Hero image + company logo + tenure dates
- One-line role summary
- Then one section per feature/project: feature name (H2), 2–4 sentence description of the problem and approach, followed by screenshots/mockups

**Style traits:**
- Minimal, whitespace-heavy, image-forward
- Casual first-person voice with personality (emoji in headline, italics for emphasis)
- Every claim is concrete: "40+ consumer features," "15,000 downloads"
- Consistent card pattern: image → title → blurb → CTA link
- Social links repeated in header, homepage, and footer

## 2. Your site structure

```
Home (index.html)
├── Hero: photo + positioning statement
├── Experience timeline
├── About me
├── Work section (cards → detail pages)
├── Side Projects section (cards)
├── Case Studies section (cards)
├── Contact / footer
└── Detail pages (one per company/project, shared template)
```

Since goal is a mix (job hunting + clients + personal brand):
- Lead with a positioning statement that names your specialty (e.g., "PM focused on X")
- Include a light "Work with me" or contact CTA
- Link out to wherever you publish content (LinkedIn, Medium, YouTube)

## 3. Content you need to gather

Per **employer**: company, title, dates, 2–4 shipped features each with problem → what you did → outcome (metrics if possible), 2–3 screenshots/mockups per feature.

Per **side project**: name, one-line pitch, story (why you built it, what happened), screenshots, downloads/users if any.

Per **case study** (aim for 2–3): pick a well-known product, follow a framework — problem/opportunity → user research → solution concept → mockups → success metrics. These are the highest-leverage pages if your work experience is thin or under NDA.

Plus: professional photo, short bio (5–6 paragraphs following origin → arc → now → mission → personal), social links, contact method.

## 4. Build roadmap

**Phase 1 — Skeleton (this session):** single-file HTML prototype with all homepage sections and placeholder content. Free hosting via GitHub Pages or Netlify.

**Phase 2 — Content:** replace placeholders with your real experience; write the bio and blurbs; collect/create screenshots (Figma mockups work well for case studies).

**Phase 3 — Detail pages:** build the shared detail-page template, one page per company/project. Start with your strongest 2–3; "Coming soon" is acceptable for the rest (the reference site does this).

**Phase 4 — Polish & launch:** custom domain (~$12/yr), favicon, Open Graph meta tags for link previews, mobile check, then share on LinkedIn.

## 5. Tips specific to PM portfolios

- Metrics beat descriptions. "Increased booking conversion 12%" > "worked on booking flow."
- Mind NDAs — describe problems and outcomes without confidential numbers; use recreated mockups instead of internal screenshots.
- Case studies on famous products let you show full product process with zero confidentiality risk.
- Keep blurbs to 1–2 sentences on the homepage; depth lives in detail pages.
- A portfolio that exists beats a perfect one. Ship Phase 1–2, iterate.
