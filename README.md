# AgentHire AI

**An Agentic AI platform for smart recruitment: a working prototype.**

AgentHire AI shows how eight cooperating AI agents can support a recruiter from job description to explainable shortlist, while the recruiter stays the final decision-maker.

> **Prototype notice:** All candidates, scores, analytics and fairness figures are illustrative mock data, and the agents are simulated in the interface. No real language model, resume parsing, authentication or database is included. The project demonstrates the design and workflow, not model accuracy.

**Live demo:** https://agenthire-ai-nu.vercel.app/

## The agent pipeline

Job Intelligence → Resume Analysis → Skill Extraction → Candidate Matching → Skill Gap → Interview → Evaluation → Explainability → Recruiter decision

## Features (15 pages)

- Landing page and recruiter dashboard with funnel and match distribution
- AI Agent Control Center with status, purpose, input, output and time for each agent
- Candidate Intelligence with radar chart, evidence list and AI reasoning summary
- Skill Gap analysis with a recommended learning path
- Create Job with simulated AI analysis
- Standard and adaptive interview views (difficulty moves with each answer)
- Candidate comparison using review labels, never "best candidate"
- Analytics dashboard and candidate report page
- AI Recruiter Assistant, live multi-agent monitoring and Agent Pulse ticker
- Smart Resume Parser demo
- Bias and Fairness Monitor (selection-rate ratio against the 0.80 guideline)

## Principles

Explainability, evidence-based analysis, skill-gap detection, adaptive interviews and human-in-the-loop decisions. No candidate is rejected automatically.

## Tech stack

Plain HTML, CSS and JavaScript in a single file (`index.html`, about 40 KB). Hash-based routing, no framework or build step. Inter font from Google Fonts.

## Run locally

Open `index.html` in a modern browser. No installation is needed.

## Deploy to Vercel

```bash
npx vercel          # follow the prompts, answer No to build questions
npx vercel --prod   # production URL
```

## Project structure

```
agenthire-ai/
├── index.html      # complete application (router, pages, mock data)
├── vercel.json     # static hosting config
├── docs/           # project report
└── README.md
```

## Limitations

Mock data only; agent behaviour is simulated; no accuracy or reliability results are claimed; no authentication, database or file upload.

## Future enhancements

Real LLM-based agents with traces, real resume parsing (PDF, DOCX, TXT), authentication and database, a Next.js with shadcn/ui and Recharts rebuild, a candidate portal, and a fairness audit on real anonymised data.

## Disclosure

Developed by Pavan. The initial prototype code and report draft were generated with Claude (Anthropic) from my specification and reviewed by me. [Edit to describe your own review and testing.]

## License

[Choose a license, for example MIT, or remove this section.]
