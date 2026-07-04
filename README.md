# Hi, I'm Arley 👋

Software Engineering Co-op student at Concordia University, building practical software across AI products, robotics, cybersecurity, and developer tooling.

## What I build

I like projects that turn messy technical systems into usable tools: AI assistants, robotics software, reproducible security environments, and full-stack applications with clear product value.

## Current research: The boring layer

An ongoing research program on AI agent governance, run across three public repositories. It does not solve a problem yet. It asks one and reports what actually happened.

The question: before AI agents touch consequential systems like funds transfers, can the trust layer be built the way boring infrastructure is built, deterministic, auditable, and honest about what it has not proven?

- [agent-preflight](https://github.com/Arley100/agent-preflight): classifies an agent's intended action by domain and risk tier, then injects matching governance rules before it acts. Deterministic, no LLM in the pipeline.
- [disproof-harness](https://github.com/Arley100/disproof-harness): a falsification engine for executable claims. Survival must be earned through paired controls; the words verified and proven are banned by an invariant test.
- [knowledge-refinery](https://github.com/Arley100/knowledge-refinery): pre-registered experiments on whether any of this scaffolding measurably changes agent behavior.

First finding (Milestone 1): the evidence-refined rulebook did not beat the naive baseline. 96.25% vs 87.5% primary accuracy, against a pre-registered bar of +10 points. Both safety guardrails held in every run. The deficit traced to two scenarios out of sixteen, and the result is published as a null result with the full evidence chain, frozen hashes, and a reproducible bootstrap.

Interesting so far, solved: nothing. That is the point of pre-registering.

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
