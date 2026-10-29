# Arley Ndaribike

**Software Engineering Co-op student at Concordia University** | Montréal, QC

I build practical software where reliability matters: AI products whose outputs can be checked, robotics software, and reproducible security tooling. My current research asks how far deterministic, auditable infrastructure can go in governing AI agents, and I publish the results, including the ones that did not work.

[Portfolio](https://arley-ndaribike-portfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/arley-ndaribike-1b1a431a1) · [Research film: The Boring Layer](https://youtu.be/dcG4GsKA-uo)

---

## Research: The Boring Layer

An ongoing research program on AI agent governance, conducted across three public repositories. It does not claim to solve AI trust. It asks one narrow question: before an agent touches a consequential system such as a funds transfer, can the trust layer be built the way boring infrastructure is built, meaning deterministic, auditable, and explicit about what it has not proven?

| Repository | Purpose |
| --- | --- |
| [agent-preflight](https://github.com/Arley100/agent-preflight) | Classifies an agent's intended action by domain and risk tier, then injects matching governance rules before the agent acts. Deterministic, with no LLM in the pipeline. |
| [disproof-harness](https://github.com/Arley100/disproof-harness) | Falsification-first claim checker with a closed five-verdict vocabulary and paired controls. Survival is rationed; disproof is not. |
| [knowledge-refinery](https://github.com/Arley100/knowledge-refinery) | Pre-registered experiments testing whether this governance scaffolding measurably changes agent behavior. |

**Milestone 1 result: null.** The naive baseline reached 96.25% primary accuracy and the evidence-refined rulebook reached 87.5%, missing the pre-registered requirement of a 10-point improvement. Both safety guardrails held in every run. The deficit was concentrated in two of sixteen scenarios, and the result is published with its full evidence chain.

agent-preflight and disproof-harness are early (v0.1) releases, and each repository states plainly what it does not claim.

---

## Selected projects

| Project | What it is | Stack |
| --- | --- | --- |
| [memory_360_NOVA](https://github.com/Arley100/memory_360_NOVA) | AI-built project memory in which every sentence is checked against its source. **Winner, CodeML 2026** (Loto-Québec, Challenge 2: Project 360 / NOVA). Built with a team. | TypeScript, Next.js, Claude API |
| [nineforge](https://github.com/Arley100/nineforge) | Unit testing for the physical world: a deterministic validation layer that simulates, scores, and stress-tests AI-generated machine programs (CNC G-code) before they touch real hardware. | TypeScript |
| [spendguard-ai](https://github.com/Arley100/spendguard-ai) | AI spending advisor with a narration guard: the model explains only engine-computed numbers and never invents them. Built for Brim Financial. | TypeScript, Claude API |
| [ros2_ws](https://github.com/Arley100/ros2_ws) | ROS 2 package that maps rover states to CAN frames for the SR-32 Status Indicator Light, for Space Concordia Robotics. | ROS 2, CAN bus |
| [nsec-ctf-toolkit](https://github.com/Arley100/nsec-ctf-toolkit) | Reproducible Docker-based CTF environment with 60+ pre-installed security tools. | Docker |
| [shipready](https://github.com/Arley100/shipready) | Pre-flight readiness advisor for hackathon projects: scores a GitHub repo across five dimensions and generates a judge-ready pitch. Built at MPC Hacks 2026; I built the backend, scoring engine, and deployment. | FastAPI, React |

Also: [cortex-deck](https://github.com/Arley100/cortex-deck), a focus-recovery console with six cognitive drills and honest scoring against your own baseline (React, TypeScript, IndexedDB), and [offline-code-tutor](https://github.com/Arley100/offline-code-tutor), an offline-first coding assistant benchmark using llama.cpp and GGUF models.

---

## Technical stack

| Area | Tools |
| --- | --- |
| Languages | TypeScript, JavaScript, Python, Java |
| Web and APIs | React, Next.js, FastAPI, Claude API |
| Robotics and embedded | ROS 2, CAN bus |
| Infrastructure and tooling | Docker, GitHub Actions |
| Security | Reproducible CTF environments, tooling in Docker |
