# Hi, I'm Harshmay 👋

Software engineer working across full-stack web, data, and applied AI. I build
internal tools, marketing sites, and data-driven apps end to end — from schema
and API to the UI people actually use.

**Stack I reach for:** TypeScript · Next.js / React · Node/Express · PostgreSQL
(+ PostGIS) · Sanity · Supabase · Python · AWS · Vercel

---

## Selected work

### Eleno — Leadership Operations Tool
Internal operations app for an AI & automation consultancy. Tracks billable vs
total hours per engineer, per client, per fortnight, so leads can watch
utilisation targets, approve timesheets, and manage finance — replacing manual
spreadsheet ops.
- **My role:** built the app end to end — role-gated engineer/lead views,
  timesheet submission and approval flow, utilisation reporting.
- **Stack:** Next.js, TypeScript, Playwright.
- _Private repo (company work). Happy to walk through it on request._

### Eleno — Marketing Site
Marketing website for Eleno, an Australian AI & automation engineering firm.
Leads with proven consulting work as the credibility anchor, then introduces the
subscription platform.
- **My role:** built the site and the content model, including an embedded
  Sanity Studio at `/studio` for the team to edit copy.
- **Stack:** Next.js, Sanity CMS, TypeScript.
- _Private repo (company work)._

### Wayfynd — Sensory-budget route scoring
Scores walking routes in the Melbourne CBD by *sensory cost*, not just time,
using City of Melbourne open data (pedestrian counts, sensor locations,
landmarks, refuges). Warns commuters before a crowd surge reaches them and points
to a nearby quiet refuge.
- **My role:** full monorepo — React SPA, Express API, and a nightly ETL job
  that fetches and upserts the open datasets on a schedule.
- **Stack:** React (Vite), Node/Express, PostgreSQL 16 + PostGIS (RDS),
  AWS (S3/CloudFront + EC2, EventBridge cron), Turborepo/pnpm.

### Weekly Budget
A zero-dependency budgeting web app: one `index.html`, no build step. Plan income
by bucket into weekly figures, log each expense so it sorts into its category
against a weekly ideal, then roll weeks up into a monthly trend. Backup/restore to
JSON.
- **My role:** designed and built the whole thing, including the fortnightly
  pay-cycle logic and a later Supabase-backed sync branch.
- **Stack:** vanilla HTML/CSS/JS, localStorage, Supabase (sync build), Vercel.
- 🔗 **Live:** https://supabase-sync-rouge.vercel.app

---

## Data & AI

### F1 AI Coach
An AI-powered coaching app for Formula 1 strategy. Built on real race data — lap
times and pit stops — to reason about race decisions and surface actionable
insight.
- **Feature — PitWindow:** analyses lap times and pit-stop data to find the
  optimal pit window, with a full report and slides.
- **My role:** built the app and the underlying analysis end to end.
- **Stack:** Python / R data analysis, applied AI.
- _Private repo._

### Tabular Q-Learning (FIT5226)
Reinforcement-learning agent trained with tabular Q-learning, delivered as a
documented notebook.
- **Stack:** Python, Jupyter.

### Ant robot locomotion
Locomotion experiments for a simulated ant robot.
- 🔗 [ant_robot_locomotion](https://github.com/harsh0040/ant_robot_locomotion)

### ACME Tenant Portal
Web app that automates a manual data-entry task for a property-management company.
- 🔗 [acme-tenant-portal](https://github.com/harsh0040/acme-tenant-portal)

---

## Get in touch
- **GitHub:** [@harsh0040](https://github.com/harsh0040)
- **LinkedIn:** [harshmay-prasad](https://www.linkedin.com/in/harshmay-prasad/)
- **Email:** [harshmayprasad@gmail.com](mailto:harshmayprasad@gmail.com)

<sub>Several projects above are private company work; source isn't public, but I'm
glad to talk through architecture and my contributions.</sub>
