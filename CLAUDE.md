# CLAUDE.md — Nishant Rana Portfolio (nishantrana.net)

## Project intent
Personal PM portfolio. A static site — NO backend, NO database, NO auth.
Contact stays as mailto: or a serverless form service. Do not add a server.

## Source of truth
`Nishant_Rana_Resume.pdf` (in this repo) is the ONLY source of truth for
work experience — titles, dates, metrics. If anything on the site conflicts
with the resume, the resume wins. When in doubt, ask; do not invent facts.

## The site's job (read this before editing content)
The resume says WHAT I did. This site says HOW I THINK. Do NOT restate resume
bullets. The site complements the resume; it never duplicates it. Every section
should add something the resume can't: reasoning, approach, point of view.

## Career facts (align all sections to these — from the resume)
- AI Product Manager, Sparc — Feb 2026–Present (CURRENT role)
- AI Product Intern, Sparc — May–Dec 2025
- Associate Product Manager, Infosys — Dec 2021–Aug 2024
- Education: Duke MEM, Aug 2024–Dec 2025; B.Tech Bioinformatics
- Flagship project: Tear — multi-agent AI research platform
  (Claude Code, model routing, RAG); cut research time 4 hrs → ~10 min

## DELETE from the current live site (do not preserve)
- KeyPath entirely (no longer current or any role)
- Vitalise Ventures as an employer; its work now sits under Sparc AI Product Intern
- The "10K projected users / Vitalise" framing — resume says 10K reached, at Sparc
- The "Student Consultant · Duke DTI" framing on Sparc metrics
- The Google Drive resume link — self-host the final PDF in this repo instead

## Identity / hero (replace the current "high-impact, user-first" line)
Lead with AI PM positioning, matching LinkedIn:
"AI Product Manager — I build LLM products end to end: RAG, multi-agent
systems, evals, and guardrails." Remove "Operations & Management" hedging.

## Sections to ADD (my content — leave placeholders where marked TODO)
- How I Work / product approach — TODO: Nishant to supply. Core throughline:
  the gap between what customers say they want and what they actually need.
- Leadership & management POV — TODO: Nishant to supply. A short point of view,
  not a bulleted skills list.
- Tools & stack — how I use them, not a logo wall. TODO: Nishant to supply the
  real list + one line each on usage (e.g. Claude Code, RAG+evals, n8n, SQL).
- Tear — full flagship case study (problem → build → evals/guardrails → result).
- Healthcare cards — B.Tech Bioinformatics: colorectal cancer research,
  COVID-19 mortality data analysis. Supports digital-health positioning.

## Reframe existing case studies (the Duke decks)
Lead each with the THINKING (problem → approach → what I'd decide), deck
secondary/embedded. Keep the best 2–3, not all six. Fewer, deeper, cleaner.

## Design (LATER — do content + structure first)
Do NOT restyle before content is locked. Goal: simple, minimal, intentional —
must NOT read as a templated/generated default look. Pick a real typographic
+ color point of view before generating any visuals. Design pass comes last.

## Known open item (flag, don't fix silently)
Infosys dates differ between resume (APM Dec 2021–Aug 2024) and LinkedIn
(APM Jan 2023 + SSE split). Site follows the resume, but this creates a
site-vs-LinkedIn mismatch. Do not "resolve" it by editing — flag for Nishant.

## Working rules
- Use git; make small, reviewable commits so any change can be rolled back.
- One section at a time. Show the diff, let me review, then move on.
- No new dependencies without asking. Keep it static and fast.