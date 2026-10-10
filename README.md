# yaya-study

Buildless mobile-friendly civil-service exam practice for yaya. Deploy the repository root as a static site; no build command, output directory `.`. Entry: `index.html`.

## Practice and rewards
- Fixed 20-question daily challenge, refreshed by Beijing date; six categories, pause/resume.
- First daily answer: correct +5 points, incorrect +2. Completion +20, all twenty first answers correct +50. Perfect day: 170 points. Repeated answers earn no extra points.
- Specialty practice earns separate XP; existing `shangan-dazi-v1` learning records are preserved on the same origin.
- Gift wishes: coffee 200, perfume 1500, bag 4500, hotel 6000, camera 8000, Xinjiang flights/hotel 15000. Redemption deducts points and creates a copyable request; cancellation refunds once. Actual fulfillment, budget and arrangements are agreed privately by the two people.
- This is a personal browser-local reward tracker, not a verified payment or fulfillment service. No accounts or cross-device sync. Export a JSON backup in the gift page; changing origin or clearing storage loses local records.
- Reminder messages work only while the page is open and visible.

## Content
101 playable questions: 21 recalled-paper concept adaptations and 80 independently written exercises. Sources include https://github.com/ERRRC/xingcezhenti, with 54 module links for 2024–2026. Adapted questions identify year and original question ID where available; they are not unchanged official papers. No claim that all original papers have been imported.

## Verification
Run `node verify.cjs` for daily selection, point accounting, resume, migration, one-time reward and redemption checks. No dependencies required. Mobile CSS includes safe-area navigation and reduced-motion handling; real-device visual verification remains needed.
