# Site audit — Katerina Bischel portfolio

A reflective review of all seven public pages (`index`, `about`, `resume`, `projects`, `research`, `writing`, `contact`), the shared design system, and the project artifacts you handed me. Written as a colleague's read, not a checklist.

---

## 1. The shape of the site

You have built something that is genuinely uncommon for an early-career environmental scientist's portfolio: a single, consistent editorial voice executed across seven pages with a real design system behind it. The "Cartographer's Atelier" theme — Cormorant Garamond for the body, JetBrains Mono for the labels, glass cards with iridescent rim effects, the panorama-with-quote dividers, the `§ Plate` numerals, the MMXXVI Roman dating — is not just decoration. It's a worldview applied evenly. Almost every page reads as if the same person wrote, designed, and proofed it on the same afternoon, which is rare.

The information architecture is also strong. You've made an explicit choice that each page is a different *lens* on the same body of work — Projects shows the build artifact, Research shows the science, Writing shows the craft — and you've told the reader that openly with phrasings like "the writing-craft lens on this document lives on Writing." That's a real editorial decision and it works.

The technical anchors are credible: live ORCID, real Zenodo deposit, working CalCOFI Shiny app, a deployed bilingual River Remedy site, an EPA continuing-ed paper trail. These are not stage props.

So my assessment in one line is: **this site is the upper end of what a graduating M.E.S.M. student typically ships.** Most of the rest of this document is about the small wedge of polish between "very good" and "professionally bulletproof," because that wedge is where hiring decisions actually get made.

---

## 2. What's working

A few things I want to name explicitly so they don't get edited away:

The **specificity** is your real advantage. Lines like "1,436 samples across 46 monitoring stations spanning eight years (2016–2024)" or "mAP50 = 0.745, precision = 0.878, recall = 0.648" or "9-week field season, three daily shifts, randomized site order" are the parts of the site that do scientific work. A peer reading those numbers can engage; a recruiter can verify; a hiring manager can ask about them in an interview. Keep that bar everywhere.

The **cross-linking pattern** ("the build/engineering view of this work lives on Projects") is unusual and good. It signals that you know what you're showing on each page and why.

The **resume page's continuing-education ledger** (PFAS rule implementation, anatoxin cyanobacteria, melioidosis CERCLA decontamination, Green Lab) is a quiet but powerful signal. It says: I take regulatory and applied environmental practice seriously beyond my degree. Most early-career portfolios don't show that.

The **bilingual River Remedy site** is the single strongest item in the whole portfolio. A solo-built English/Spanish analytical site for a transboundary basin study with policy stakeholders downstream is a stronger differentiator than the manuscript-in-prep itself, in my opinion.

The **mentorship narrative** is well-handled: it's named on About, named on Resume, named in the YOLOv8 prose, and not over-claimed. Two undergraduate trainees through a 9-week field season is real and you say so accurately.

---

## 3. The voice tension — the one strategic decision worth being deliberate about

Here is the conversation I'd want to have with you in person before I'd give a recommendation.

The site reads in two voices simultaneously. One is the literary editorial voice: "Chapter VII · Correspondence · MMXXVI", "I read every letter and reply within a tide cycle", "Begin where the watershed bends —", "the diamonds and rules", "starlight, ink, glass, water." The other is the scientific voice: "Spatiotemporal partitioning is modelled in R using a coupled hydrological–geochemical framework", "1,436 samples across 46 monitoring stations", "Kalman-filter occlusion handling, ≥ 3–5 s minimum visit duration".

These are both legitimate voices, but they pull on different audiences:

- **A federal hiring manager** (EPA, USGS, NOAA, state water boards) is going to skim this site in 90 seconds on a Tuesday afternoon. The scientific voice helps them. The "tide cycle" promise and the Roman numeral dating may register as ornamental in a way that doesn't help.
- **An environmental consulting firm** like AMS (your current/incoming employer) probably reads it the same way as a state agency.
- **An academic peer** or a science-communication-focused organization may genuinely love the literary register and read it as taste.
- **A general audience** (a journalist, a policy person, a community partner in Bolivia or Paraguay) may also love it.

You can't fully serve all four at once with the same voice. The good news is the literary scaffolding is mostly *containers* — the `§ Plate` labels, the "Chapter II" eyebrows, the panorama-quote dividers — and those can be dialed up or down without touching the substantive prose underneath them.

My suggestion: **keep the substantive prose as it is, but reduce the literary scaffolding by about 30% across the site.** Concretely:

- Drop a few of the panorama-quote dividers — the site has one between almost every block. Two or three across the whole site would be more powerful than ~10. The current density makes them feel like punctuation rather than emphasis.
- Drop "MMXXVI" from the page headers and footer copyright. Use "2026". A reader on a phone will read that line three or four times across the site and wonder if you're testing them.
- Soften "I read every letter and reply within a tide cycle" on Contact. Either say "within ~24 hours" or just say nothing. You've already replaced the Currently text with "Graduating in June 2026!" — that's the right register.
- Keep the diamond rules, keep the glass, keep the gold. Those are doing real visual work.

This is a 30-minute editorial pass. It would lower the friction for the scan-in-90-seconds audience without losing the readers who like the literary voice.

---

## 4. Scientific soundness & defensibility

I read every page, and your science is stated carefully and with appropriate hedging in almost every place. The Pilcomayo card says "in preparation" — correct. The River Remedy report says "group authorship is attributed inside the document" — correct and humble. The senior thesis names the dissolved-oxygen trade-off alongside the pH win, which is much more persuasive than a clean "alkalinity enhancement worked" claim would have been.

A few small flags:

- **About page, line 613 — "I work at Applied Marine Sciences as an Environmental Scientist…"** Combined with the Resume entry dated "2026 —" and the Contact page note "Graduating in June 2026!", a careful reader will notice you're presenting a current full-time position while also still finishing a master's. If this is a part-time role that converts to full-time post-graduation, or an offer accepted with a start date, it's worth being explicit. Right now I'd probably ask about it in an interview, and you'd want to be the one to choose how that question lands.

- **Pilcomayo manuscript citation — `Bischel, K., and Keller, A.`** This is a real, public claim of authorship order on a manuscript that doesn't exist yet. Make sure Dr. Keller has agreed to that order. Most preprint policies and most advisors are fine with student-first on a thesis-derived manuscript, but this is a place where surface presentation can outpace the actual agreement.

- **Diputada María Ángela Ruíz Farfán presentation.** This is a strong signal — that policymaker engagement landed. But the line is currently a single mention with no date, no co-presenter, no event title, no photo, no link. As written, it reads like a footnote, when it could be one of the strongest items on the Pilcomayo card. (See my "things I want clarification on" section below.)

- **YOLOv8 paper status.** The new prose I helped you write says "a manuscript on the comparison in preparation under Dr. Katja Seltmann and Dr. Chris Evelyn." The Paper Outline draft you sent has co-authorship implied with mentorship from Seltmann/Evelyn, not first-authored under them. If you'll be first-author with Seltmann/Evelyn as co-authors, that's the more defensible phrasing.

- **The "tide cycle" reply promise on Contact** is the only place on the site where you make a service-level claim about your own behavior. Service-level claims are the kind of thing a careful reader will test. If a recruiter sends a note and gets a reply in two business days, that's fine — but they shopped your stated promise against the actual behavior. Either don't make the promise, or make one you can keep.

Otherwise: the science is stated cleanly and the contributions are attributed accurately. That's the most important thing on a site like this and you have it.

---

## 5. Things that will hurt the site right now and should be fixed in the near term

These are concrete and can be batched into a single Claude Code prompt if you want.

**5.1 The Mailchimp campaign-archive link is broken in three places.** It contains `?e=__test_email__&u=05cf4db23a15975cb832e2846&id=3d0ad0cae9` — `__test_email__` is a Mailchimp template placeholder, not a real recipient identifier. Anyone who clicks that link is going to land somewhere weird or get a "this campaign cannot be displayed" page. The link appears in `index.html` (the press strip), `projects.html` (the YOLOv8 card), and `research.html` (the YOLOv8 card). Fix: replace with the publishable Mailchimp campaign URL, which has the form `https://mailchi.mp/<short-id>/<slug>` or `https://us15.campaign-archive.com/?u=…&id=…` *without* the `e=` parameter.

**5.2 The LinkedIn article on writing.html Card 03 is a `href="#"` placeholder** with a TODO comment next to it. Either fill the URL in or remove the card until publication.

**5.3 The 127 MB River Remedy PDF iframe on `research.html` is a performance bug.** Embedding a 127 MB document in an iframe will fail or take minutes to load on most connections, and is unusable on mobile. The same page also has the senior-thesis PDF embedded as an iframe, which is fine because it's smaller. Fix: delete the iframe for the River Remedy PDF and keep the existing "View report (Bren PDF)" external link plus the local download link. The Whitewater plan (37 MB) on the writing page is borderline; I'd watch it but not touch it yet.

**5.4 Two different "primary" emails across the site.**
- Footer (every page): `katerinabischel@amarine.com` (the AMS work address)
- Contact card (top of contact.html): `katerina.bischel@gmail.com`
- Contact colophon (also contact.html): `katerina.bischel@gmail.com`

Pick one and use it everywhere. My recommendation: the AMS address if AMS is your professional identity going forward, or the personal Gmail if you want a stable address that survives any future job change. Just don't use both.

**5.5 Orphan demo pages.** `fishbowl.html` and `donut.html` exist in the deploy but aren't linked from anywhere. They look like 3D experiments. Two questions: (a) are they meant to be in the production deploy, and (b) if yes, should they be linked from Projects with a "side projects" or "experiments" framing? If no, they should be moved to a `_drafts/` subdirectory excluded from the GitHub Pages build.

**5.6 The `ui_kit/` folder is publicly reachable.** Anyone who guesses or stumbles on `katerinabischel.github.io/ui_kit/` will see the design-system documentation. Not a security issue, but it can read as work-in-progress to someone who finds it. Either keep it (some designers like showing the kit) and link to it intentionally, or move it under `_ui_kit/` so GitHub Pages excludes it.

**5.7 Mobile nav fix is still pending** from the earlier CLAUDE_CODE_PROMPT.md. Until that's run, the hamburger menu is invisible on phones. Recruiters and interviewers do open links on phones.

---

## 6. The Projects / Research / Writing repetition you already noticed

You're right that there's redundancy. Concretely:

- **River Remedy report** appears on Projects (Plate 02) and Research (Card 04, post-reorder). The prose overlaps.
- **YOLOv8 model** appears on Projects (Plate 03) and Research (Card 02). The Projects card is brief and the Research card is now substantial — that's the right asymmetry.
- **Whitewater plan** appears on Projects (Plate 04) and Writing (Card 04). Two takes on the same document.
- **River Remedy site** is its own item on Projects (Plate 01) and is referenced from Research (Card 01).

The "lens" framing is internally coherent, but in practice a reader who clicks all three pages reads the same project three times, each time with a one-paragraph reframing followed by a "the [other lens] view lives on [other page]." After the second or third project they start to feel the pattern.

Two ways forward, ordered by how much surgery you want to do:

**Option A (low effort): tighten each page's prose so the lens does real work.** Each lens should genuinely add something the other pages don't say. The build artifact card should be one paragraph that says "this is the deliverable, here's where it lives, here's the technology stack" — period. The science card is the substantive scientific paragraph. The writing card is about register and craft — what made writing this thing hard. Right now the Projects cards are doing all three jobs at the same time, which is what creates the duplication feeling.

**Option B (more effort, more powerful): consolidate to a single "Work" page** where each project gets a single tile that expands or links into all three lenses. This is a real refactor. I wouldn't do it before graduation. But it's the long-term right shape if you're going to keep the lens metaphor.

For now I'd do Option A and revisit Option B in the summer.

---

## 7. Smaller opportunities, in rough priority order

These are nice-to-haves rather than must-fixes.

1. **Add a "What I'm looking for" line on the home page or About page.** Not a full job-search blurb, just one sentence that situates the audience: "I'm finishing my M.E.S.M. in June 2026 and continuing in environmental consulting at Applied Marine Sciences, with continued research collaboration on transboundary water systems." It tells a reader what to do with the site.

2. **The home-page hero subline is doing too much.** "An environmental scientist working at the intersection of field research, data analytics, and scientific storytelling — across hydrochemistry, computer vision for conservation, watershed planning, and interactive data communication." Five things in one sentence is a lot. I'd cut it to three: "Field research, environmental data science, and scientific writing — with current work in hydrochemistry, computer vision for conservation, and watershed planning."

3. **OG images per page could be more distinctive.** Right now most pages share generic panorama backgrounds. Research uses `bee_model.png` (good — distinctive). Projects uses `acid_mine_drainage.png` (good — distinctive). Writing and About use generic panoramas. Swapping in a more specific image per page would make Twitter / Slack / iMessage previews more recognizable.

4. **Add `<meta name="twitter:card">` etc. to every page**, not just the home page. The new prompt added Twitter card tags to `index.html`. Doing the same on the other pages means link previews look like landscape image cards instead of small thumbnails everywhere they're shared.

5. **Quantify the YOLOv8 mentorship outcome.** The Resume entry says you mentored two undergraduate trainees and the About page says the same. If either trainee produced a deliverable (a poster, a phenology dataset, an in-progress paper), say so by name on the YOLOv8 card. "Mentored two undergraduates whose phenology side project [X]" is one line that turns mentorship from a soft claim into a hard one.

6. **Add a small "Selected publications & deposits" section to About or Resume.** Right now the manuscript and the Zenodo deposit are findable through Research, but they don't appear in the resume's documents. A reader who downloads the resume gets a story that's missing the in-prep manuscript and the deposited dataset.

7. **Color contrast.** A few of the gray-on-blue passages (e.g., footer copyright in `aurora-3` at opacity 0.55) are at or below WCAG AA contrast. Worth one pass through with a contrast checker. Less for compliance; more because some interview committees actually grade portfolios on accessibility.

8. **Skills page is good but flat.** Each chip is just a label. If you want the chip cloud to do more work, link a couple of the high-value chips (e.g., "YOLOv8" → research.html#pollinator card, "Watershed Management" → projects.html#whitewater card). Most readers won't click; the ones who do will see your taxonomy is real.

9. **Drop `target="_blank"` from internal navigation links.** I didn't find any of these, but you have a lot of `target="_blank" rel="noopener noreferrer"` on external links — that's correct usage and worth keeping.

10. **Title tag style is inconsistent across pages.** You have `Projects | Katerina Bischel`, `Resume · Katerina Bischel` (with a middle-dot), `About · Katerina Bischel`, and `Katerina Bischel` (home). Pick one separator (probably ` | `) and apply it consistently. Tiny but noticeable in browser tabs.

---

## 8. Things I'd like clarification on before I'd recommend any prose changes

Listed in priority order. None of these is urgent; all of them would meaningfully improve the site if you handed me an answer.

**8.1 AMS employment status.** Is the Environmental Scientist position at AMS:
- (a) currently active part-time alongside your master's,
- (b) an offer accepted with a post-graduation start, or
- (c) something else?

This affects how about.html line 613 should be phrased and how the Resume's "2026 —" entry should read.

**8.2 The Diputada Ruíz Farfán presentation.** I want a date, a venue (UCSB visit specifically — campus location?), a co-presenter or audience description, and any photo or news clip. As-is it's a footnote on the Pilcomayo card. With one paragraph of context it becomes one of the strongest items in the whole portfolio. (Policy reach is rare for graduate work; the site should make it visible.)

**8.3 The YOLOv8 manuscript's actual authorship order, status, and target venue.** "A manuscript on the comparison in preparation under Dr. Katja Seltmann and Dr. Chris Evelyn" is the safe phrasing. If you'll be first author with Seltmann/Evelyn as co-authors, that's a stronger claim and we should say so. Also: any target journal, any submission timeline?

**8.4 The LinkedIn biological-waste-treatment article.** Has it been published? If yes — the URL. If no — the timing for publication. Right now the card is on the site with a `#` href, which is a worse signal than not having the card at all.

**8.5 The Cheadle Center "feature article."** The Mailchimp link is broken (see §5.1). Do you have the canonical permalink for that newsletter feature? Even better if it's republished somewhere not behind a campaign-archive URL (a blog, a PDF, a UCSB news page).

**8.6 The CalCOFI dashboard's authorship and intent.** Did you build it solo? Was it a class project, an extension of one, or independent? The Projects card just says "An interactive R Shiny application built on NOAA CalCOFI oceanographic survey data" — the framing is fine but the context isn't there. Even one sentence ("built for ESM XXX as a coursework project") would help.

**8.7 The senior thesis dataset.** The thesis claims a MANOVA across pH, dissolved oxygen, conductivity, and salinity using YSI and pH meters. Was the underlying dataset deposited anywhere (Zenodo, Dryad, Figshare)? If yes, link it. If no, that's something we could do as a small project that adds reproducibility to a four-year-old undergraduate thesis without rewriting it.

**8.8 The fishbowl and donut pages.** Are these meant to be portfolio pieces, abandoned drafts, or personal experiments? Different answers lead to different fixes (link them, delete them, or hide them from the build).

**8.9 What's the audience you most want this site to serve?** This is the meta-question behind everything else. The literary voice serves one audience; the scientific voice serves another; the consulting-firm voice serves a third. You don't have to pick one, but knowing which one is "first among equals" would let me give you sharper recommendations.

---

## A quick note on what NOT to change

- The design system. Keep it. It's the most cohesive thing about the site.
- The cross-linking pattern. The "lens" framing is good even when the prose around it is repetitive.
- The specific scientific numbers. Every one of those numbers is doing work.
- The continuing-education ledger on Resume. Many early-career portfolios skip these. Yours doesn't, and that matters.
- The mentorship claim. It's stated accurately and at the right scale.
- The voice of the substantive prose. It's the literary scaffolding I'd dial back, not the actual paragraphs.

---

If you want, I can turn any of the §5 fixes into a Claude Code prompt the same way I did the mobile-nav fix and the content updates. The two I'd start with are the broken Mailchimp link (replace it across all three pages) and the River Remedy iframe (delete it).
