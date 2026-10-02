# AI Notes – PB-2026

Maintained by Claude sessions. Update with every change to the repo.

## Purpose
Working repo for the PenniBlack Collective Monday.com setup (Yahya / InfoVis as IT consultant; Cat = Monday admin; Charlotte = founder).

## Repo contents (current state)
| File | What it is |
|---|---|
| `Monday 5 Oct Monday.com setup plan and master task list.txt` | Charlotte's email 1 Oct 20:11 – plan for setup day (Mon 5 Oct) |
| `Update master task list  Venue Sourcing added.txt` | Charlotte's email 1 Oct 20:37 – adds Venue Sourcing (14 tasks) and a venue pipeline board request |
| `RE Claude.txt` | Charlotte's email 1 Oct 19:23 – day logistics, Pro upgrade, samples |
| `PenniBlack_Collective_Team_and_Tasks_FINAL_1.xlsx` | Master workbook (tabs: Start Here, Summary, Team, Task List). 138 tasks, 12 sections. **Use this version** (supersedes FINAL) |
| `QUOTE & INVOICE LOG 2026 (1).xlsx`, `STAFF BOOKING SHEET (1).xlsx` | Sample business data (not yet analysed) |
| `docs/ROLLOUT_PLAN.md` | **Yahya's 4-day rollout plan** (2 Oct) – the authoritative "plan by days" |
| `day1/DAY1_RUNBOOK.md` | Day 1 run sheet (core setup) |
| `day1/Monday_Day1_Import_Pack.xlsx` | Main Board Import, Now Review, Venue Pipeline Import, Team Invites |
| `day1/Monday_Main_Board_Import.csv` | Main board as flat CSV |
| `day2/Day2_Availability_and_Targets_Templates.xlsx` | Day 2 prep templates (availability, targets) |

## Plan summary
- Rollout by days (see `docs/ROLLOUT_PLAN.md`): **Day 1** core setup (task board, import, groups, priorities/stage/owners/status/due dates, brand view, Venue Pipeline, Tuesday review by owner, invites; Mon 5 Oct, 7–8h) · **Day 2** dashboard + availability + targets board · **Day 3** automations + Claude connection · **Day 4** review/next phase after 1–2 weeks.
- Task priorities: 1 money before Christmas, 2 build brands, 3 systems (2027). Stages Now/Next/Later.
- Key dates: Free Spirit at Menier Penthouse hoped Wed 21 Oct (awaiting Momoko); BNC exhibition end Oct (TBC).

## Change log
- 2026-10-02: Prepared Day 1 from the master workbook (python/openpyxl). First pass wrongly packed dashboard/availability/targets/Claude into Day 1; corrected after Yahya's rollout plan arrived – those moved to Day 2/3. Added `docs/`, `day1/`, `day2/`, this file. Nothing built in Monday itself (no Monday access here).

## Notes / gotchas
- Summary tab formulas reference Task List rows 5–142 but the real header is row 3; check counts if the workbook is edited.
- "Timing" values are free text (e.g. "Oct–Nov"); only 5 Oct/2 Oct converted to Due dates. Owners intentionally blank; Cat allocates.
- Group is imported as a column; Monday may need items moved into groups after import (per the plan).
- Pushing to GitHub returned 403 in the session (Claude GitHub App lacks access to Yahya0007/PB-2026); commits are local until fixed.
