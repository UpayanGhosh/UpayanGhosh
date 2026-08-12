<div align="center">

# 👋 Upayan Ghosh

**AI systems engineer building agentic tools, retrieval systems, and developer workflows.**

I work at the intersection of application engineering and applied AI: systems that can understand a task, route it to the right tools, use memory responsibly, and explain what happened well enough for another engineer to trust it.

Currently I work as an Associate Software Engineer at Accenture, building LLM tooling over enterprise SQL Server data with the Claude API and MCP. Outside work I build open-source AI tooling around local-first assistants, codebase intelligence, and agent orchestration.

[![GitHub](https://img.shields.io/badge/GitHub-UpayanGhosh-181717?style=for-the-badge&logo=github)](https://github.com/UpayanGhosh)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Upayan%20Ghosh-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/upayan-ghosh/)
[![X](https://img.shields.io/badge/X-@UpayanGhosh0__0-000000?style=for-the-badge&logo=x)](https://twitter.com/UpayanGhosh0_0)
[![npm](https://img.shields.io/badge/npm-claude--jarvis-CB3837?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/claude-jarvis)

![Profile views](https://komarev.com/ghpvc/?username=UpayanGhosh&style=flat-square&color=58a6ff&label=PROFILE+VIEWS)
![Focus](https://img.shields.io/badge/focus-agentic%20AI-7c3aed?style=flat-square)
![Builder](https://img.shields.io/badge/builder-local--first%20tools-2ea043?style=flat-square)
![Open source](https://img.shields.io/badge/open%20source-shipping-ff7b72?style=flat-square)
![Available](https://img.shields.io/badge/available-immediately-2ea043?style=flat-square)

</div>

---

## 🧭 Focus Areas

**🤖 Agentic engineering**  
Designing tool-using systems that can plan, route, recover, and hand work back to humans with useful context.

**🧠 Retrieval and memory**  
Building RAG and hybrid-memory flows that separate durable knowledge from task-local context, with clear inspection points.

**⚙️ Developer experience**  
Turning confusing codebases and workflows into explainable systems: readable commands, good defaults, sharp docs, and practical automation.

**🔐 Local-first AI**  
Exploring self-hosted and privacy-aware AI workflows where sensitive context stays closer to the developer.

## 🚀 Selected Projects

| Project | What it does | Measured |
| --- | --- | --- |
| [![Synapse-OSS](https://img.shields.io/badge/Synapse--OSS-local%20AI-7c3aed?style=flat-square&logo=github)](https://github.com/UpayanGhosh/Synapse-OSS) | Self-hosted multi-channel AI agent platform (WhatsApp, Telegram, Discord, Slack) with hybrid RAG, 6-provider LLM routing, and durable long-term memory. | Retrieval **P50 243 ms / P95 327 ms** over 200 live-corpus queries · **99.2% peak-RAM cut** replacing in-memory NetworkX with a SQLite triple store · 100% delivery through a 500-message burst · 800+ commits, 3,400+ tests |
| [![tldr-skill](https://img.shields.io/badge/tldr--skill-codebase%20explainer-2ea043?style=flat-square&logo=github)](https://github.com/UpayanGhosh/tldr-skill) | Turns any repository into a self-hosted interactive explainer site: dependency graphs, directory maps, diagrams, and framework-specific recipes. | Handles repos up to **5,000+ files across 15 languages** · **85% inference-cost cut** via static analysis plus parallel workers · **1,000+ npm downloads** |
| [![claude-jarvis](https://img.shields.io/badge/claude--jarvis-intent%20router-CB3837?style=flat-square&logo=npm)](https://github.com/UpayanGhosh/claude-jarvis) | Universal intent router for Claude Code that routes natural-language intents across installed skills using fast-path matching and dynamic SKILL.md discovery. | **2,690 npm downloads** in its first year |
| [![local-qwen-coder-turboquant](https://img.shields.io/badge/local--qwen--coder-8GB%20VRAM-f59e0b?style=flat-square&logo=github)](https://github.com/UpayanGhosh/local-qwen-coder-turboquant) | Runs a 30B sparse-MoE coding model locally on consumer hardware via smart expert offloading and a TurboQuant KV cache. | **262K context on an 8 GB VRAM GPU** · ~29 tokens/sec · OpenAI-compatible local endpoint |
| [![Chat-with-Code](https://img.shields.io/badge/Chat--with--Code-local%20RAG-58a6ff?style=flat-square&logo=github)](https://github.com/UpayanGhosh/Chat-with-Code) | Local RAG pipeline for asking questions about an unfamiliar codebase, using custom chunking into a local Chroma store, answered by a local Ollama model. | Sub-second code-intelligence queries with **100% local data** |

```bash
npm install -g claude-jarvis
```

## 🛠 Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,docker,linux,bash,sqlite,git,githubactions&theme=dark" alt="AI and backend tools" />
  <br/>
  <img src="https://skillicons.dev/icons?i=cs,dotnet,angular,ts,js,html,css,react,flutter,firebase&theme=dark" alt="Application and product tools" />
</p>

**AI / backend:** Python, FastAPI, Pydantic, asyncio, RAG, vector search, agent orchestration, MCP, SQLite, PostgreSQL, Docker, Linux, Bash  
**Application engineering:** C#, .NET, ASP.NET Core, Angular, TypeScript, JavaScript, SQL Server, T-SQL  
**Product prototyping:** React, Flutter, Firebase, CLI tools, npm packages, GitHub Actions  
**Foundations:** C, C++, data structures, system design, debugging, documentation

## 🧩 How I Build

- 🧭 I start from the user workflow, then work backward into architecture.
- 🔎 I prefer small, observable components over hidden magic.
- 🧠 I treat prompts, tools, memory, retrieval, and logs as one system, not separate features.
- 📚 I write for the next engineer: clear setup, explicit tradeoffs, useful failure messages.
- ✅ I care about AI systems that are measurable, debuggable, and maintainable after the demo is over.

## 🔬 Current Questions

I am especially interested in:

- how assistants can build reliable mental models of large codebases;
- how memory should expire, compact, and explain itself;
- how agent routers can choose tools without becoming unpredictable;
- how local-first AI can give developers useful power without unnecessary data exposure;
- how AI coding tools can produce better handoffs, not just faster diffs.

## 📊 GitHub Snapshot

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=UpayanGhosh&theme=github_dark" width="100%" alt="Upayan Ghosh GitHub contribution summary" />
</p>

## 🤝 Open To

**Available immediately** for backend and AI engineering roles: remote, or Kolkata / hybrid.

I work on agentic systems, retrieval and memory, developer tooling, and local-first AI. Claude Certified Architect, Foundations (Anthropic).

📫 **upayan1231@gmail.com** · [LinkedIn](https://www.linkedin.com/in/upayan-ghosh/)

---

<p align="center">
  <strong>Useful AI is not just smart output. It is context, control, observability, and trust.</strong>
</p>
