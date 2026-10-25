# ESL classes

General ESL class materials.

## Module E — Dhofar Project Finder

A buildless, mobile-first FIND IT form for an A2+/B1 English learner. Open `module-e/project-finder/index.html` or serve this directory with `python3 -m http.server 8765`. No dependencies, backend, accounts, analytics or remote assets.

Answers and current step are saved under `dhofar-project-finder-v1` in browser localStorage. The completion screen provides all answers, editing, browser printing and confirmed reset. Storage belongs to that browser and origin; it is not synced between devices.

## Content review

The eight questions cover area, people, apparent problem, observation, evidence, importance, investigation and motivation. The original broad options are retained. A short reminder after the area question encourages focus on one need, without selecting a solution. Uncertainty is explicitly welcomed. Extra fields cover areas, people, problems and places. The final writing screen lets the learner review earlier choices.

All eight requested scenarios remain coherent: jobs, sport, litter/environment, transport, education, small businesses, visitor information and community/free-time activities. Evidence and importance are separate; observation and investigation concern present experience and possible future checking respectively. Writing consolidates earlier thinking.

## Verification

Browser-tested all eight questions, both maximum-three limits, single-choice replacement, all four extra fields, forward/back navigation, progress, writing persistence, refresh recovery, summary, edit controls and reset cancellation/confirmation. Ran eight complete example journeys across the project areas above. Inspected 390px phone and 1280px desktop layouts; verified keyboard activation. JavaScript syntax check passed; no JavaScript errors observed during journeys.

The browser print action was exercised, but its native modal blocked further inspection in that tab. Print CSS removes navigation and controls, uses plain white paper styling, and keeps each answer section together; a final visual paper/PDF check remains outstanding.

## Publishing

Intended repository: `orlandorobson/esl-classes`, branch `main`.

Enable GitHub Pages using **Deploy from a branch**, `main`, `/ (root)`.
The project finder will be at:
`https://orlandorobson.github.io/esl-classes/module-e/project-finder/`

The repository root has a small materials index and `.nojekyll` for plain static hosting. No build step is required. Repository creation, push and live verification are pending authenticated access.
