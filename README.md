# Arnav Singh

I build ML systems and the tools that check them. Most of my work is inference, evaluation and agent reliability, plus hackathon apps that real people can open and use.

Every project below has a README with what was measured, what failed and how to run it.

## Featured

| Project | What it is | Proof |
| --- | --- | --- |
| [MAC8](https://github.com/Arnav66692/mac8) | An int8 multiply-accumulate unit for AI compute, taken from RTL to GDS on SkyWater 130 nm with open-source tools. Formally verified. Runs a 16-tap FIR filter. | [DSP demo](https://arnav66692.github.io/mac8/reports/dsp-demo/) |
| [Paged Attention Engine](https://github.com/Arnav66692/paged-attention-engine) | A paged KV-cache inference engine with continuous batching and preemption. | Matched-memory throughput and latency benchmarks, wins and losses both reported |
| [Did it actually happen?](https://github.com/Arnav66692/did-it-actually-happen) | Measures how often a false "done" from one agent corrupts a multi-agent pipeline, and which checker catches it. Swarm Alignment Hackathon 2026. | 3 preregistered experiments, 1,260 steps, [full report](https://github.com/Arnav66692/did-it-actually-happen/blob/main/report/report.pdf) |
| [Is it an e-bike?](https://github.com/Arnav66692/is-it-an-ebike) | Sourced e-bike rule checks for a rider and location, with on-device OCR, bike comparisons and route planning. Neighborhood Hacks 2026. | [Live app](https://is-it-an-ebike.vercel.app) |
| [Four Looks](https://github.com/Arnav66692/four-looks) | Type and control a computer with your head. A laptop camera is the only hardware. SanD Hacks 2026. | Runs locally, setup in the README |
| [Erase Me](https://github.com/Arnav66692/erase-me) | A privacy toolkit for data-broker removal requests, with a browser workspace, a Chrome companion and an agent skill. | [Live preview](https://erase-me-preview.vercel.app) |

## Agent reliability

| Project | What it does |
| --- | --- |
| [claim-check](https://github.com/Arnav66692/claim-check) | Claude Code hooks that check an agent's "done" against build, type-check, test and diff evidence. |
| [testguard](https://github.com/Arnav66692/testguard) | Claude Code hooks that catch an agent weakening tests, with held-out checks for hardcoded answers. |

## Hackathon builds

| Project | Event | What it does |
| --- | --- | --- |
| [Long Shadow](https://github.com/Arnav66692/NASA-Space-Apps-Challenge-2026) | NASA Space Apps 2026 | Shows what changes in the first 72 hours on the Moon when a landing slips. Geometry from NASA/JPL Horizons. [Live site](https://long-shadow-moon.vercel.app) |
| [Five Feet](https://github.com/Arnav66692/five-feet) | Learn AR with SPECS | A Spectacles Lens that shows the 5 ft around a house to clear before a wildfire, with spoken cards for blind users. |
| [Pledge Line](https://github.com/Arnav66692/pledge-line) | | Donor support and purchasing for small nonprofits, with explicit approvals and PayPal sandbox checkout. [Demo](https://pledge-line.onrender.com/demo) |
| [Model Shelf](https://github.com/Arnav66692/model-shelf) | UGREEN AI NAS 2026 | A NAS skill that names every AI model file, matches models to a job in plain words and never deletes. |

## Data and research

| Project | What it does |
| --- | --- |
| [EV charging access](https://github.com/Arnav66692/EV-Charging-Access-San-Diego) | Reproducible analysis of EV charging access, demographics and spatial equity in San Diego. |
| [EV grid siting](https://github.com/Arnav66692/EV-Charging-Access-San-Diego-version-2) | Charging equity, grid-feasibility screening and siting across three California counties. |

## Tools I use

Python, PyTorch, TypeScript, Next.js, SystemVerilog, cocotb, Yosys, LibreLane, Vercel.
