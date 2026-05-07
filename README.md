# PhD Dissertation Defense -- Mario Morales Gomez

Single-file scroll-based HTML deck for the public seminar and oral exam,
Mel and Enid Zuckerman College of Public Health, University of Arizona, 2026.

**Live URL:** <https://yeridu.github.io/phd-dissertation-presentation-2026/>

The deck is one self-contained HTML file. Open the URL in any modern browser
(Chrome, Edge, Firefox, Safari) on any device. No build step, no install, no
external dependencies beyond Google Fonts loaded at runtime.

---

## Talk

Three studies, three analytical scales:

- **Paper 1 -- Worldwide.** Systematic review of cluster-randomized trials
  that measured both dating-violence and substance-use outcomes.
- **Paper 2 -- Institutional.** Four-year evaluation of Green Dot in 26
  Kentucky high schools, focused on a school-level victim-blaming attitude
  (AR-SAVB).
- **Paper 3 -- Population.** YRBS 2023 etiological analysis of seven life-
  experience composites predicting nonmedical prescription opioid use,
  testing whether bullying is opioid-specific.

Total run time: about 37 minutes of speaking plus three 2-minute Spanish
summary videos, leaving roughly 6-7 minutes for committee questions in the
50-minute seminar slot.

## Committee

- Scott C. Carvajal, PhD, MPH -- Chair, Dept. of Health Promotion Sciences
- Patricia L. Haynes, PhD
- Maeve E. Wallace, PhD
- Ann L. Coker, PhD, MPH

## Keyboard shortcuts

| Key | Action |
|---|---|
| `Right` / `Left` / `Space` | Next / previous slide |
| `Home` / `End` | Jump to first / last slide |
| `S` | Toggle the speaker-notes drawer |
| `Q` | Toggle the anticipated committee-question drawer |
| `D` | Toggle the dissertation-source pointer drawer |
| `R` | Toggle the references drawer |
| `T` | Toggle the talk timer |
| `F` | Fullscreen |
| `P` | Print-friendly view |
| `I` | From any appendix slide, jump back to the appendix index |
| `Esc` | Close any open drawer |

## Repository contents

| File | Purpose |
|---|---|
| `index.html` | Tiny redirect to the deck (keeps the repo URL clean) |
| `index3.html` | The presentation deck (single self-contained HTML file) |
| `VideoSysRew_v1.mp4` | Spanish summary, Paper 1 (~2 min) |
| `VideoGreenDot_v1.mp4` | Spanish summary, Paper 2 (~2 min) |
| `VideoNMPOU_v1.mp4` | Spanish summary, Paper 3 (~2 min) |
| `Speaker_Notes_Booklet.md` | Per-slide spoken script, in study-and-memorize format |
| `LICENSE` | CC BY-NC 4.0 |

## Run locally

Either open `index.html` directly in any modern browser, or serve via a
simple static server so the videos load without file-protocol restrictions:

```
python -m http.server 8080
```

Then open <http://localhost:8080/>.

## License

Slides and supporting materials are released under the Creative Commons
Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0). See
`LICENSE` for full terms.

Cite as:

> Morales Gomez, M. (2026). *Adolescent prevention of dating violence and
> substance use: integrated and specific.* PhD dissertation defense,
> University of Arizona, Mel and Enid Zuckerman College of Public Health.
