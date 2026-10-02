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
| `day1/DAY1_RUNBOOK.md` | Prepared plan for Day 1 (Mon 5 Oct) |
| `day1/Monday_Day1_Import_Pack.xlsx` | Import sheets: Marketing Board, Venue Pipeline, Team Availability, Targets |
| `day1/Monday_Task_List_Import.csv` | Same task list as flat CSV for Monday import |

## Plan summary
- Priorities: 1 money before Christmas (Oct–Dec), 2 build brands (Nov–Jan), 3 systems (2027). Stages: Now / Next / Later.
- "Day 1" = Mon 5 Oct setup day: marketing board (group per brand), load task list, goals/targets dashboard, team availability calendar, venue pipeline board (added later), Claude↔Monday if time.
- Key dates: Free Spirit at Menier Penthouse hoped Wed 21 Oct (awaiting Momoko); BNC exhibition end Oct (TBC).

## Change log
- 2026-10-02: Added `day1/` (runbook, import pack, CSV) generated from the master workbook's Task List/Team tabs (python/openpyxl; fields mapped: Section→Group, Task→Item, Priority text labels). Added this file. Nothing built in Monday itself (no Monday access from this environment).

## Notes / gotchas
- The Summary tab formulas reference Task List rows 5–142 but the real header is row 3; check counts if the workbook is edited.
- "When" values are free text (e.g. "Oct–Nov"), so import as Text, not Date.
- Owners intentionally blank; Cat allocates.
