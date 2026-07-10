# Hi, I'm Arley 👋

Software Engineering Co-op student at Concordia University, building practical software across AI products, robotics, cybersecurity, and developer tooling.

🎬 **Research Film:** The Boring Layer  
https://youtu.be/dcG4GsKA-uo

## What I build

I like projects that turn messy technical systems into usable tools: AI assistants, robotics software, reproducible security environments, and full-stack applications with clear product value.

## Current research: The Boring Layer

An ongoing research program on AI agent governance, conducted across three public repositories. It does not claim to solve AI trust. It asks a narrower question and reports what actually happened.

The question: before AI agents touch consequential systems such as funds transfers, can the trust layer be built the way boring infrastructure is built—deterministic, auditable, and honest about what it has not proven?

- [agent-preflight](https://github.com/Arley100/agent-preflight): classifies an agent's intended action by domain and risk tier, then injects matching governance rules before it acts. Deterministic, with no LLM in the pipeline.
- [disproof-harness](https://github.com/Arley100/disproof-harness): a falsification engine for executable claims. Survival must be earned through paired controls; the words verified and proven are prohibited by an invariant test.
- [knowledge-refinery](https://github.com/Arley100/knowledge-refinery): pre-registered experiments testing whether this governance scaffolding measurably changes agent behavior.

First finding, Milestone 1: the naive baseline achieved 96.25% primary accuracy, while the evidence-refined rulebook achieved 87.5%, missing the pre-registered requirement that refinement improve performance by at least 10 percentage points. Both safety guardrails held in every run. The deficit was concentrated in two of sixteen scenarios, and the null result is published with its full evidence chain, frozen hashes, and reproducible bootstrap.

Interesting so far. Definitively solved: nothing. That is the point of pre-registering the experiment.

## Selected Projects

### SpendGuard AI
AI spending advisor for business card transactions.  
Built with TypeScript, Next.js, and Claude API, with a focus on deterministic financial analysis and AI narration guardrails.
Repo: [spendguard-ai](https://github.com/Arley100/spendguard-ai)

### ROS 2 / CAN Bus Rover Work
Rover-status software work for Space Concordia Robotics.  
Maps rover state information into CAN-frame-ready status signals for the SR-32 Status Indicator Light.
Repo: [ros2_ws](https://github.com/Arley100/ros2_ws)

### NSEC CTF Toolkit
Reproducible Docker-based cybersecurity environment with 60+ preinstalled tools.  
Built to make CTF practice faster, cleaner, and easier to reproduce.
Repo: [nsec-ctf-toolkit](https://github.com/Arley100/nsec-ctf-toolkit)

### ShipReady
Hackathon project-readiness advisor built during MPC Hacks 2026.  
Team fork, I built the backend + scoring engine + deployment.
Analyzes GitHub repositories and gives judge-facing feedback on README quality, security, setup, UX, and demo readiness.
Repo: [shipready](https://github.com/Arley100/shipready)

## Current Focus

- AI agent governance and verification research
- AI-assisted software products
- Full-stack TypeScript applications
- ROS 2 and robotics software
- Docker-based developer tooling
- Cybersecurity and reproducible environments

## Tech

TypeScript · JavaScript · Python · Java · Docker · React · Next.js · FastAPI · ROS 2 · CAN bus · GitHub Actions
