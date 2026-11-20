# The Rusty Griffin (Ржавый Грифон)

**Play in the browser: https://iansilent.github.io/rusty-griffin/**

A cozy web prototype: you run a magic weapon shop for heroes. The look is old fantasy with a dungeon synth mood.

## The loop

1. Three to five heroes come in each day, each before a quest. They differ by race, class and what they are missing: a hand, a leg, an eye.
2. For each hero you pick an item type, a material and a magic gem. The choice should fit the hero and the quest.
3. A short forge mini-game: three timed hammer strikes.
4. At night a raven brings letters: how each hero did, why, and what they pay.
5. Gold upgrades the shop and the workshop. Fame unlocks harder quests.

Heroes come back, earn titles and greet you differently. Rarely, a veteran's weapon returns with a name and a story, and trophies from big events hang on the shop wall.

## Tech

One `index.html`: vanilla JavaScript and a low-resolution canvas, no build step. Fonts load from Google Fonts. Progress is saved in the browser's `localStorage`. The UI is in Russian.
