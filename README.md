<h1 align="center">Dingran Dai</h1>

<p align="center">
  <strong>Creative Technologist & AI Builder</strong> — Designer who builds, engineer who sketches<br>
  <sub>Architechture → Applied Information Science @ Cornell Tech</sub>
</p>

<p align="center">
  <a href="https://www.daidingrdesigns.com"><img src="https://img.shields.io/badge/Portfolio-18181B?style=flat-square&logo=safari&logoColor=E4E4E7"></a>
  <a href="https://www.linkedin.com/in/dingran-dai-4a24a8320/"><img src="https://img.shields.io/badge/LinkedIn-18181B?style=flat-square&logo=linkedin&logoColor=E4E4E7"></a>
  <a href="mailto:dd699@cornell.edu"><img src="https://img.shields.io/badge/Email-18181B?style=flat-square&logo=maildotru&logoColor=E4E4E7"></a>
</p>

<br>
## Design for noticing, not for answers

A street never tells you where to walk. It widens a sightline, drops a threshold, puts a bench where you'd hesitate — and leaves the decision to you. Five years of planning taught me that the strongest intervention is the one that changes what you *notice*.

So that's what I build, in silicon now instead of concrete. Every project below surfaces something that was already there but unattended, frames it so a person can act in one glance, and then gets out of the way. None of them hand down a verdict.

```mermaid
%%{init: {'theme':'base','themeVariables':{'fontFamily':'ui-sans-serif, system-ui, sans-serif','fontSize':'13px','primaryColor':'#27272A','primaryTextColor':'#E4E4E7','primaryBorderColor':'#3F3F46','lineColor':'#71717A','clusterBkg':'#18181B','clusterBorder':'#3F3F46'}}}%%
flowchart TB
    subgraph DEV["　DEVICES & PHYSICAL COMPUTING　"]
        direction LR
        d1("Subway Telltale"):::n
        d2("PROMPT!"):::n
        d3("Sprout"):::n
        d4("ER-Companion"):::n
        d5("Cat Companion"):::n
    end

    subgraph AI["　AI & AGENT SYSTEMS　"]
        direction LR
        a1("SocratiDesk"):::n
        a2("TeaGuard"):::n
        a3("Socratic Agent"):::n
        a4("FitFindr"):::n
    end

    subgraph WEB["　FULL-STACK PRODUCTS　"]
        direction LR
        w1("Into Place"):::n
        w2("ai-wardrobe"):::n
        w3("portfolio-next"):::n
    end

    DEV ==> T
    AI ==> T
    WEB ==> T

    T{{"surface it · frame it · hand the judgment back"}}:::thesis

    classDef n fill:#27272A,stroke:#52525B,color:#E4E4E7,rx:6,ry:6
    classDef thesis fill:#312E81,stroke:#6366F1,color:#EEF2FF,font-weight:bold
```

<br>

### ◾ Devices & Physical Computing
*ESP32 · CircuitPython · Jetson · sensors · 3D printing*

**[Portable Subway Telltale](https://github.com/Daidai1031/Portable-Subway-Telltale)** — Keychain ambient display for Roosevelt Island. One glance tells you whether to run.
**[PROMPT!](https://github.com/Daidai1031/PROMPT-)** — AI literacy card game for kids 10+. They say what they notice out loud; a coach replies. Fully offline on a Jetson, so no child's voice leaves the table.
**[Sprout](https://github.com/Daidai1031/Sprout)** — Chest-clip wearable that turns posture into physics-driven bubbles. Visualizes, never nags.
**[ER-Companion](https://github.com/Daidai1031/ER-Companion)** — Low-cost wristband that catches falls and seizures for ER patients who can't speak for themselves.
**[Cat Companion](https://github.com/Daidai1031/ubicomp-cat-companion)** — A 3D-printed cat you level up by keeping your own daily quests.

### ◾ AI & Agent Systems
*RAG · ReAct agents · on-device inference · multi-signal classification*

**[SocratiDesk](https://github.com/Daidai1031/SocratiDesk)** — Voice-first study companion that asks instead of answers. No tabs, no copy-paste, just thinking aloud.
**[TeaGuard Trust API](https://github.com/Daidai1031/teaguard-trust-api)** — Screens anonymous reviews for privacy and defamation risk. Refuses to rule on truth; flags what needs a human.
**[Socratic Agent](https://github.com/Daidai1031/socratic-agent-local)** — Local ReAct agent scaffold behind the Socratic experiments.
**[FitFindr](https://github.com/Daidai1031/ai201-project2-fitfindr-starter)** — Three-tool agent with a planning loop: finds secondhand listings, styles them against your wardrobe, writes the caption.

### ◾ Full-Stack Products
*Next.js · Supabase · fal.ai · Flask*

**[Into Place](https://github.com/Daidai1031/into-place)** — Drop a pin and a place's real archive becomes a short film you direct. Sourced material keeps its era and license; every generated frame stays labeled as generated.
**[ai-wardrobe](https://github.com/Daidai1031/ai-wardrobe)** — Shoot your closet once, then let it dress you for the weather.
**[portfolio-next](https://github.com/Daidai1031/portfolio-next)** — This site, hand-built. Next.js 16, Tailwind v4, MDX.

<br>

## Bench

| | |
|:--|:--|
| **Design** | Figma · Rhino · Fusion 360 · Illustrator · AutoCAD · Adobe Creative Suite|
| **Frontend** | TypeScript · Next.js · React · Tailwind · MDX |
| **Backend** | Python · Flask · FastAPI · SQL · SQLAlchemy · Supabase |
| **AI** | LLM orchestration · RAG · ReAct agents · Whisper · Kokoro TTS · Tesseract OCR · Claude · Llama · fal.ai |
| **Hardware** | ESP32-S2/S3 · Raspberry Pi · Jetson AGX Thor · Arduino · CircuitPython · IMU |
| **Fabrication** | Laser cutting · 3D printing · Parametric modeling |
| **Ops** | Git · Linux / Bash · Vercel |
