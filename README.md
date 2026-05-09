# THE RECKONING

> A Manifesto of Calm Fury · May 2026

```
─────────────────────────────────────────────────────────────────
 A documented, sourced, unapologetic reckoning with the fall of
 American democratic norms — built on court verdicts, peer-reviewed
 political science, and Gallup data.

 No hysteria. Only truth. Verify everything.
─────────────────────────────────────────────────────────────────
```

→ **Read the manifesto:** <https://calmfury-docs.github.io/the-reckoning/>

---

## § I.  WHAT THIS IS

A single-page, self-contained HTML document making one argument across six
chapters: that the deterioration of American democratic institutions in 2025–2026
is not opinion, not partisan framing, and not exaggeration — it is a pattern that
has been *measured, ruled on, and published* by independent institutions whose job
is precisely to measure such things.

The document holds itself to a single standard: **every numeric claim, legal
finding, and institutional statement is traceable to a primary source.** Where a
claim could not be sourced, it was rewritten or removed.

## § II.  WHAT THIS IS NOT

```
NOT  a neutral journalistic account
NOT  an argument from authority — every claim is independently verifiable
NOT  written for engagement metrics
NOT  written to comfort either tribe
NOT  written in haste
```

It has a clear point of view. It says so, in the introduction, before any
substantive claim is made. The point of view is held by the human who initiated
the project; the AI's role was to ensure that point of view was expressed with
sufficient factual integrity that a skeptic could follow every citation and
arrive, on their own, at the same conclusions.

## § III.  METHODOLOGY

```
01.  RAW HUMAN VOICE        Anger as compass heading, not noise to suppress.
02.  RHETORICAL DISCIPLINE  Strip hysteria without stripping fire.
03.  SOURCE VERIFICATION    Every claim → primary source, or rewrite/remove.
04.  SOURCE HIERARCHY       (1) court rulings  (2) peer-reviewed institutional
                            reports  (3) major verified journalism. Opinion
                            labeled as opinion.
05.  BOUNDARIES HELD        AI refused certain framings — not to protect power,
                            but because precision is more dangerous to it.
06.  FULL TRANSPARENCY      Methodology disclosed in the document itself.
```

The full version of this methodology, including the rationale for each step, is
written into the introduction of the manifesto itself — not buried in a footnote.

## § IV.  PRIMARY SOURCES

Every institution cited can be read directly. Do not take this document's
characterization on faith; verify against the originals.

**Democracy & Governance Indices**
- V-Dem Institute, *Democracy Report 2026: Unraveling the Democratic Era?* — University of Gothenburg
  <https://www.v-dem.net/documents/75/V-Dem_Institute_Democracy_Report_2026_lowres.pdf>
- Freedom House, *Freedom in the World 2026: The Growing Shadow of Autocracy*
  <https://freedomhouse.org/report/freedom-world>
- Pew Research Center, *Multiple Indicators Show a Decline in the Health of America's Democracy in 2025* (April 2026)
  <https://www.pewresearch.org/short-reads/2026/04/15/>
- The Century Foundation, *U.S. Democracy Meter 2025* (January 2026)
- Reporters Without Borders, *World Press Freedom Index 2026*
- Toda Peace Institute, *Policy Brief: Democratic Resilience in the United States* (July 2025)

**Court Records**
- *People of the State of New York v. Donald J. Trump* — Manhattan Supreme Court, 34 felony counts, May 30, 2024
- *Carroll v. Trump* — S.D.N.Y. jury verdict, May 2023
- *Carroll v. Trump (defamation)* — 2nd Circuit affirmed in full, September 8, 2025 (No. 24-644)
- *Inspectors General firings ruling* — U.S. District Judge Ana C. Reyes, September 24, 2025

**Polling & Public Opinion**
- Gallup World Poll — *China Edges Past U.S. in Global Approval Ratings* (April 2026)
- Gallup International End-of-Year Global Survey (January 2026)

**Congressional & Legislative Record**
- Senator Tammy Duckworth — Statement on Military Officer Purges (April 2025)
- Inspector General Act of 1978 — 5 U.S.C. App.

**Scholarly Commentary**
- Ruth Ben-Ghiat (NYU) — On Project 2025 as authoritarian blueprint (May 2024)
- Levitsky & Way — *Competitive Authoritarianism* framework

A complete in-document bibliography is at the foot of the manifesto.

## § V.  HOW TO VERIFY

If you read one claim and want to check it:

```
1.  Find the claim in the document.
2.  Note the source citation immediately following it.
3.  Open the source. Read the original.
4.  If our characterization is wrong, file an issue here.
```

Disagreement based on the primary sources is exactly the engagement this project
was designed to invite. Disagreement that bypasses the sources is not engagement;
it is performance.

## § VI.  TECHNICAL

```
SITE         Single-page HTML document, no framework, no build step.
HOSTING      GitHub Pages, served from /main branch root.
DEPENDENCIES Google Fonts (Playfair Display, Courier Prime, Bebas Neue).
             No JavaScript framework. ~10 lines of vanilla JS for fade-in.
ACCESSIBILITY Single document, semantic HTML, dark color scheme declared,
             color contrast AA on body text.
SEO          Open Graph + Twitter Card + JSON-LD Article schema.
             Sitemap and robots.txt at site root.
LICENSE      Code: MIT.  Content: CC BY 4.0.
```

### File map

```
/
├── index.html      The manifesto. Self-contained, no build step.
├── preview.png     1200x630 social-share card (og:image, twitter:image).
├── robots.txt      Permits all crawlers; references sitemap.
├── sitemap.xml     Single-URL sitemap.
├── 404.html        Custom 404 maintaining site aesthetic.
├── README.md       This file.
├── CHANGELOG.md    Version history.
├── LICENSE-CODE    MIT — covers any code in this repository.
└── LICENSE-CONTENT CC BY 4.0 — covers the manifesto text and design.
```

### Local preview

```bash
python3 -m http.server 8000
# → http://localhost:8000/
```

That is the entire toolchain.

## § VII.  PROVENANCE

Built collaboratively between a human who refused to look away and Claude, an AI
assistant developed by Anthropic. The collaboration is disclosed in the document
itself, not buried.

This disclosure is not a disclaimer. It is a demonstration: an AI was given free
rein to assist in writing a political manifesto critical of a sitting government,
and its contribution was not to radicalize the argument but to discipline it into
something that cannot be easily refuted. That is not a limitation of the
collaboration — it is the feature being modeled.

## § VIII.  LICENSE

```
CONTENT   Manifesto text, design, preview card .........  CC BY 4.0
CODE      HTML/CSS/JS, build scripts (if any) ..........  MIT
```

You are encouraged to translate, excerpt, remix, embed, and republish — including
commercially — provided you credit the source and link back. This document was
built to spread.

## § IX.  CITE THIS

```
"The Reckoning — A Manifesto of Calm Fury 2026."
calmfury-docs/the-reckoning. Accessed [date].
https://calmfury-docs.github.io/the-reckoning/
```

---

```
                              ◇ ◇ ◇
        TRUTH REQUIRES NO AMPLIFICATION. ONLY REPETITION.
                              ◇ ◇ ◇
```
