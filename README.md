# Dhofar Project Finder

A buildless, mobile-first FIND IT form for an A2+/B1 English learner. Open `index.html` or serve this directory with `python3 -m http.server 8765`. No dependencies, backend, accounts, analytics or remote assets.

Answers and current step are saved under `dhofar-project-finder-v1` in browser localStorage. The completion screen provides all answers, editing, browser printing and confirmed reset. Storage belongs to that browser and origin; it is not synced between devices.

## Content review

The eight questions cover area, people, apparent problem, observation, evidence, importance, investigation and motivation. The original broad options are retained. A short reminder after the area question encourages focus on one need, without selecting a solution. Uncertainty is explicitly welcomed. Extra fields cover areas, people, problems and places. The final writing screen lets the learner review earlier choices.

All eight requested scenarios remain coherent: jobs, sport, litter/environment, transport, education, small businesses, visitor information and community/free-time activities. Evidence and importance are separate; observation and investigation concern present experience and possible future checking respectively. Writing consolidates earlier thinking.

## Verification

Browser-tested all eight questions, both maximum-three limits, single-choice replacement, all four extra fields, forward/back navigation, progress, writing persistence, refresh recovery, summary, edit controls and reset cancellation/confirmation. Ran eight complete example journeys across the project areas above. Inspected 390px phone layout. JavaScript syntax check passed; no JavaScript errors observed during journeys.

The browser print action was exercised, but its native modal blocked further inspection in that tab. Print CSS removes navigation and controls, uses plain white paper styling, and keeps each answer section together; a final visual paper/PDF check remains outstanding.

## Publishing

This workspace began as an empty Git repository on `main`, with no commits, remote, existing files or deployment configuration. No GitHub destination can be inferred from it. Push and deployment require the intended existing repository URL and branch. The three application files can be served directly by GitHub Pages without a build step; follow the destination repository's actual deployment configuration once identified.
