# VC Screening Agent

A lightweight AI workflow for first-pass venture screening. It is designed for a Cowork-style action-taking workflow: the agent receives a startup memo/deck, extracts the core facts, evaluates fit against an investment thesis, identifies missing diligence, and produces an IC-ready screening note.

## Workflow

1. Read the startup materials in the working folder.
2. Extract company, market, product, traction, business model, team, funding, and risks.
3. Score the opportunity against the thesis without inventing missing facts.
4. Separate **evidence** from **inference**.
5. Identify the 5 highest-priority diligence questions.
6. Produce a recommendation: **Advance / Watch / Pass**.
7. Save the final screen to `screening-output.md`.

## Investment thesis used for the challenge

- **Stage:** Series B/C/D, with selective flexibility around adjacent stages.
- **Geography:** North America, with selective interest in India, Singapore, and China.
- **Sector:** Enterprise AI, AI infrastructure, and applied AI software. Fintech B2B, Femtech, and Climate Tech.
- **Founder profile:** Technical founders building B2B products with defensible technical or workflow advantages.
- **What matters:** Clear enterprise pain, evidence of product pull, credible path to durable margins, meaningful technical differentiation, and a market large enough to support venture-scale outcomes.

## Agent prompt

Use the prompt in `agent-prompt.md` as the Cowork/agent instruction. Give the agent a folder containing a startup deck, memo, website export, or other source materials. The agent should work through the files, write the screening note, and stop for human review before any external outreach or irreversible action.

## Challenge run

The included `sample-startup.md` is a synthetic company used to test the workflow. The sample demonstrates how the agent handles incomplete information, distinguishes facts from assumptions, and reaches a thesis-specific recommendation rather than simply summarizing the company.

## Research used

The workflow design was informed by Anthropic's 2026 Cowork materials, which describe Cowork as a desktop environment for multi-step work across local files and connected applications, and by Anthropic's guidance on agent harnesses, tools, environments, and human oversight.
