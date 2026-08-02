0x1

**Data Analytics · AI Governance · Agent Orchestration · Local-First AI**

Building **0x1 — Orchestra Unified**, an AI-governed work orchestration platform
that manages AI agents, verifies their output, and maintains a tamper-evident
audit trail. 6,400+ Python modules, 14,310 commits, ~299K chained events.

- Orchestrating AI work across cloud and local — local execution layer bootstrapping on AMD Strix Halo (128 GB unified memory)
- Multi-node setup: macOS + Linux over private mesh
- Source code is private — [showcase here](https://github.com/AIandI0x1/0x1-showcase)

## Main project

| Project | 
  What it does 

| [0x1-showcase](https://github.com/AIandI0x1/0x1-showcase) | 
    AI-governed work orchestration platform. Includes absorbed modules: agent harness (hermes-agent), communication platform (buzz), a couple of inference servers i will soon start to list em all up        shout out to Carlo 

| 0x1(https://github.com/AIandI0x1/0x1-Main-mirror) | 
    The actual project early dev (coding) started two years ago, real full dev began September 2025, 0x1 as a vision and idea is 10+ years old now with AI i can finally accelerate development
    This month we will update to the next Version with major changes (August 2026), multi agent orchestration framework
    fully auditable, early alpha, Agent GOV; Authority, Synthetic Brain framework. State machine.
    Next steps: Fully Synthetic Brain APP (Dont fear the brain naming these are labels to boost coherence but can be chosen by the dev at will),
    Goal: Semi-autonomous AI factory driven by human in the loop. Continuoous self-improvement. 
    Goal: Deploy a humanoid robot driven by 0x1 (preferably Unitree) EOY 2027
    
          
## Hardware porting — AMD Strix Halo (gfx1151, RDNA 3.5)

Ported inference optimization tools to Strix Halo with documented evidence:

| Project | What was done |
|---|---|
| [Hyperloom](https://github.com/AIandI0x1/Hyperloom) | GPU type detection for gfx1151, llama.cpp framework adapter, 135 tests passing |
| [Magpie](https://github.com/AIandI0x1/Magpie) | Benchmark scripts for Strix Halo, TraceLens validation, hardware-agnostic trace analysis |
| [GEAK](https://github.com/AIandI0x1/GEAK) | RDNA 3.5 hardware knowledge, Triton and HIP kernel verification, wave32/wave64 guidance |

All three verified on hardware: `_autodetect_gpu_type() = 'strix-halo'`

- One step at a time.
