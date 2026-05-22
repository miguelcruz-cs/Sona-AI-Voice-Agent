# Sona AI Voice Agent

**AI voice agent knowledge architecture — live implementation on mpascualcruz.com using Quo/Sona.**

> This is a portfolio case study, not an open-source project. The configuration documented here is a real, live deployment — the agent fields calls 24/7 at the number listed below.

---

## What This Is

A live AI voice agent configured through [Quo](https://quoapp.com) (formerly OpenPhone) using their Sona AI feature. The agent is deployed as a hiring-focused contact point for [mpascualcruz.com](https://mpascualcruz.com) — designed to answer questions about background, experience, and availability at any hour, across any time zone.

**Try it:** Call **(438) 801-1115** — Sona will answer.

---

## Case Study

The full case study — including context, approach, outcome, and the step-by-step setup guide — is published at:

**→ [miguelcruz-cs.github.io/Sona-AI-Voice-Agent](https://miguelcruz-cs.github.io/Sona-AI-Voice-Agent/)**

---

## What's in This Repo

| File | Description |
|------|-------------|
| `index.html` | Full case study page (GitHub Pages) |
| `sona-ai-voice-agent.png` | Screenshot artifact — call flow and knowledge architecture in Quo |
| `README.md` | This file |

---

## Architecture Overview

The implementation has three layers:

**1. Call Flow**
All incoming calls route to Sona. Fallback path: voicemail. Jobs handle edge cases — escalation requests, out-of-scope questions, and message capture.

**2. Knowledge Pages (3 total)**
- Core professional bio and background
- Work experience and AI capabilities breakdown
- Scope, availability, and booking instructions

**3. Greeting & Scope Design**
The greeting was written to orient callers immediately. Caller history is enabled — repeat callers don't re-introduce themselves. The agent explicitly scopes what it will and won't answer, preventing hallucination on out-of-range questions.

---

## Setup Guide

The full step-by-step configuration guide with annotated screenshots is available on Scribe:

**→ [Read the Setup Guide](https://scribehow.com/viewer/Configuring_Sona_Call_Flow_and_Knowledge_Settings__6AUpAAPNQ0a1zIK58qboAg)**

Covers: plan requirements, call flow editor, Sona placement, knowledge page setup, Jobs configuration, and the most commonly missed step (toggling Knowledge pages on under "Shared with Sona").

---

## Key Decision: Why This Counts as a Case Study

Sona wasn't built from scratch — it's a feature inside Quo. The case study isn't about building AI. It's about **applying AI systems thinking** to a real use case:

- Defining knowledge scope (what the agent knows vs. what it shouldn't attempt)
- Designing escalation paths (when AI hands off to human, and how)
- Writing greetings and instructions that produce consistent, on-brand responses
- Evaluating agent quality using the same criteria you'd apply to a human rep

These are the same decisions made when deploying AI in a support environment. The portfolio just makes them visible.

---

## Tools Used

| Tool | Role |
|------|------|
| **Quo / Sona AI** | Voice agent platform — the core implementation |
| **Scribe** | Step-by-step setup documentation with screenshots |
| **CleanShot X** | Dashboard screenshot (2x, PNG) |
| **ElevenLabs** | Voiceover for the portfolio subpage |
| **Claude** | Knowledge page drafting, copy refinement |

---

## Related Case Studies

| Case Study | Connection |
|------------|------------|
| [Customer Service Flow](https://github.com/miguelcruz-cs/Customer-Service-Flow) | The resolution framework Sona's escalation paths are based on |
| [Quality Evaluation Rubric](https://github.com/miguelcruz-cs/Quality-Evaluation-Rubric) | AI agent quality is evaluated using the same rubric dimensions as human agents |

---

Miguel Cruz · [mpascualcruz.com](https://mpascualcruz.com) · Support & Enablement Systems · 2026
