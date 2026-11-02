# Kiezkorb v2: user feedback (Week 5)

Date: 2 Nov 2026. Version tested: v2 (https://bejewelled-bavarois-a884c2.netlify.app/). I missed the in-class maker fair (sick), so these are my own tests, done remotely.

## T1: brother

Role/age: to fill. Where/how: to fill (remote, phone?).

Quote (translated from Spanish): "A way to write to the other person instead of just pressing Accept, and maybe a window to see a history, so that after Mark as taken the offer doesn't just disappear."

- **Pain point 1:** Accept is a one-way button. The giver cannot talk to the neighbor (to agree a time, ask a question).
- **Pain point 2:** After "Mark as taken" the offer vanishes, with no record of what was shared.
- **Need:** When I decide who gets the food, I want to talk to them, so I can agree the pickup. When I close an offer, I want to see it later, so I know what happened.
- **Suggests:** in-app chat or message thread per request, a history section (taken and expired offers).

## T2: friend (Hiram, university)

Role/age: university student, to fill age. Remote, via chat.

Quotes (translated): "The only thing I see is that it looks made for phones, so it would be good if it looked better on a PC." / "And it should have more description when you click an item."

- **Pain point 1:** Layout is a narrow phone column on desktop.
- **Pain point 2:** The offer detail has too little information.
- **Suggests:** a wider layout on desktop, a free-text description in the offer (v1 had one, v2 dropped it).

## Patterns so far (2 people)

| Theme | Who | Link to earlier findings |
|---|---|---|
| Contact between neighbors is too thin | T1 | Week 3 P1 trusts people she knows. A message thread supports that. |
| No record after an offer closes | T1 | Week 2 H3 (user control). v2 added undo but no history. |
| Not good on desktop | T2 | v2 was designed mobile-first from P1's context. Not tested on desktop. |
| Detail lacks description | T2 | v1 had "details and ingredients". v2 removed it for speed. |

## Not yet known

- Did they finish the three tasks (find, ask to pick up, offer)? Ask next testers to do them and watch.
- Neither tester commented on allergens, trust cues or the building scope, the main v2 bets. Only 2 testers, so this is not evidence they work.

## Changes made to v2 after these tests

| Feedback | Change |
|---|---|
| T2: more description when you open an offer | New optional "Details and ingredients" field when offering (step 2). The offer detail shows it under "About this food". Sample offers have descriptions. |
| T2: looks made for phones, better on PC | From 900 px wide the layout is wider with two columns of offers and a wider dialog. |
| T1: after "Mark as taken" it just disappears | New "History" section in My offers with taken and expired offers (and who took them, when accepted). |
| T1: write to the other person instead of only Accept | Not done yet. Needs a message thread between neighbors, a bigger change. |
