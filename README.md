# Applied AI Engineering

Hands-on projects, experiments and notes from my journey into applied AI engineering, from LLM fundamentals to autonomous agents, MCP servers and AI systems in production.

This repository follows the **Applied AI Software Engineering** program (UniPDS), extended with my own study guide and extra exercises. Every module has working code, not just notes.

## About me

I'm a senior full stack developer (frontend-focused) building AI-powered products with React, TypeScript, Next.js, Node.js and NestJS. I'm also the creator of **SafetySwap**, a product I build end to end using spec-driven development and AI coding agents.

- LinkedIn: [your-linkedin](https://www.linkedin.com/in/your-profile)
- Portfolio: [your-site](https://your-site.com)

## Tech stack

| Area | Tools |
| --- | --- |
| Languages | TypeScript, JavaScript, Python (fine-tuning only) |
| Frontend | React, Next.js |
| Backend | Node.js, NestJS |
| LLM APIs | Anthropic (Claude), OpenAI, Google Gemini, OpenRouter, Ollama |
| Agents & orchestration | LangChain, LangGraph, Claude Agent SDK, MCP SDK |
| Data & retrieval | PostgreSQL + pgvector, embeddings, hybrid search |
| ML | TensorFlow.js, Hugging Face, LoRA / PEFT |
| DevOps | Docker, Kubernetes, GitHub Actions, Terraform, AWS |
| AI dev tools | Claude Code, Cursor, Gemini CLI |

## Modules

| # | Module | Highlights | Status |
| --- | --- | --- | --- |
| 01 | [Fundamentals of AI & LLMs](./01-fundamentals) | Neural network from scratch in TensorFlow.js, tokens, embeddings, in-browser ML | Not started |
| 02 | [Generative AI APIs & Prompting](./02-genai-apis-prompting) | Streaming endpoint, structured output, smart OCR, multimodal bot | Not started |
| 03 | [MCP: Model Context Protocol](./03-mcp) | MCP server in TypeScript with auth and rate limiting | Not started |
| 04 | [Autonomous Agents](./04-autonomous-agents) | ReAct vs. Plan-and-Execute, LangGraph agent, multi-agent system | Not started |
| 05 | [AI for UX & UI](./05-ai-ux-ui) | Figma to React, E2E tests driven by an agent via MCP | Not started |
| 06 | [AI for DevOps](./06-ai-devops) | Kubernetes troubleshooting agent, ChatOps bot, AI in CI/CD | Not started |
| 07 | [AI for Project Management](./07-ai-project-management) | RICE prioritization, Monte Carlo delivery forecast, Slack to Jira bot | Not started |
| 08 | [AI System Architecture](./08-ai-system-architecture) | Hybrid RAG, model router, semantic cache, ADRs | Not started |
| 09 | [Data Processing & Fine-Tuning](./09-data-fine-tuning) | JSONL pipeline, LoRA fine-tuning, A/B evaluation | Not started |
| 10 | [AI Security & Governance](./10-ai-security-governance) | Prompt injection red teaming, PII masking, risk matrix | Not started |

**Capstone:** an AI-powered Micro-SaaS with RAG, agents and MCP, deployed to production. It lives in its own repository: [link-to-capstone](https://github.com/your-user/your-capstone).

## Repository structure

```
applied-ai-engineering/
├── 01-fundamentals/
├── 02-genai-apis-prompting/
├── 03-mcp/
├── 04-autonomous-agents/
├── 05-ai-ux-ui/
├── 06-ai-devops/
├── 07-ai-project-management/
├── 08-ai-system-architecture/
├── 09-data-fine-tuning/
├── 10-ai-security-governance/
├── .env.example
└── README.md
```

Each module folder has its own `README.md` with:

- **Goal:** what the module covers.
- **Projects:** what was built and how to run it.
- **Learnings:** key takeaways, trade-offs and what I'd do differently.

## Getting started

Requirements: Node.js 20+, Docker, and API keys for the providers you want to use.

```bash
git clone https://github.com/your-user/applied-ai-engineering.git
cd applied-ai-engineering
cp .env.example .env   # add your API keys
```

Then open a module folder and follow its README.

> Never commit real API keys. `.env` is listed in `.gitignore`.

## How I work

- **Spec first:** every project starts with a short spec (goal, flows, data model, acceptance criteria) that also serves as context for AI coding agents.
- **Small, verifiable tasks:** features are split into steps with a clear "done" check, such as a passing test or a successful build.
- **AI output is reviewed like a pull request:** generated code is read, tested and adjusted before it's committed.
- **Measure, don't guess:** prompts and models are compared on cost, latency and quality with small eval sets.

## License

MIT