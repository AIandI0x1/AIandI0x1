0x1

**Data Analytics · AI Governance · Agent Orchestration · Local-First AI**

Building **0x1 — Orchestra Unified**, an AI-governed work orchestration platform
that manages AI agents, verifies their output, and maintains a tamper-evident
audit trail. 6,400+ Python modules, 14,310 commits, ~299K chained events.

- Orchestrating AI work across cloud and local — local execution layer bootstrapping on AMD Strix Halo (128 GB unified memory)
- Multi-node setup: macOS + Linux over private mesh
- Source code is private — [showcase here](https://github.com/AIandI0x1/0x1-showcase)
- Repository access on request: andre.hamm1@gmx.de

## Main project

| Project | What it does |
|---|---|
| [0x1-showcase](https://github.com/AIandI0x1/0x1-showcase) | AI-governed work orchestration platform. Includes absorbed modules: agent harness (hermes-agent), communication platform (buzz) |

## Hardware porting — AMD Strix Halo (gfx1151, RDNA 3.5)

Ported inference optimization tools to Strix Halo with documented evidence:

| Project | What was done |
|---|---|
| [Hyperloom](https://github.com/AIandI0x1/Hyperloom) | GPU type detection for gfx1151, llama.cpp framework adapter, 135 tests passing |
| [Magpie](https://github.com/AIandI0x1/Magpie) | Benchmark scripts for Strix Halo, TraceLens validation, hardware-agnostic trace analysis |
| [GEAK](https://github.com/AIandI0x1/GEAK) | RDNA 3.5 hardware knowledge, Triton and HIP kernel verification, wave32/wave64 guidance |

All three verified on hardware: `_autodetect_gpu_type() = 'strix-halo'`

## Standalone projects

| Project | What it does |
|---|---|
| [SwiftLM](https://github.com/AIandI0x1/SwiftLM) | Native Swift MLX inference server for Apple Silicon, SSD MoE streaming, OpenAI-compatible API |
| [hermes-agent-self-evolution](https://github.com/AIandI0x1/hermes-agent-self-evolution) | Evolutionary self-improvement for Hermes Agent (DSPy + GEPA) |

## Recognition

- **Devin Pro Max** — tool access funded by [Nader Dabit](https://x.com/naderdabit) (AI developer advocate, ~100k followers)
- **hoplite.sh** — Pro account granted directly by Ryan Morrissey (Co-Founder & CEO, Hoplite / YC S26)
- **boardyai** — lifetime member

## Contact

- Email: andre.hamm1@gmx.de
- Location: Essen, Germany
- One step at a time.
