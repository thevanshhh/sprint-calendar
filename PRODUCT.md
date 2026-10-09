# Sprint Calendar — Product Context

## Purpose & Goal
A hyper-focused founder sprint calendar and execution dashboard designed to manage daily hour-by-hour operational momentum toward two core objectives:
1. **Financial Target:** Generate **$2,000 cash** within the sprint window (October 9 to November 30).
2. **Physical Target:** Drop body weight from **70 kg to 66 kg** by January 9.

## Operating Context
- **User:** Solo founder / operator executing high-leverage daily routines (audits, in-person walk-in business discovery, outbound emails, physical health, skill building, and content creation).
- **Daily Operating Rhythm:**
  - Day starts at 8:00 AM with wake-up, physical reset, and breakfast.
  - Morning focus: Go Leverage audit production & delivery.
  - Afternoon focus: Walk-in merchant discovery (10 genuine conversations/day).
  - Evening focus: Appointy email prospecting and follow-ups.
  - Night focus: Decompression walk, book reading, camera practice, reel creation, skill building, and daily market intelligence synthesis.
  - Hard stop at 2:00 AM.
- **Operating Day Boundary:** Uses a 4:00 AM day cutover (`adj = new Date(now.getTime() - 4 * 3600 * 1000)`) to correctly align late-night productivity (up to 2 AM) with the intended calendar day.

## Key Targets & KPIs
- **Audits Sent:** 1 high-quality audit/day.
- **Conversations:** 10 genuine problem-discovery conversations/day.
- **Outbound Emails:** 10 targeted emails/day.
- **Reading:** 10 pages/day.
- **Content:** 1 reel/day.
- **Speaking Practice:** 5 minutes of camera practice/day.

## Core Constraints
- **Offline & Local-First:** All schedules, checklist completions, and scoreboard tallies persist in browser `localStorage` (`KEY: "sprint-cal-v3"`).
- **Fast Execution:** No slow backend or login barriers; instantly available on desktop and mobile browsers.
