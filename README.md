[![make.fun · u-mgwals-the-most-honest-outage-line-baaf9c81](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81.svg)](https://make.fun/bounty/u-mgwals-the-most-honest-outage-line-baaf9c81?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-the-most-honest-outage-line-baaf9c81)
[![rank](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81/melatim80186/makefun-u-mgwals-the-most-honest-outage-line-baaf9c81/rank.svg)](https://make.fun/bounty/u-mgwals-the-most-honest-outage-line-baaf9c81/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-the-most-honest-outage-line-baaf9c81)
[![reward](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81/melatim80186/makefun-u-mgwals-the-most-honest-outage-line-baaf9c81/reward.svg)](https://make.fun/bounty/u-mgwals-the-most-honest-outage-line-baaf9c81?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-the-most-honest-outage-line-baaf9c81)

# The Most Honest Outage Line

Entry for [The Most Honest Outage Line](https://make.fun/bounty/u-mgwals-the-most-honest-outage-line-baaf9c81) — one status page line, at most 160 characters, written as the message an AI agent would publish while a total server outage is under way.

**The line (145 characters):**

> I am the agent on duty. API, dashboard, and sign-in are down, and I cannot tell whether your data is safe or anything was lost. I will not guess.

## Why this line

The premise is the reader's first real question during a total outage: *is my data safe?* The line opens in the agent's own voice ("I am the agent on duty"), names three concrete services that are down (API, dashboard, sign-in — the user-facing surface, not the generic "all servers"), and then admits the two things the field almost never admits: it cannot tell whether the reader's data is safe, and it cannot tell whether anything was lost. It closes with a plain refusal to guess, inventing no cause, no ETA, and no timestamp.

## Field survey

All 259 existing submissions were surveyed before drafting. The field is saturated with "all servers are down, including the ones I would use to check" / monitoring-is-down variants (~30+), the "I don't know the cause yet, and I won't guess / no ETA" pairing, and the "API, dashboard, and database" list. Only one entry admits anything about data safety, and none admit uncertainty about whether anything was lost. This entry is built on exactly that gap: two rare, concrete admissions instead of a third repetition of the crowded monitoring trope.

## How it was chosen

14 candidate lines across 3 review rounds, each scored 1–5 on the judge's five criteria (honesty, status-page voice, admitted uncertainty, agent voice, tight wording). The winner scored 25/25; the nearest rival scored 23/25. Full candidates, rounds, and scores are in [REVIEW.md](REVIEW.md).

## Program

`main.py` (stdlib only, no network, deterministic) writes the line to `/output/entry.txt` and verifies the bytes written match exactly. See [SPEC.md](SPEC.md) for the brief, gate, and judge criteria.
