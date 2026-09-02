# AI in VC — Sprint Portfolio Presentation

**Project:** VC Dealflow Screening Agent  
**Focus:** AI-powered first-pass venture screening

---

## 1. What I built

I built a thesis-driven AI screening workflow for evaluating enterprise AI startups. Instead of using AI only as a chatbot, the workflow turns a startup's source materials into a structured, reviewable investment screen.

**Input → Analysis → Decision support**

Startup deck / memo / website materials  →  structured extraction  →  thesis fit + evidence analysis  →  diligence gaps  →  Advance / Watch / Pass

The workflow is designed to keep the investor in control: AI prepares the analysis and surfaces questions; the investor makes the final decision.

## 2. My VC Workspace

My VC Workspace is organized around a specific investment thesis:

- **Stage:** Series B, with selective flexibility around adjacent stages
- **Geography:** North America, with selective interest in India, Singapore, and China
- **Sector:** Enterprise AI, AI infrastructure, and applied AI software
- **Founder profile:** Technical founders building B2B AI companies
- **Core signals:** Enterprise pain, product pull, technical differentiation, defensibility, venture-scale market potential, and credible economics

I added reusable instructions and documentation so the AI evaluates opportunities consistently rather than starting from a blank prompt each time.

## 3. Push Your Skills challenge

For the challenge, I built a VC screening agent/workflow that:

1. Reads startup materials.
2. Extracts company, product, market, traction, team, business model, and funding information.
3. Labels information as **Fact / Inference / Unknown**.
4. Scores thesis fit.
5. Tests technical differentiation and defensibility.
6. Identifies the five highest-priority diligence questions.
7. Produces an **Advance / Watch / Pass** recommendation.
8. Creates a concise investment-screening memo.

The full workflow and sample are in this repository's `vc-screening-agent` folder.

## 4. The AI output that changed the workflow

The strongest example was the ability to turn a messy startup information set into a structured investment screen while simultaneously identifying what the materials did **not** establish.

A manual first pass would normally require reading the materials, taking notes, organizing the facts, comparing them with the thesis, writing a preliminary view, and then separately thinking through diligence questions. The workflow compresses those activities into one repeatable process and forces the output to distinguish evidence from inference.

The important improvement is not simply speed. It is **consistency**: the same thesis, evidence rules, scoring framework, and diligence structure can be applied repeatedly across companies.

## 5. What I learned

- AI is much more useful when given a defined workflow than when asked for an open-ended “investment opinion.”
- Context and documentation materially improve the usefulness of an AI workspace.
- The best VC workflows preserve uncertainty instead of allowing the model to fill gaps with plausible-sounding assumptions.
- Agentic workflows are strongest for repeatable, structured, tool-based work; human judgment remains important for ambiguous investment decisions. OpenAI's current guidance similarly emphasizes repeatability, clear outputs, tools, and human approval/guardrails for agent workflows. [Source](https://openai.com/academy/workspace-agents/)
- AI can move the investor's time from mechanical synthesis toward deciding what actually matters.

## 6. Working Group feedback

**Feedback status:** I have not fabricated peer feedback. This section should be completed immediately after the Working Group presentation with the group's actual comments.

Suggested capture format:

- **Most impressive:** ______________________________
- **Most useful feature:** ___________________________
- **Biggest improvement suggested:** _________________
- **Question/concern raised:** _______________________
- **Feature peers wanted next:** _____________________

## 7. Next steps

I want to evolve this from a screening workflow into a broader dealflow system: automated company discovery, source-backed market research, comparable-company analysis, CRM/pipeline updates, and eventually human-approved outreach.

The key constraint will be reliability. As workflows move from analysis into external actions, source quality, permissions, approval checkpoints, and evaluation become increasingly important.

---

**Portfolio link:** https://github.com/nvatsya1/commandcenter/tree/main/vc-screening-agent
