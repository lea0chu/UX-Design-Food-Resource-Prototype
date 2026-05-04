# UX Design Food Resource Prototype
** UX in Digital Development**  
Group 7 —  Leanne, Farah, Aran · Spring 2026

---

## Overview

This prototype is a digital design solution addressing a communications asymmetry in graduate student food access at Columbia University. Research found that students were unaware of institutional food resources — not because the resources didn't exist, but because they were never communicated clearly. This prototype surfaces those resources at the moments when students are forming habits.

The project consists of two linked HTML pages designed to be embedded in existing student communication channels like in newsletters, WhatsApp groups, Google Sites.

---

## Files

| File | Description |
|------|-------------|
| `Food_Digest.html` | Biweekly newsletter page with deal cards, dining plan spotlight, student pick of the week, and a recipe section |
| `index.html` | Interactive food resource directory with live search and category filtering |

---

## Features

### Food Digest (`Food_Digest.html`)
- **Filterable deal cards** — filter nearby restaurants by Halal, EBT, or Vegetarian
- **Dining plan spotlight** — side-by-side cost comparison ($11–$13.75 vs $17.50 walk-in)
- **QR code** — auto-generated, links to the resource directory; scannable or clickable
- **Student pick of the week** — rotating peer recommendation
- **Student recipe** — submitted by students, tagged by dietary restriction
- **Resource tiles** — SNAP/EBT and campus pantry, framed as everyday resources

### Food Resource Directory (`index.html`)
- **Live search bar** — filters all cards in real time as you type
- **Category filters** — On campus · Federal · NYC programs · Discounts · Halal & dietary
- **Clickable links** — all resources open in a new tab
- **Hover effects** — cards lift on hover
- **No-results state** — displayed when search + filter returns nothing
- **Section auto-hide** — sections with no matching cards disappear automatically

---

## How to open locally

Double-click either HTML file to open it in your browser. No server or installation required.

To open from R:
```r
browseURL("path/to/Food_Digest.html")
browseURL("path/to/index.html")
```

---

## How to host (GitHub Pages)

This prototype is hosted at:  
**[https://lea0chu.github.io/UX-Design-Food-Resource-Prototype/](https://lea0chu.github.io/UX-Design-Food-Resource-Prototype/)**

To update:
1. Edit the HTML files locally
2. Commit and push to the `main` branch
3. GitHub Pages deploys automatically within ~60 seconds


## Research background

This prototype emerged from our research process involving semi-structured interviews, journey maps, and ecosystem mapping with 7 graduate students across SIPA and SPS (March 2026).

Key findings: no participant had been informed about the graduate dining plan through any institutional channel. Students had built their own informal infrastructure — a "Free Food at SIPA" WhatsApp group circulating photos of leftover club food — in response to institutional silence.

The intervention addresses the communications failure, not the supply problem. It surfaces existing resources (dining plan, pantry, SNAP) at orientation and through channels students already open, rather than requiring students to seek them out.

Full research documentation available in the project presentation deck.

---

## Design decisions

- **No new infrastructure** — works within existing student channels
- **Pantry framed as one tier among several** — reduces stigma of crisis-signal framing
- **Dietary filters built in** — halal, vegetarian, EBT tags address structural mismatch between provision and need
- **Peer content** — student picks and recipes increase trust and relatability
- **QR code links to resource directory** — orientation handout → digital resource in one scan

---

## Limitations

- Does not solve the supply problem (e.g., limited halal options in IAB)
- Depends on students opening the newsletter
- Stigma is redistributed, not fully resolved
- Does not reach students in crisis periods when engagement drops
