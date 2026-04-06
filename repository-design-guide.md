# Leaders Tribe — Repository Design Guide & Brand Identity

**Excel for Data Analysis for Women**
*Visual Design Guidance for GitHub Repository and GitHub Pages*

---

## Part A: Proposed Repository Structure

```
leaders-tribe-excel-program/
│
├── README.md                          ← Public entry point; project overview
├── LICENSE                            ← CC BY-NC 4.0 license
├── CONTRIBUTING.md                    ← Contribution guidelines
├── .gitignore                         ← Ignore OS/temp/build files
│
├── docs/                              ← All public-facing documentation
│   ├── index.md                       ← GitHub Pages homepage
│   ├── about.md                       ← Leaders Tribe organization profile
│   ├── program-overview.md            ← Full program rationale and structure
│   ├── level-1.md                     ← Level 1 Beginner curriculum guide
│   ├── level-2.md                     ← Level 2 Intermediate curriculum guide
│   ├── train-the-trainer.md           ← TTT requirements, steps, and tips
│   ├── facilitator-resources.md       ← Facilitation guidance and pacing
│   ├── monitoring-and-evaluation.md   ← M&E framework and metrics
│   └── contact.md                     ← Contact information
│
├── level-1/                           ← All Level 1 (Beginner) materials
│   ├── slides/                        ← Session slide decks (upload manually)
│   │   ├── session-1-intro-to-excel.pptx
│   │   ├── session-2-data-entry-sorting.pptx
│   │   ├── session-3-formulas-functions.pptx
│   │   ├── session-4-if-statements.pptx
│   │   ├── session-5-charts-visualization.pptx
│   │   ├── session-6-summarization-formatting.pptx
│   │   ├── session-7-guided-practice.pptx
│   │   └── session-8-capstone-briefing.pptx
│   ├── workbooks/                     ← Practice Excel workbooks (upload manually)
│   │   ├── week1-practice-workbook.xlsx
│   │   ├── week2-formulas-workbook.xlsx
│   │   ├── week3-charts-workbook.xlsx
│   │   └── week4-capstone-template.xlsx
│   └── assessments/
│       ├── pre-assessment-level1.md   ← (copy from templates/)
│       └── capstone-rubric-level1.md  ← (copy from templates/)
│
├── level-2/                           ← All Level 2 (Intermediate) materials
│   ├── slides/                        ← Session slide decks (upload manually)
│   │   ├── session-1-data-cleaning.pptx
│   │   ├── session-2-data-validation.pptx
│   │   ├── session-3-lookup-functions.pptx
│   │   ├── session-4-conditional-functions.pptx
│   │   ├── session-5-pivottables.pptx
│   │   ├── session-6-dashboards.pptx
│   │   ├── session-7-real-world-practice.pptx
│   │   └── session-8-capstone-briefing.pptx
│   ├── workbooks/                     ← Practice Excel workbooks (upload manually)
│   │   ├── week1-cleaning-validation-workbook.xlsx
│   │   ├── week2-lookup-conditional-workbook.xlsx
│   │   ├── week3-pivot-dashboard-workbook.xlsx
│   │   └── week4-capstone-template.xlsx
│   └── assessments/
│       ├── pre-assessment-level2.md
│       └── capstone-rubric-level2.md
│
├── datasets/                          ← All CSV practice datasets
│   ├── level-1/
│   │   ├── contact-list.csv
│   │   ├── entrepreneurs-sales-messy.csv
│   │   ├── entrepreneurs-sales-clean.csv
│   │   ├── household-budget.csv
│   │   ├── student-performance.csv
│   │   ├── attendance-sheet.csv
│   │   ├── savings-group.csv
│   │   └── capstone-level1.csv
│   └── level-2/
│       ├── ngo-beneficiaries-messy.csv
│       ├── ngo-beneficiaries-clean.csv
│       ├── data-validation-practice.csv
│       ├── student-info.csv
│       ├── exam-scores.csv
│       ├── sales-conditional.csv
│       ├── program-outcomes-pivot.csv
│       ├── dashboard-practice.csv
│       └── capstone-level2.csv
│
├── train-the-trainer/                 ← All TTT tools and templates
│   ├── ttt-reflection-report-template.md
│   ├── ttt-session-plan-template.md
│   ├── ttt-attendance-log-template.csv
│   └── ttt-checklist.md
│
├── facilitator-resources/             ← Facilitation support materials
│   ├── facilitation-guide-level1.md   ← Upload manually or create from docs
│   ├── facilitation-guide-level2.md
│   └── qa-support-notes.md            ← Common participant questions & answers
│
├── templates/                         ← Reusable forms and templates
│   ├── pre-assessment-template.md
│   ├── capstone-rubrics.md
│   ├── attendance-log-template.csv
│   └── follow-up-survey-template.md
│
├── workbooks/
│   └── capstone/                      ← Blank capstone templates (Excel)
│       ├── capstone-template-level1.xlsx   ← Upload manually
│       └── capstone-template-level2.xlsx   ← Upload manually
│
└── assets/                            ← Brand and visual assets
    ├── leaders-tribe-logo.png         ← Upload manually
    ├── leaders-tribe-logo-white.png   ← Upload manually (white version for dark backgrounds)
    └── brand-colors.md                ← Color reference guide
```

---

## Part B: Brand & Design Guidance

### Logo Analysis

The Leaders Tribe logo features:
- A **feather/quill** motif with a warm gradient from **flame orange at the tip** through **coral/red** to **rich purple** at the base
- Script lettering **"Leaders Tribe"** in **deep purple/violet**
- A **black background** in the source logo (use as dark variant; strip background for light backgrounds)

The logo communicates: elegance, creativity, warmth, and feminine strength. The feather is both a writing instrument and a symbol of lightness, voice, and freedom — well-suited to a program about data storytelling.

---

### Proposed Color Palette

These colors are derived from the logo and designed to work as a cohesive, warm, empowering brand system.

#### Primary Colors

| Name | Hex | Usage |
|---|---|---|
| **Tribe Purple** | `#7B2D8B` | Primary brand color; headings, buttons, section headers |
| **Flame Orange** | `#F4811F` | Accent; call-to-action buttons, highlights, icons |
| **Deep Coral** | `#D94F3D` | Secondary accent; badges, alerts, important notices |

#### Secondary / Supporting Colors

| Name | Hex | Usage |
|---|---|---|
| **Warm Ivory** | `#FAF7F2` | Page background; warm, non-clinical white |
| **Soft Lavender** | `#EDE4F5` | Section backgrounds; alternating panels, table header fills |
| **Charcoal Text** | `#2C2C2C` | Body text; readable but softer than pure black |
| **Mid Grey** | `#6B6B6B` | Secondary text; captions, footnotes, metadata |
| **Light Border** | `#E0D6EB` | Table borders, dividers, card outlines |

#### Dark / Contrast Colors

| Name | Hex | Usage |
|---|---|---|
| **Rich Black** | `#1A1A1A` | Logo backgrounds; dark hero sections |
| **Deep Plum** | `#3D1A52` | Footer backgrounds, dark nav bars |

---

### Typography Recommendations

#### Headings
- **Font:** `Georgia` or `Playfair Display` (Google Font — import via `@import url`)
- **Weight:** Bold
- **Color:** Tribe Purple (`#7B2D8B`) for H1/H2; Charcoal Text for H3/H4
- **Feel:** Elegant, feminine, trustworthy

#### Body Text
- **Font:** `Lato`, `Open Sans`, or `system-ui` (web-safe fallback)
- **Size:** 16px base, 1.6 line-height
- **Color:** Charcoal Text (`#2C2C2C`)
- **Feel:** Readable, warm, approachable

#### Code / Data Labels
- **Font:** `Courier New` or `Consolas` (monospace)
- **Background:** Soft Lavender (`#EDE4F5`)
- **Color:** Deep Plum (`#3D1A52`)

#### Recommended Font Stack (CSS)
```css
/* Headings */
font-family: 'Playfair Display', Georgia, serif;

/* Body */
font-family: 'Lato', 'Open Sans', Arial, sans-serif;

/* Code */
font-family: 'Courier New', Consolas, monospace;
```

---

### Logo Placement Recommendations

| Location | Usage |
|---|---|
| **README.md header** | Center-align the logo at the top, above the program title. Use the transparent/PNG version. Size: ~200px wide. |
| **docs/index.md (GitHub Pages homepage)** | Feature prominently in the hero section or navigation header |
| **Navigation banner (GitHub Pages)** | Use a small version (40–60px height) in the top-left nav bar, linked to the homepage |
| **Footer** | Repeat small logo in footer alongside contact info and copyright |
| **Slide decks** | Top-right corner of each slide; bottom bar on title slides |
| **Capstone templates** | Top-right of the workbook header row |

**For the README**, add this at the very top of README.md:
```markdown
<p align="center">
  <img src="assets/leaders-tribe-logo.png" alt="Leaders Tribe Logo" width="200"/>
</p>
```

---

### GitHub Pages Styling (Jekyll `_config.yml` suggestion)

If you activate GitHub Pages with the **Minima** or **Cayman** theme, you can override styles using a custom CSS file:

```yaml
# _config.yml
title: Excel for Data Analysis for Women
description: A Leaders Tribe Training Program
theme: minima
url: "https://[your-github-username].github.io"
baseurl: "/leaders-tribe-excel-program"
```

Create `assets/css/style.scss`:
```scss
---
---
@import "{{ site.theme }}";

:root {
  --color-purple: #7B2D8B;
  --color-orange: #F4811F;
  --color-coral: #D94F3D;
  --color-ivory: #FAF7F2;
  --color-lavender: #EDE4F5;
  --color-text: #2C2C2C;
}

body {
  font-family: 'Lato', Arial, sans-serif;
  background-color: var(--color-ivory);
  color: var(--color-text);
}

h1, h2, h3 {
  font-family: Georgia, serif;
  color: var(--color-purple);
}

a {
  color: var(--color-purple);
}

a:hover {
  color: var(--color-orange);
}

.site-header {
  background-color: #3D1A52;
  border-bottom: 3px solid var(--color-orange);
}

.site-title {
  color: #FFFFFF !important;
}
```

---

### Page Layout Guidance

- **Maximum content width:** 800–900px (comfortable reading width)
- **Spacing:** Use generous white space between sections — avoid cramped layouts
- **Section dividers:** Use `---` horizontal rules in Markdown; style with the light border color in CSS
- **Tables:** Keep headers bold and shaded with Soft Lavender; use Light Border color for borders
- **Code blocks:** Use fenced code blocks (triple backtick) — style with Soft Lavender background
- **Icons:** Use simple Unicode emoji (📧 🌐 📍 📂 ✅) sparingly for visual cues — they render in Markdown without any dependencies
- **Cards / Panels:** Simulate with blockquotes (`>`) in Markdown for callout boxes

---

### Visual Design Principles for This Program

| Principle | Application |
|---|---|
| **Warm, not clinical** | Use ivory backgrounds, not pure white; use soft lavender for alternating sections |
| **Empowering, not corporate** | Script-inspired headings (Georgia/Playfair); affirming language ("You can do this") |
| **Practical, not decorative** | Icons only where they add navigation clarity; charts and tables over decorative graphics |
| **Accessible** | Maintain AA contrast ratio between text and background; don't rely on color alone for meaning |
| **Women-centered** | Use Nigerian women's names and contexts throughout datasets and examples |

---

## Part C: File-by-File Content Plan

| File | Purpose | Notes |
|---|---|---|
| `README.md` | Public entry point; complete program overview | Must be strong enough to stand alone for any visitor |
| `docs/index.md` | GitHub Pages homepage | Add `layout: home` front matter for Jekyll |
| `docs/about.md` | Leaders Tribe org profile | Based on Organisation Profile document |
| `docs/program-overview.md` | Full program rationale and structure | Based on Concept Note document |
| `docs/level-1.md` | Beginner curriculum guide | Based on Level 1 Curriculum PDF |
| `docs/level-2.md` | Intermediate curriculum guide | Based on Level 2 Curriculum PDF |
| `docs/train-the-trainer.md` | TTT requirements and guide | Based on Concept Note TTT section |
| `docs/facilitator-resources.md` | Facilitation notes and tips | Synthesis of all uploaded materials |
| `docs/monitoring-and-evaluation.md` | M&E framework | Based on Concept Note M&E table |
| `docs/contact.md` | Contact information | From Concept Note and Organisation Profile |
| `datasets/level-1/*.csv` | 7 practice datasets for Level 1 | All created with Nigerian context |
| `datasets/level-2/*.csv` | 9 practice datasets for Level 2 | Includes messy + cleaned versions |
| `train-the-trainer/*.md/.csv` | TTT tools | Reflection report, session plan, checklist, attendance log |
| `templates/*.md/.csv` | Reusable forms | Pre-assessment, capstone rubrics, follow-up survey |
| `LICENSE` | CC BY-NC 4.0 | Protects content; allows non-commercial sharing |
| `CONTRIBUTING.md` | Contribution guidelines | Invites community contributions |
| `.gitignore` | Repository cleanliness | Ignores OS/temp/editor files |

---

## Part D: Files to Upload Manually (Remaining Checklist)

These files need to be created and uploaded manually. The repository structure already has placeholders for them.

### Slide Decks — `level-1/slides/` and `level-2/slides/`
- [ ] `session-1-intro-to-excel.pptx`
- [ ] `session-2-data-entry-sorting.pptx`
- [ ] `session-3-formulas-functions.pptx`
- [ ] `session-4-if-statements.pptx`
- [ ] `session-5-charts-visualization.pptx`
- [ ] `session-6-summarization-formatting.pptx`
- [ ] `session-7-guided-practice.pptx`
- [ ] `session-8-capstone-briefing.pptx`
- [ ] *(Repeat all 8 for Level 2 with Level 2 content)*

### Practice Workbooks — `level-1/workbooks/` and `level-2/workbooks/`
- [ ] `week1-practice-workbook.xlsx` (Level 1)
- [ ] `week2-formulas-workbook.xlsx` (Level 1)
- [ ] `week3-charts-workbook.xlsx` (Level 1)
- [ ] `week4-capstone-template.xlsx` (Level 1)
- [ ] `week1-cleaning-validation-workbook.xlsx` (Level 2)
- [ ] `week2-lookup-conditional-workbook.xlsx` (Level 2)
- [ ] `week3-pivot-dashboard-workbook.xlsx` (Level 2)
- [ ] `week4-capstone-template.xlsx` (Level 2)

### Capstone Workbook Templates — `workbooks/capstone/`
- [ ] `capstone-template-level1.xlsx` — Pre-formatted Excel file with blank sections for dataset, formulas, chart, and data story box
- [ ] `capstone-template-level2.xlsx` — Pre-formatted Excel file with sheets for raw data, cleaned data, analysis, PivotTable, and dashboard

### Brand Assets — `assets/`
- [ ] `leaders-tribe-logo.png` — Transparent background version for light pages
- [ ] `leaders-tribe-logo-white.png` — White version for dark backgrounds (dark nav, footer)
- [ ] `leaders-tribe-logo-black.png` — Dark version if needed for print

### Assessment Files — `level-1/assessments/` and `level-2/assessments/`
- [ ] `pre-assessment-level1.md` (copy from `templates/pre-assessment-template.md` and adapt)
- [ ] `pre-assessment-level2.md` (adapted version for Level 2 baseline)
- [ ] `capstone-rubric-level1.md` (copy from `templates/capstone-rubrics.md`)
- [ ] `capstone-rubric-level2.md`

### Facilitator Resources — `facilitator-resources/`
- [ ] `facilitation-guide-level1.md` — Detailed week-by-week facilitator notes
- [ ] `facilitation-guide-level2.md` — Detailed week-by-week facilitator notes
- [ ] `qa-support-notes.md` — Compiled answers to common participant questions

### Optional: Certificate Templates
- [ ] `templates/certificate-level1.docx` or `.pdf` — Printable Level 1 certificate
- [ ] `templates/certificate-level2.docx` or `.pdf` — Printable Level 2 / Data Ambassador certificate

---

## Part E: Suggested First Commit Structure

Start with these files and folders to get the repository live quickly. You can add slides, workbooks, and remaining assets in subsequent commits.

### Commit 1 — Foundation (Do This First)
```
README.md
LICENSE
CONTRIBUTING.md
.gitignore
docs/index.md
docs/about.md
docs/program-overview.md
docs/contact.md
```

### Commit 2 — Curriculum Documentation
```
docs/level-1.md
docs/level-2.md
docs/train-the-trainer.md
docs/facilitator-resources.md
docs/monitoring-and-evaluation.md
```

### Commit 3 — Datasets
```
datasets/level-1/ (all 7 CSV files)
datasets/level-2/ (all 9 CSV files)
```

### Commit 4 — Templates and TTT Tools
```
templates/ (all 4 files)
train-the-trainer/ (all 4 files)
```

### Commit 5 — Assets and Brand
```
assets/leaders-tribe-logo.png
assets/brand-colors.md
```

### Commit 6+ — Manual Uploads (as you create them)
```
level-1/slides/*.pptx
level-1/workbooks/*.xlsx
level-2/slides/*.pptx
level-2/workbooks/*.xlsx
workbooks/capstone/*.xlsx
```

---

## Part F: GitHub Pages Setup Instructions

1. Go to your repository → **Settings** → **Pages**
2. Under **Source**, select: **Deploy from a branch**
3. Branch: `main` | Folder: `/docs`
4. Click **Save**
5. Your documentation site will be live at:
   `https://[your-github-username].github.io/leaders-tribe-excel-program/`

To add a Jekyll theme, create `docs/_config.yml`:
```yaml
title: Excel for Data Analysis for Women
description: A Leaders Tribe Training Program
theme: minima
```

---

## Assumptions Made Without Stopping the Task

> *These are questions I would normally ask, answered with best-effort assumptions:*

1. **Lesson_Plan.docx content** — The file was listed as uploaded but its extracted text was not visible in the documents provided. I based all curriculum content on the Level 1 and Level 2 PDFs and the Concept Note, which were fully detailed.

2. **Program is currently two levels only** — The Organisation Profile mentions "a three-level program" but the Concept Note and both curriculum PDFs describe only Level 1 and Level 2. I structured the repository for two levels, with a note that Level 3 may follow.

3. **License choice** — CC BY-NC 4.0 was chosen as it allows free sharing and adaptation for educational use while preventing commercial exploitation without Leaders Tribe's permission. A more restrictive license (CC BY-NC-ND) could be used if remixing should not be permitted.

4. **GitHub username / repo name** — Assumed `leaders-tribe-excel-program` as the repository slug. Update the `_config.yml` baseurl if you use a different name.

5. **Cohort dates** — Used January 2024 (Cohort 1) and April 2024 (Cohort 2) in datasets as plausible cohort dates. These are fictional.

6. **Facilitators A and B** — Dashboard dataset references two unnamed facilitators. Real facilitator names can replace these.

7. **Currency** — All monetary values in datasets use Nigerian Naira (NGN) as stated in the brief. No currency symbols are used in CSV columns to keep data clean for Excel import.

8. **Student performance dataset** — Left Grade, Result, and Comment columns blank intentionally so participants can write IF formulas to populate them during the exercise.

9. **Savings group dataset** — Left "Total Saved" column blank intentionally so participants practice SUM formulas.

10. **GitHub Pages theme** — Minima (Jekyll default) recommended as it is the simplest to set up. Any Jekyll theme can be swapped in later.
