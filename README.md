# [Christmas Shop](https://vlmna13.github.io/christmas-shop/home/)

A themed two-page gift shop website with a countdown timer, card shuffling, and product popup — built with pure HTML, CSS, and JavaScript.

## Features

- **Countdown timer** counting down to December 31 in real time (days / hours / minutes / seconds)
- **Featured gifts slider** on the home page — responsive chunk-based scrolling that recalculates on window resize; prev/next buttons auto-disable at boundaries
- **Randomized gift cards** — shuffled on every page load using a custom shuffle function
- **Category filter** on the gifts page — instant re-render by category (All / specific), keeping shuffle state
- **Product popup** — dynamically built in JS, shows name, description, category, and a "superpowers" section with snowflake rating visuals
- **Scroll-to-top button** appears after 300px scroll on mobile
- **Burger menu** with body scroll lock

## Tech Stack

| | |
|---|---|
| Markup | HTML5 (semantic) |
| Styles | CSS3 — flexbox, grid |
| Logic | Vanilla JavaScript, ES Modules |
| Data | Static JS data file (`gifts.js`) |
