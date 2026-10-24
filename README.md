# GUI Design & Web Optimization

Kiezkorb v2, Week 4 redesigned prototype. Cycle 1, Personal Product.

- Live build: https://bejewelled-bavarois-a884c2.netlify.app/
- Live lo-fi: https://benevolent-phoenix-da0d32.netlify.app
- `lofi/index.html`: lo-fi prototype, five annotated mobile screens (feed, offer detail, ask to pick up, offer in 3 steps, my offers).
- `app/index.html`: the vibe-coded redesign, a single static file with no build step. Open it in a browser.

## What the research says

Sources: Week 2 heuristic evaluation (Heuristic_Evaluation_Kiezkorb) and the Week 3 context map plus interview 1 (Week3_Context_Mapping_Nicolas).

Problem statement: people have food they cannot finish and throw it away, because they have no easy way to offer it to neighbors. Sharing only happens in special moments, and taking food from a stranger feels strange. Trust in the person and the look of the food decide if they accept.

Design goal: neighbors can easily offer and find extra food nearby, and feel safe and comfortable sharing it.

## Decisions

| Decision | Research behind it |
|---|---|
| Feed starts with "My building", then "Nearby" | P1: "I never find out about food that people give away near me." Sharing works better where neighbors already know each other (Norwegian suburb study). |
| Big photo, condition chip and giver (floor, number of shares) before any contact | P1 refuses food that "looks bad" or from someone she does not trust. |
| "Ask to pick up" inside the app with a one-tap message, no public email, pickup spot revealed after acceptance | Week 2 H4 (email exposed). The "strange" feeling gets a soft script. |
| Allergens and condition are required (with "None known") | Week 2 H4. Allergens did not come up in P1's interview, so this one rests on the heuristic evaluation and the assumption in the Week 3 map, not on interview evidence. |
| Offer in 3 steps, photo first, "offer something again" | Problem statement: no easy way to offer. |
| Mark as taken and Delete with an Undo toast, request status (Sent, Accepted, Picked up) | Week 2 H1 and H3. |
| Share on WhatsApp from my offers | Week 3 assumption that people already use chat apps. Not confirmed by P1, to test. |
| Real counts, no fake "LIVE" or kg stats | Week 2 H1. |
| "You" and "Your offer" instead of "Tú" and a bare "0" | Week 2 H2. |

## Limits

- Only one interview done (P1, a family member in Pereira, Colombia, so answers may be softer). Interview 2 is missing, so the decisions are not yet cross-checked.
- Demo only: data lives in `localStorage`, requests are simulated (the neighbor "accepts" after 4 seconds), no backend.
- Photos are resized in the browser and stored on the device.
