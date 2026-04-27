# Agentic Architecture for Vibe Founders

The 5-layer questionnaire system, dual-model routing (smart brain plus cheap hands), parallel task fan-out, and a 90-day build plan for solo founders shipping agentic AI products in 2026. Builder-to-builder, no enterprise pretensions.

---

> **Part of the AI BrandFactory open toolkit.**
> Free to use and adapt with attribution.
> More tools, templates, and AI systems at [aibrandfactory.com](https://www.aibrandfactory.com)

---

## What's Inside

- The vibe founder vs enterprise architect frame. Why most agentic AI content is written for 50-engineer teams that do not exist. The 5 design philosophies that flip when you ship solo: build small, ship in days not quarters, boring infrastructure, route by cost, user as co-author.
- The 5-Layer Questionnaire Architecture in full. Layer 1 captures intent (2 to 3 questions). Layer 2 surfaces unknowns. Layer 3 proposes answers pre-filled from web research and asks the user to confirm. Layer 4 locks context into one prompt block. Layer 5 executes. Worked example: a SaaS launch.
- Dual model routing. Smart brain plus cheap hands. Use Claude Sonnet or GPT-4.5 for planning, structure, and judgement. Use Gemini Flash or GPT-mini for API payloads, format conversions, and boring transforms. The 3-line decision rule and a 200-task batch cost-math showing 80 percent savings.
- Parallel task fan-out. When the context is locked, fan out 200 tasks concurrently instead of sequentially. Concurrency caps that respect API rate limits. Exponential backoff retry with a 3-attempt ceiling. Partial-failure handling so you ship the wins and queue the misses for a clean second pass.
- State, storage, and resumability. Why agentic systems must survive a crash mid-batch. The 3-tier storage model: in-memory for current task, JSONL for within-session resume, persistent DB for across-session resume. Worked example: a 200-task batch where task 74 fails and the system picks up at 75.
- The vibe founder's toolkit. Claude Sonnet for planning, Haiku for routing, Gemini Flash for parallel payloads, a small Node.js or Python orchestrator (no framework), JSONL for state, Railway for deployment. Operational cost under $50 a month at 100k tasks. Why LangChain is over-engineered here.
- The 90-day build plan, week by week. Week 1 specs the questionnaire layers. Weeks 2 to 3 build the dual-model router. Weeks 4 to 6 ship parallel fan-out plus state. Weeks 7 to 9 run a production workload with one paying client. Weeks 10 to 13 iterate on what broke. Closing 3-line ship-it call.

## Files

- `playbook.md` — full playbook source in Markdown
- `playbook.pdf` — rendered PDF for download / sharing
- `copy.json` — title, hook, benefits, schema for re-publishing
- `image-prompts.json` — Gemini prompts for the brand 4 images (cover, hero, og, notion-cover)
- `embedded-prompts.json` — Gemini prompts for the embedded tactical visuals


## Read or Download

- Live page: [files.aibrandfactory.com/playbooks/agentic-architecture-vibe-founders](https://files.aibrandfactory.com/playbooks/agentic-architecture-vibe-founders)
- Notion duplicatable template: [https://massiveimpact.notion.site/Agentic-Architecture-for-Vibe-Founders-34ffb27e6634816d9d06da6b1fb5014f](https://massiveimpact.notion.site/Agentic-Architecture-for-Vibe-Founders-34ffb27e6634816d9d06da6b1fb5014f)

## Use

Fork this repo, edit `playbook.md` for your own audience or customize the prompts in `image-prompts.json` to re-skin for your brand. Attribution required per LICENSE.

## License

Free to use with attribution. See [LICENSE](LICENSE) for details.

Built by [AI BrandFactory](https://www.aibrandfactory.com), tools and systems for AI-powered content businesses.
