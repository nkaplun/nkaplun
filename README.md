# Nicholas Kaplun

Forward Deployed AI Engineer at **Zoolatech** and MS in Artificial Intelligence student at **Northeastern University** (Silicon Valley campus, graduating Dec 2027). Before engineering I spent three years as a product manager, so I like working close to the people who use what I build.

## What I build at Zoolatech

Most of my production work is in private company repos, so here is what it does:

- **Case-study assistant.** Answers questions over 100+ internal case-study documents with cited, source-linked answers, delivered in Slack. Runs on Google Cloud Run, uses Google Drive as the source of truth, and re-indexes weekly. Also generates sales decks through the Google Slides API.
- **Evaluation and guardrails.** Tracks correctness, latency, cost, and token usage. Includes a deterministic check that blocks invented case studies and a regression suite, built from real user requests, that runs before every deploy.
- **Outreach automation.** n8n workflows that write personalized LinkedIn messages and cold emails. Processed 2,500+ prospects and produced 5,000+ outreach assets at under $0.03 per prospect, saving about 300 hours of manual work.

## Featured project

**[Casebook](https://github.com/nkaplun/casebook)**: a public, rebuilt version of the case-study assistant above. A Slack bot finds the past projects that fit a sales prospect and builds a pitch deck from them. Code checks block invented case studies and any number on a slide that isn't in its source. Includes offline tests and a live eval suite. Python, Claude and OpenAI APIs, Slack Bolt, python-pptx.

## School projects

| Project | What it does | Stack |
|---|---|---|
| [Personae](https://github.com/nkaplun/personae) | Finds customer segments with PCA and K-means and describes each as a marketing persona, with an automated check that every number cited is real ([live app](https://personae.onrender.com/)). Team of 3; I led the persona layer and the Flask app. | Python, scikit-learn, Flask, Claude API |
| [VisaHire](https://github.com/EddyJJHuang/VisaHire) | Reads a resume and surfaces employers likely to sponsor an H-1B. **2nd Runner-Up of 20 teams**, NU Silicon Valley Hackathon 2026. Team project. | React, TypeScript, Python, LLM |
| [Penny](https://github.com/EddyJJHuang/Penny) | Personal finance tracker that categorizes bank transactions with local rules plus Gemini (85%+ accuracy) and suggests savings. Team project. | Python, FastAPI, React, Docker |
| [ROAM](https://github.com/EddyJJHuang/ROAM) | Plans a group's day in a new city: picks the itinerary that maximizes group satisfaction within budget and time, using dynamic programming and Dijkstra. With Jiajun Huang. | Python, Flask, React |

## Tools

Python · SQL · JavaScript · FastAPI · Pydantic · React · Docker · Google Cloud Run · n8n · Claude, OpenAI, and Gemini APIs

[LinkedIn](https://www.linkedin.com/in/nicholas-kaplun/)
