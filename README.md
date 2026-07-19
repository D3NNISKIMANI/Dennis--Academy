# Dennis Academy — Splunk Core Certified User Practice Console
link https://d3nniskimani.github.io/Dennis--Academy/
A self-contained, mobile-friendly practice exam tool for the Splunk Core Certified User (SPLK-1001) certification. Built as a single HTML file — no backend, no database, runs entirely in the browser.

## Question Bank

**480 total practice questions**, drawn from two sources:
-Questions are written to align with the official Splunk exam blueprint's 8 domains

All questions are organized across the same 8 official SPLK-1001 blueprint domains, each weighted to match the real exam's percentage breakdown:

| Domain | Weight |
|---|---|
| Splunk Basics | 5% |
| Basic Searching | 22% |
| Using Fields in Searches | 20% |
| Search Language Fundamentals | 15% |
| Basic Transforming Commands | 15% |
| Reports and Dashboards | 12% |
| Lookups | 6% |
| Scheduled Reports & Alerts | 5% |

## Features

- **Domain-based drilling** — pick any of the 8 blueprint domains individually, or the Full Bank combined
- **Two study modes**
  - *Practice* — instant right/wrong feedback with explanations where available
  - *Exam Sim* — timed, no feedback until submission, closer to real test-day conditions
- **Review Missed** — automatically builds a queue of every question you've gotten wrong, across sessions
- **Question Navigator** — jump to any question mid-drill, flag questions for review, see answered/unanswered status at a glance
- **Session History** — a running log of every past attempt: date, domain, mode, score, time
- **Progress persists locally** in the browser (no account or sign-in needed)

## How it's built

Single `index.html` file — vanilla JavaScript, no frameworks, no build step. Question data is embedded directly in the file. Progress is saved via `localStorage`, so it works fully offline once loaded.

## Usage

Open the live link on any phone, tablet, or laptop. Pick a domain or the Full Bank, choose a mode and length, and start drilling.

## A note on source material

This is independently-built practice content, not official Splunk exam material. It's useful for reinforcing concepts and terminology, not a guaranteed predictor of the current exam's exact questions.
