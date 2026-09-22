# AMDM 26~27 — Static Mirror

Static mirror of `https://sites.google.com/view/amdm21-22` (Google Sites, owned by the teacher), built 2026-09-22 for use where Google Sites is blocked. **Not published to GitHub** — local files only.

## Page mapping (14 HTML pages + 1 CSS)

| File | Source page |
|---|---|
| `index.html` | Home |
| `welcome-20262027.html` | Welcome, 2026~2027 |
| `course-introduction.html` | Course Introduction |
| `course-outline-and-math-policies.html` | Course Outline & Math Policies |
| `questioning-and-prompting-skills.html` | Questioning & Prompting Skills |
| `rubrics-with-sample-writing.html` | Rubrics with sample writing |
| `math-projects.html` | Math Projects |
| `unit-1-number-and-operations.html` | Unit 1- Number and Operations |
| `unit-2-geometric-ratios.html` | Unit 2- Geometric Ratios |
| `unit-3-function-models-decision-making.html` | Unit 3- Function Models & Decision Making |
| `unit-4-probability.html` | Unit 4- Probability |
| `unit-5-statistics.html` | Unit 5- Statistics |
| `unit-6-finance.html` | Unit 6- Finance |
| `unit-7-networks-and-graphs.html` | Unit 7- Networks and Graphs |

All pages share one `styles.css` and one common responsive navigation bar in the same fixed page order, with `aria-current="page"` on the current page and a skip link.

## Embeds and links

- **YouTube:** every video is embedded via `https://www.youtube-nocookie.com/embed/VIDEO_ID` with `loading="lazy"` and a descriptive `title`.
- **Google Drive/Docs:** each document/file uses the exact `/preview` URL found on the source page (docs.google.com or drive.google.com), embedded in an iframe with a title, plus an "Open in Google Drive" link right next to it. No document URL was guessed.
- **Images:** original `sites.google.com/sitesv-images-rt/...` URLs are hotlinked (never downloaded) with `loading="lazy"` and descriptive `alt` text.
- **External links:** copied from the source page as shown. Where only a domain was indicated, the verified homepage/article was used (see "Unresolved / approximated links" below).
- **No trackers, no external fonts.**

## Videos embedded

- Home: `V6yixyiJcos` (welcome), plus two designated PDF links
- Unit 1: `0YzvupOX8Is`, `3O0WbXg6rJo`, `FTtrOUUJUZQ`, `JQRoAiVyR0k`, `Uc2Tm4Lr7uI`, `is2mZG3dXJA`, `liyFKUFCQno`, `qGTYSAeLTOE`, `slFqL86q3EA` (9 IDs)
- Unit 2: `_syV6cDk7Lg`, `uyKvSe6Ltgs`
- Unit 3: `NXMVraoAoWg`, `sjIvUz7T0zY`, `C-iEq79Em1s`, `Gytu2rI8_lI`, `M0yhHKWUa0g`, `unxPj_U2CkQ`
- Unit 4: no YouTube embeds appear on the source page
- Unit 5: `zjHfAhcU6kE`, `j6ftiC2o6O4`, `ugd4k3dC_8Y`, `fHxfoQsc8hc`
- Unit 6: `IKihYinXmIg`, `hDJZ6m59ugk`

## Documents embedded (Docs/Drive /preview)

- Unit 1: 3 Docs + 4 Drive files
- Unit 2: 1 Doc
- Unit 3: 2 Docs
- Unit 4: 4 Docs
- Unit 5: 2 Docs + 2 Drive files
- Unit 6: 1 Drive file
- Course Outline, Rubrics, Math Projects: provided Drive/Docs `/preview` URLs with fallback "Open in Google Drive" links

## Placeholders — owner must add sharing links (7 required + extras)

Exact format used on the pages: `[Document: <name> — owner to add sharing link]`

**The 7 designated ones:**
1. Unit 2: `L1 trig ratios`
2. Unit 2: `L4 Area of a Triangle`
3. Unit 2: `L5 The Cosine Rule`
4. Unit 4: `B-Theoretical Probability.docx`
5. Unit 5: `I-Continuous Data & Frequency Distribution Tables`
6. Unit 5: `A-Correlation.docx`
7. Unit 6: `L8- Depreciation good`

**Extra placeholders (names appeared on the source page but no URL could be recovered):**
- Unit 1: `AMDM Classroom Activity Rubric(20~21).docx`, `sample essay(Jane Doe).docx`
- Unit 1: "The video link" noted but the ID could not be recovered
- Unit 3: `L1- Functions, Domain and Range`, `L2-Function Notation`

## Notes and gaps

- **Home:** keeps the original welcome video `V6yixyiJcos` and the two designated PDF links.
- **Unit 3:** two videos from the original page were excluded — "The Marshmallow Study Revisited" (private) and "The True Story Of Ronald Read" (unplayable). This is noted on the page.
- **Unit 7:** the source page currently contains only the table of contents; no lesson content exists to mirror. Noted on the page.
- **Text fidelity:** English source text is preserved as-is. Only obvious extraction spacing glitches were repaired (`202 6` → `2026`, `Clas s` → `Class`, `No tations` → `Notations`, etc.). Anything ambiguous (e.g., "Compliments" in probability, "Vendiagram") was left untouched.
- **Unresolved / approximated links:** where the source page linked a site without showing the exact article URL, the verified domain homepage was used rather than guessing:
  - mathinsight.org glossary links (functions, linear function, independent variable, exponent, dynamical systems, simple models of bacteria growth) → `https://mathinsight.org`
  - www.superprof.co.uk word-problems link → `https://www.superprof.co.uk`
  - www.google.com example link → `https://www.google.com`
  - www.mathsisfun.com example link → `https://www.mathsisfun.com`
  - Experian article links without exact URLs (charge cards, Experian Boost, prospective employers, building up good credit) → `https://www.experian.com`
  - credit.com links (three major credit reporting agencies, free annual credit report, free credit score through Credit.com) → `https://www.credit.com`
  - consumerfinance.gov links (debt sent to collection, foreclosure, bankruptcy) → `https://www.consumerfinance.gov`
  - TVM calculator: exact URL `https://www.fncalculator.com/financialcalculator?type=loanCalculator`
- Verified article URLs in use: Khan Academy ratio/intro, basic trigonometry, equivalent ratios, zeroth power, Pythagorean theorem; Experian "what is a credit report", "what is revolving credit", "what is credit?"; CFPB "what is a credit score".
- All pages include `title` on iframes, `alt` on images, no trackers, no external fonts, no guessed document URLs.
