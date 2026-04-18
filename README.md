# trackai-backend

Backend API for TrackAI — a job application tracker with AI-powered JD-to-resume matching.

## Why I'm building this

As an MS CS candidate entering a high-volume job search, I needed a way to track 100+ applications across companies, sources, and pipeline stages — and a way to quickly evaluate how well each role fits my background before I apply. Rather than use a spreadsheet, I'm building the tool I actually need.

## What it does

TrackAI lets users track job applications through a defined pipeline (Applied → Screening → Technical → Onsite → Offer/Rejected), with full history of status changes, source, referral info, and outcomes. The differentiating feature is an LLM-powered JD matcher — users paste a job description, and the system extracts required skills, compares them against a stored resume, and returns a structured fit score with specific gaps flagged.

## Tech stack

- **FastAPI** — Python async web framework
- **Postgres** — relational database, JSONB for structured LLM output storage
- **SQLAlchemy + Alembic** — ORM and migrations
- **JWT + bcrypt** — authentication, built from scratch
- **Anthropic Claude API** — LLM for JD matching
- **Docker** — local Postgres; Railway for deployment

## Status

In active development. Targeting MVP by April 24, 2026.

## Local setup

Coming once the project is bootstrapped.