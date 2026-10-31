<div align="center">

<img src="assets/banner.svg" alt="Cool AI Skills" width="100%"/>

<br/>

![Skills](https://img.shields.io/badge/skills-4-7c3aed?style=for-the-badge)
![Format](https://img.shields.io/badge/format-SKILL.md-0ea5e9?style=for-the-badge)
![Curated](https://img.shields.io/badge/curated-by_hand-f472b6?style=for-the-badge)

**A collection of cool AI skills I've found.**
Each one is a drop-in `SKILL.md` bundle for Claude Code and other skill-aware agents.

</div>

---

## Contents

| | Skill | What it does |
|---|---|---|
| 🚀 | [nasa-handbook](#-nasa-handbook) | Apollo-era NASA paperwork, rendered to PDF |
| 📐 | [anatomy](#-anatomy) | Interactive isometric SVG explainers |
| ⠿ | [ascii-art](#-ascii-art) | Photos to animated dot-lattice art |
| 🎨 | [taste-skill](#-taste-skill) | Art direction so agents stop building generic AI pages |

---

## 🚀 nasa-handbook

![Type](https://img.shields.io/badge/type-documents-b91c1c?style=flat-square)
![Output](https://img.shields.io/badge/output-PDF-1f2937?style=flat-square)
![Style](https://img.shields.io/badge/style-Apollo_era-f5f5f4?style=flat-square&labelColor=1f2937)

> **Make printable technical documents in the style of Apollo-era NASA paperwork.**

Modelled on an Apollo Operations Handbook "Systems Data" page, with:

- a typed running head and numbered paragraphs
- Leroy-lettered line drawings and schematics
- a performance data table
- `NOTE` / `CAUTION` / `WARNING` notices
- a Flight Data File checklist card, a black thumb tab and a dated footer
- A4 or US Letter PDF output

**Use it for:** NASA-style or retro aerospace docs, spec sheets and one-pagers that should look like vintage engineering paperwork, or a handbook page explaining a product, codebase, system or fictional gadget.

**Try:** *"Make me an Apollo-style handbook page for my home server."*

**Source:** [R44VC0RP/skills → nasa-handbook](https://github.com/R44VC0RP/skills/tree/main/skills/nasa-handbook)

---

## 📐 anatomy

![Type](https://img.shields.io/badge/type-illustration-0ea5e9?style=flat-square)
![Output](https://img.shields.io/badge/output-SVG_+_WebGL-6366f1?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-22c55e?style=flat-square)

> **Build crafted, interactive isometric SVG figures that explain a technical idea as a real physical object.**

Think a test rig, a dial gauge, a cabinet of drawers, a plotter or a lock, with:

- many small, precise solid parts and four-tone shading
- correct painter's order
- a framed card with title, hint and live readout
- calm, eased motion
- optional WebGL shaders (fire, exhaust, water, caustics, lamp light) inside the drawing, in the same isometric perspective
- framework-free TypeScript/JS, or React/Next.js

**Use it for:** docs, blog posts, landing pages and articles, "Linear-style" premium technical drawings, or any SVG showing how a system, algorithm or component works.

**Try:** *"Draw how a rate limiter works as an isometric machine."*

**Source:** [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy)

---

## ⠿ ascii-art

![Type](https://img.shields.io/badge/type-generative_art-dc143c?style=flat-square)
![Output](https://img.shields.io/badge/output-HTML_+_MP4-3f3f46?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-22c55e?style=flat-square)

> **Dot-lattice art: photo to two-tone dot map to seamless animated loop.**

Turns any photo, sculpture, object or drawing into a figure made of dots on a fixed grid (charcoal ground, two greys, rare crimson), then animates it into a seamless loop.

- disintegration into wind-blown dust
- things emerging or growing out of the figure
- voids, tentacles and fine-stipple creatures
- engine plus scripts for the mechanical parts: image to dot map, still render, scene JSON to HTML, frames to MP4

**Needs:** Python 3.10+ (`numpy`, `scipy`, `Pillow`, `scikit-image`), Playwright with Chromium, and `ffmpeg`.

**Try:** *"Turn this photo of a bust into a dust-disintegration loop."*

**Source:** [0xSero/ascii-art](https://github.com/0xSero/ascii-art)

---

## 🎨 taste-skill

![Type](https://img.shields.io/badge/type-frontend_design-ff6b00?style=flat-square)
![Output](https://img.shields.io/badge/output-websites_+_app_screens-24292f?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-22c55e?style=flat-square)

> **Makes coding agents design websites and app screens instead of assembling the average landing page.**

Gives the agent an art direction, real pictures, and a way to check its own work in a real browser.

- anti-slop design direction instead of generic AI layouts
- reference imagery rather than placeholder blocks
- a browser check step so the agent reviews what it built
- older styles (soft, minimalist, brutalist and more) live in the opt-in [taste-skill-classics](https://github.com/Leonxlnx/taste-skill-classics)

**Try:** *"Build a landing page for a coffee shop using taste-skill."*

**Source:** [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) · [tasteskill.dev](https://tasteskill.dev)

---

## Installing a skill

Copy the skill folder from its source repo into your skills directory:

```bash
# personal (all projects)
~/.claude/skills/<skill-name>/

# or per project
.claude/skills/<skill-name>/
```

Restart your agent and the skill will show up automatically.

---

<div align="center">
<sub>Skills belong to their original authors. Check each source repo for licence details.</sub>
</div>
