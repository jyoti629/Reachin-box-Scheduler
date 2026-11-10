# ReachInbox Email Scheduler

Full-stack email job scheduler: **Express + TypeScript**, **BullMQ + Redis** delayed jobs (no cron), **PostgreSQL**, **Ethereal SMTP** (multiple senders), **Elasticsearch** search, live **Bull Board** dashboard, **Slack OAuth** alerts, and a **React + Tailwind** dashboard with **Google login**.

## Run it: step by step

Prerequisites: Node 20+. You also need Postgres and Redis (step 2).

**1. Install everything** (root, backend and frontend; also creates `backend/.env` with a random `JWT_SECRET`)
```bash
npm install
