# Dhyan — Reddit Brand & Keyword Monitoring Platform

## 🚧 Status: In Development

This project is currently in the pre-development phase.
We have submitted an application for Reddit Data API access
and are awaiting approval before active development begins.
No Reddit API calls are being made at this time.

---

## What is Dhyan?

Dhyan is a SaaS (Software as a Service) platform that allows
brands, businesses, and marketers to monitor Reddit for
real-time mentions of their brand name, products, and
competitors.

**Example use case:**
A sunscreen brand wants to know what Reddit users are saying
about their product across communities like r/SkincareAddiction
and r/beauty. Dhyan lets them track those keyword mentions in
a single dashboard — without having to manually browse Reddit.

---

## How It Works

- The brand enters their keywords (e.g. brand name, product
  name, competitor names)
- Dhyan scans relevant public subreddits for matching posts
  and comments
- Mentions are displayed in a clean dashboard with sentiment
  context and timestamps
- The brand uses these insights to understand customer
  feedback and competitor activity

---

## Key Principles

- ✅ Read-only — we never post, comment, vote, or interact
  with Reddit
- ✅ Public data only — no private messages or restricted
  subreddit access
- ✅ No user data collection from Reddit
- ✅ Full compliance with Reddit's Data API Terms of Service
- ✅ Content attribution always links back to the original
  Reddit post

---

## Intended API Usage

- **Access type:** Reddit Data API (read-only)
- **Rate limit target:** Within 100 QPM (free tier)
- **Data accessed:** Public posts and comments only
- **Subreddits:** Public subreddits relevant to each user's
  industry keywords
- **Storage:** No permanent storage of Reddit content

---

## Tech Stack (Planned)

- Backend: Node.js / Python
- Reddit Integration: PRAW (Python Reddit API Wrapper)
- Frontend: React.js
- Database: PostgreSQL

---

## Contact

- Website: https://dhyaan.carrd.co
- Developer: Ravi Rathod
- Reddit: u/ugh-shit

---

*This repository will be updated with source code once
Reddit Data API access is approved and development begins.*
