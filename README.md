# Wisdom Conversation Prep

**Status:** v0.1 shipped 2026-05-17, in response to Elijah's 2026-05-16 commitment to make wisdom-asking a life practice. Companion to `~/.claude/projects/.../memory/plans/wisdom-asking-practice.md`.

## What it does

A 5-minute prep tool for a conversation with someone wiser than you. The user inputs:
- Mentor name + role + years-ahead
- The one specific thing they're wrestling with
- 1-2 domains the conversation touches (marriage, career, faith, money, parenting, friendship, mental health, failure/adversity, vocation, time/discipline)
- Any context

Output:
1. **The ask** — a copy-paste text/DM to send first to schedule the conversation
2. **First-60-seconds opener** — what to say on-site to frame the conversation
3. **7 customized questions** — pulled from the curated question library, weighted to chosen domains
4. **The closing move** — "What's the question I should have asked you but didn't?" — surfaces the most valuable answer of the conversation
5. **Post-call reflection template** — pre-filled markdown for the wisdom-log
6. **Follow-through reminders** — 24h thank-you, 30-day check-in, 1-year handwritten note

## Why this exists

The wisdom-asking practice methodology has 80+ questions in a static library (`memory/plans/wisdom-asking-practice.md`). That library is reference; this tool is contextualization.

The pattern most people miss: showing up to a wisdom conversation without specific questions = "tell me about your life" = surface answers. Showing up with 5-7 specific calibrated questions = the kind of conversation the mentor will remember + want to have again.

## How to use

Open `index.html` in any browser. ~5 minutes per conversation. Result stays in browser. Copy-paste the parts you need.

## Pairs with

- `~/.claude/elijahbot/wisdom-log.md` — append the post-call template here
- Phone command `wisdom <person> | <topic>` then `learned <text>` — same purpose, mobile version

## Cohort to use this on (per the methodology doc)

1. Faith: Pastor Matt (Stonebridge) — first conversation by Jun 13
2. Business: Clint Reeves / Uncle Will Bush / Dad
3. Marriage: Pastor Matt + wife; an older couple at Stonebridge
4. Academic: Reza Hosseini Ghomi (post-Tue call); Dr. Mohler (UA President)
5. Older/wiser: an older man at Stonebridge in the 60-80 age range

## Sister tools

- `~/ai-readiness-test/` — diagnostic for businesses (revenue funnel)
- `~/ai-cost-calculator/` — quantification for businesses (revenue funnel)
- `~/calvinism-test/` — TULIP self-assessment (theological clarity)
- `~/wisdom-prep/` — THIS (life-practice infrastructure)

## v0.2 ideas

- Save mentor profiles so re-prep is faster on subsequent conversations
- Conversation history (last N convos with this mentor shown)
- Question bank per mentor (your questions for them specifically that you haven't asked yet)
- Multi-mentor mode (preparing for a panel/dinner with multiple wise people)
- Export to PDF for printing before a coffee meeting

## How to ship

Same pattern as other standalone tools. Open `index.html`. Or port to PV site as `app/wisdom-prep/page.tsx` later if Elijah wants this public-facing.
