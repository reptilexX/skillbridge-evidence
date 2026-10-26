# SkillBridge Evidence

Evidence-based competency verification for students. Instead of trusting self-reported CV skills, the system gives a hands-on task, scores the submission with deterministic checks plus an LLM rubric, finds the exact gap, and issues a short follow-up task. Passing updates an auditable competency record.

**Live demo:** <your Vercel URL>
**Video:** <your YouTube URL>

## Flow
claim → live task → test + rubric evaluation → gap detected → 5-minute micro-task → verified record

## What is in this repo
- `index.html`: working demo of the SQL debugging scenario (checks run in the browser)

## Planned full version
- FastAPI backend with sandboxed Pytest execution
- LLM rubric scoring (Claude) and micro-task generation
- Bangla/English task and feedback support
- Employer view of evidence logs

## Run locally
Open `index.html` in a browser. No build step.

## Deploy
Vercel: import this repo as a static site. Or enable GitHub Pages on the main branch.
