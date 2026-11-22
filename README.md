# ESAT Prep

Interactive **ESAT** (Engineering & Science Admissions Test) practice — question bank, explanations, and progress tracking.

Built for students who need clean math rendering and a calm revision loop, not a dump of PDFs.

## Features

- Structured question bank with validation scripts
- KaTeX / markdown explanations
- Interactive math (Mafs) where graphs help
- Auth + progress via Supabase
- Vite + React frontend

## Stack

JavaScript · React · Vite · Supabase · KaTeX · Framer Motion · Vitest

## Local

```bash
cp .env.example .env   # fill in Supabase keys (never commit .env)
npm install
npm run dev
```

```bash
npm run validate:content   # question-bank checks
npm test
```

## Note

This is the public engineering face of the admissions-test tooling. Live product branding may live at a separate domain — this repo is the source.

---

Built by [Ahmed Mustafa](https://github.com/bya7med).
