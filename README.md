# Canva Work Experience — Frontend Prep Tracker

A single-page study plan and progress tracker for students preparing for Canva's Work Experience program, Front End Web Development track.

## Overview

This is a self-contained `index.html` app that guides a student through a structured 9-week curriculum covering HTML, CSS, JavaScript, Git, and Bootstrap via Treehouse courses. It requires roughly **4 hours per week**.

Progress is persisted automatically in `localStorage` — no server or login required.

## Curriculum

| Week | Topic | Approx. Time |
|------|-------|--------------|
| 1 | HTML Foundations | ~5.5 hrs |
| 2 | CSS Styling | ~5 hrs |
| 3 | Layout, DevTools & Mobile | ~3 hrs |
| 4 | Tables, Forms & Selectors | ~5.5 hrs |
| 5 | Accessibility, Git & JS Start | ~3.5 hrs |
| 6 | JS Basics, Numbers & Functions | ~5.5 hrs |
| 7 | Loops, Arrays & Objects | ~5 hrs |
| 8 | DOM, Interactivity & OOP | ~5.5 hrs |
| 9 | Data, Bootstrap & Portfolio | ~4.5 hrs |

> Note: Flexbox and Grid courses are intentionally excluded from the official track.

## Features

- **Tab navigation** — jump between the Overview, each of the 9 weeks, and a Full Summary
- **Per-course checkboxes** — mark individual Treehouse courses as complete
- **Week progress bars** — visual fill bar showing completion within each week
- **Overall progress bar** — global completion percentage across all 26 courses
- **Overview grid** — clickable week cards showing completion status at a glance
- **Scratch-to-JS reference table** — maps Scratch programming concepts to JavaScript equivalents for students coming from Scratch
- **Persistent state** — all checkbox state is saved to `localStorage` and restored on page load
- **Print-friendly** — all weeks display when printing (tabs collapse, nav hides)
- **Responsive** — works on mobile and desktop

## Usage

Open `index.html` directly in any modern browser — no build step, no dependencies, no internet required (aside from the Google Fonts import and Treehouse course links).

```
open index.html
```
