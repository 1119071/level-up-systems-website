# Level Up Systems — Portfolio Website

A single-page portfolio site for **Level Up Systems**, a personal AI/automation
development brand. Built as one self-contained HTML file — no framework, no
build step, no backend — and designed to showcase AI-powered tools and
custom software projects.

**Live site:**(https://1119071.github.io/level-up-systems-website/)

---

## Overview

The site is a single `index.html` file with four tabs, switched client-side
with a small curtain transition animation:

- **Home** — hero intro, quick stats, and a "What I offer" services section
  (AI Automation, Document Intelligence, Custom Software)
- **About** — bio, focus areas, tech stack, and a short philosophy statement
- **Projects** — a portfolio grid linking out to live project demos, each with
  a details overlay describing the project, tech stack, and a direct "Open"
  link
- **Contact** — contact details (email, LinkedIn, phone, website) and a
  message form

### Featured projects

- **[ChurnAI](https://1119071.github.io/churnai-dashboard/)** — a customer
  churn intelligence dashboard with a customer database, an interactive risk
  calculator, and model performance charts. Fully multilingual (EN, JA, ZH,
  DE, FR, ES). Data is synthetically generated for demonstration purposes.
- **[BriefAI](https://1119071.github.io/pdf-summarizer/)** — a single-file,
  in-browser PDF summarizer using `pdf.js` and an extractive summarization
  algorithm. Runs entirely client-side: no backend, no account, no API key,
  and the uploaded file never leaves the user's device.

Both projects are hosted separately and opened from the Projects tab via
direct links, so this site itself has no dependency on them beyond the URLs.

### Contact form

The "Send message" button on the Contact tab builds a pre-filled `mailto:`
link (recipient, subject, and body assembled from the form fields) and opens
it in the visitor's own email client. This requires no backend or third-party
service, but does depend on the visitor having an email client configured.
If a submission that doesn't require the visitor's own email client is
preferred later, the form can be pointed at a service like
[Formspree](https://formspree.io) instead.

---

## Tech Stack

- Plain HTML, CSS, and JavaScript — no framework, no build tools
- Google Fonts: Cormorant Garamond (display) and Montserrat (UI/body)
- Dark navy (`#07112b`) / electric blue (`#2A6FDB`) visual identity, shared
  across this site and the individual project demos

---

## Project Structure

```
level-up-systems/
├── index.html     # The entire site (HTML + CSS + JS in one file)
└── README.md
```

---

## Running It Locally

No installation needed — it's a static HTML file.

1. Download/clone the repository
2. Open `index.html` directly in a browser

Or deploy it with GitHub Pages for a live URL (Settings → Pages → deploy from
the branch containing `index.html`).

---

## Notes on AI Usage

This site was built using **Claude AI** (Anthropic) as part of the Level Up
Systems portfolio. Concept, structure, and visual identity were directed by
the site owner; Claude was used to generate and refine the code.

---

## About Level Up Systems

Level Up Systems is a personal software/AI portfolio brand, built while
studying Business IT & Management, focused on practical AI tools and
automation rather than demos or experiments.
