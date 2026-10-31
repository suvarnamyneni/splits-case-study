# eXp Splits — UX case study

A static case study of **eXp Splits**, the commission-splits feature in eXp Realty’s My eXp agent app. The study covers the guided splits form, Disbursement Authorization (DA) review, and the wider agent app around it.

**Case study by [Suvarna Myneni](https://www.linkedin.com/in/suvarnamyneni/).** Senior UX Designer at eXp Realty from February 2023 to September 2025, now AI-Native UX Designer. On Splits she led the end-to-end flow, DA review and approval, mobile, and notifications, in collaboration with designer Pranjali Binwani and project manager Sanjay Patel.

Design started September 13, 2023, and moved through discovery, Phase 2, and Phase 3 stakeholder reviews. Some details are generalized to respect confidentiality. Figures in the metrics table are design targets, not measured launch results.

## View it

Published with GitHub Pages from the repository root:

https://suvarnamyneni-project.github.io/splits-case-study/

Locally, open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080/. Paths are relative, so the site works both at the domain root of a user page and as a project site.

There is no build step. The site is plain HTML, CSS, and JavaScript.

## What’s in the study

- Hero with the summary and role, team, timeline, and tools
- Sticky section navigation
- Problem, personas, research inputs, goals and design targets, process, the end-to-end flow, and ten design decisions
- Final screens, including a before/after of the old three-tab transaction flow and the new stepper
- The wider My eXp app (home, transactions, earnings)
- Design outcomes, first-person learnings, and a short note on what is generalized
- Click any screenshot to enlarge it. Arrow keys move between images; Escape closes the viewer. Without JavaScript, the same control opens the image file directly.

## Screens

`assets/` holds 25 screenshots exported from the Figma file, resized to a maximum width of 1600px and saved as WebP (quality 90 for interface screens, 82 for the sketch scan and whiteboard photo). Original export names are kept so each file still matches its source frame: cover, persona, wireframes, sketches, splits steps, DA states, mobile, notifications, earnings, the old upload flow, SkySlope, staff review, and the document uploader.

## Pages setup

GitHub Pages is served from the `main` branch, folder `/`. An empty `.nojekyll` file keeps Jekyll from processing the site.
