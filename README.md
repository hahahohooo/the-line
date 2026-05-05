# The Line

> *A prototype emotional support companion for informal family caregivers.*

Built as part of the **Digital Experience Design Studio** subject at the University of Technology Sydney (UTS), supervised by Dr Alejandra Mery Keitel.

---

## Overview

**The Line** is a mobile-first interactive prototype that uses a rotary dial frequency metaphor to help informal caregivers check in with their emotional state. Each frequency (1–9) maps to an emotional register — from overwhelmed to bright — paired with a colour-coded orb, ambient soundscape, and anonymous collective presence.

The project emerged from qualitative research with informal family caregivers, exploring emotional wellbeing, identity, and the need for low-barrier, stigma-free support tools.

---

## Features

- **Rotary Dial** — drag or tap to tune into an emotional frequency (1–9)
- **Journal** — optional free-text or voice entry; AI analyses tone and adapts colour + keywords
- **Orb** — animated colour orb reflecting emotional state, blended via AI when journal text is provided
- **Soundscape** — generative ambient audio mapped to each frequency (Web Audio API)
- **Echo** — anonymous collective presence screen; floating orbs represent others on the same frequency
- **Memo** — personal archive of past check-ins with a vinyl-style audio player
- **Bluetooth UI** — simulated device pairing for headphone connection

---

## Project Structure

```
the-line/
├── index.html          # Main prototype (single-file)
├── README.md           # This file
├── assets/
│   └── preview.png     # Screenshot for README / portfolio
└── docs/
    └── blueprint.md    # Technical + design blueprint
```

---

## Tech Stack

| Layer | Technology |
|---|---|
| UI | HTML5, CSS3, Vanilla JS |
| Animation | Canvas API, RequestAnimationFrame |
| Audio | Web Audio API (generative, no audio files) |
| AI (in-prototype) | Anthropic Claude API via claude.ai artifact environment |
| Font | Instrument Sans (Google Fonts) |

> **Note:** The AI-powered journal analysis (emotion detection + colour blending) only functions inside the **claude.ai** artifact environment. In a standard browser, the prototype falls back to defaults gracefully.

---

## Running Locally

No build step required. Just open the file:

```bash
git clone https://github.com/alienonearthhh-jpg/the-line.git
cd the-line
open index.html
```

Or drag `index.html` into any browser.

---

## Viewing Online

This prototype is deployed via GitHub Pages:

🔗 `https://alienonearthhh-jpg.github.io/the-line`

---

## Research Context

This prototype is informed by qualitative research conducted with two informal caregiver participants using **Experience-Centred Design (ECD)** methods. Key themes include:

- Emotional suppression and the guilt of self-care
- The collapse of identity beyond the carer role
- The need for ambient, non-demanding support tools
- Collective presence as a form of silent solidarity

A core design argument: **caregivers must prioritise their own wellbeing to effectively care for others.**

---

## Academic Context

- **Subject:** Digital Experience Design Studio
- **Institution:** University of Technology Sydney (UTS)
- **Supervisor:** Dr Alejandra Mery Keitel
- **Semester:** Autumn 2026

---

## Author

**alienonearth** — Interaction Design (Postgraduate), UTS  
GitHub: [@alienonearthhh-jpg](https://github.com/alienonearthhh-jpg)