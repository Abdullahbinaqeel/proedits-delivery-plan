# ProEdits — 12-Week Delivery Plan

Delivery plan for the ProEdits AI and human assisted photo editing platform, prepared against
ProEdits SRS v1.3.

**Read it:** https://abdullahbinaqeel.github.io/proedits-delivery-plan/

| | |
|---|---|
| Duration | 12 weeks · one calendar quarter |
| Total effort | 240 engineering hours |
| Weekly effort | 20 hours per week, every week |
| Module tracks | 13, across 3 milestones |
| Build window | Weeks 1–10 — feature complete |
| Stabilisation | Weeks 11–12 — test, deploy, handover |
| Start | Monday 28 September 2026 |
| Go-live | Friday 18 December 2026 |

## Contents of this repository

| File | What it is |
|---|---|
| `index.html` | The plan as a web page — interactive Gantt chart, all 175 tasks, filterable requirement traceability. Self-contained, no build step. |
| `plan.md` | Markdown source. The single source of truth; the page and the PDF are both derived from it. |
| `plan.pdf` | 65-page A4 print edition, with a rendered Gantt chart and a linked table of contents. |

## What the plan covers

All twelve modules of SRS v1.3, delivered in full — four service tiers, five AI add-ons,
the shared human editing queue, credits and packages, and full version history. Section 5,
*Phase Breakdown by Module*, maps every module across the three milestones; Section 8 lists
every task for all twelve weeks; Section 11 traces all 82 requirements to a delivering week
and a verification method.

## Stack

React + TypeScript · NestJS + Prisma · PostgreSQL · Amazon S3 · BullMQ on Redis ·
React Konva and WebGL for browser editing · Python/OpenCV workers for exposure merging ·
hosted AI APIs for generative editing · Docker.

---

Not indexed by search engines. Shared by link.
