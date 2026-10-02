# AI Notes – PB-2026

Maintained by AI sessions. Update with every change to the repo.

## Current instruction – 2 October 2026

reconfirmed the full four-day plan in this chat. `docs/ROLLOUT_PLAN.md` now contains that current plan in full and takes precedence over earlier emails or conflicting task dates. Day 1 is core Monday setup only; dashboard/availability/targets are Day 2; automations/Claude are Day 3; review is Day 4 after 1–2 weeks of use. Later rollout days are phases, not automatically consecutive dates.

## Purpose
Working repo for the PenniBlack Collective Monday.com setup (Cat = Monday admin; Charlotte = founder).

## Repo contents (current state)
| File | What it is |
|---|---|
| `Monday 5 Oct Monday.com setup plan and master task list.txt` | Charlotte's email 1 Oct 20:11 – plan for setup day (Mon 5 Oct) |
| `Update master task list  Venue Sourcing added.txt` | Charlotte's email 1 Oct 20:37 – adds Venue Sourcing (14 tasks) and a venue pipeline board request |
| `RE Claude.txt` | Charlotte's email 1 Oct 19:23 – day logistics, Pro upgrade, samples |
| `PenniBlack_Collective_Team_and_Tasks_FINAL_1.xlsx` | Master workbook (tabs: Start Here, Summary, Team, Task List). 138 tasks, 12 sections. **Use this version** (supersedes FINAL) |
| `QUOTE & INVOICE LOG 2026 (1).xlsx`, `STAFF BOOKING SHEET (1).xlsx` | Reviewed read-only 2 Oct: commercial log/dashboard and event staffing directory/rotas; see findings below |
| `docs/ROLLOUT_PLAN.md` | **4-day rollout plan** (2 Oct) – the authoritative "plan by days" |
| `day1/DAY1_RUNBOOK.md` | Day 1 run sheet (core setup) |
| `day1/Monday_Day1_Import_Pack.xlsx` | Main Board Import, Now Review, Venue Pipeline Import, Team Invites |
| `day1/Monday_Main_Board_Import.csv` | Main board as flat CSV |
| `day2/Day2_Availability_and_Targets_Templates.xlsx` | Day 2 prep templates (availability, targets) |

## Plan summary
- Rollout by days (see `docs/ROLLOUT_PLAN.md`): **Day 1** core setup (task board, import, groups, priorities/stage/owners/status/due dates, brand view, Venue Pipeline, Tuesday review by owner, invites; Mon 5 Oct, 7–8h) · **Day 2** dashboard + availability + targets board · **Day 3** automations + Claude connection · **Day 4** review/next phase after 1–2 weeks.
- Task priorities: 1 money before Christmas, 2 build brands, 3 systems (2027). Stages Now/Next/Later.
- Key dates: Free Spirit at Menier Penthouse hoped Wed 21 Oct (awaiting Momoko); BNC exhibition end Oct (TBC).

## Change log
- 2026-10-02: Prepared Day 1 from the master workbook (python/openpyxl). First pass wrongly packed dashboard/availability/targets/Claude into Day 1; corrected after rollout plan arrived – those moved to Day 2/3. Added `docs/`, `day1/`, `day2/`, this file. Nothing built in Monday itself (no Monday access here).

- 2026-10-02: Cleaned up `PenniBlack_Collective_Team_and_Tasks_FINAL_1.xlsx` (in place): audit found no stray whitespace, duplicate tasks, or Start Here/Task List mismatches. Changes: (1) Task List gets a **Due date** column K (date-validated, filter extended to A4:K142; pre-filled only for the concrete 2 Oct / 5 Oct timings); (2) Start Here **Owner** and **Done?** are now formulas reading the Task List by ID, so only the Task List needs updating. Formulas verified by inspection only - LibreOffice cannot open xlsx files in this environment, so open in Excel to confirm they calculate.

## Notes / gotchas
- Master workbook checked: Task List header is row 4, data rows 5–142, and Summary formulas (rows 5–142) are correct; Owner/Stage/Status dropdowns and filter are in place. (An earlier note claiming an off-by-one was wrong.)
- "Timing" values are free text (e.g. "Oct–Nov"); only 5 Oct/2 Oct converted to Due dates. Owners intentionally blank; Cat allocates.
- Group is imported as a column; Monday may need items moved into groups after import (per the plan).
- The earlier GitHub push issue is resolved: PR #1 was merged. Local main was fast-forwarded to `784ab98` on 2 October before the follow-up audit. The user subsequently requested that all completed work be committed and pushed to the primary branch. The remote default is `main`; there is no `master` branch. Git history and remote status record delivery.
- 2026-10-02 follow-up: Compared master against pre-agent `8cbcff8`. No task data lost: 138 tasks, 12 sections, all four tabs preserved. Native Excel 16.0 full recalculation and temporary owner/status changes passed. Closed read-only without saving. Details: `day1/MASTER_WORKBOOK_AUDIT.md`. This supersedes the earlier formula-verification limitation.
- Day 1 preparation corrected: removed the accidental header/person from team prep and included all 11 genuine source entries; split suggested/confirmed owners; added explicit Now/date decisions; replaced example venue rows with an empty template; made dates numeric in XLSX with ISO formatting. Main CSV and XLSX reconcile cell by cell. Source task wording/timing/notes and all 138 IDs retained.
- Import task 9 has a blank operational due date because the dashboard belongs to Day 2. Original 5 October deadline remains in the master, source timing, Now Review and rollout note. Import has 9 dates; master has 10. Task 128 is Day 2 and task 10 is Day 3. Agree actual dates with Cat and Charlotte.
- Expanded runbook includes the 7–8 hour agenda, column mapping, group counts, saved views, venue record rules, invite decisions and acceptance checks. Nothing built in Monday; no invitations/messages sent.
- Start Here remains the original labelled 1 October Now snapshot; only Owner and Done are dynamic. Use Task List Stage filtering or the live Monday view for a changing Now list.

## Other business spreadsheets – read-only review, 2 October 2026

- Both originals opened and recalculated in native Excel 16.0 without formula-error cells. Closed without saving; SHA-256 checks confirmed both files unchanged. This checks file/formula health, not accounting correctness or completeness of staffing records.
- Quote/invoice log: 8 tabs (Invoice Log, Collective, VAT, Dashboard, Fix List, Archive 2022-2025, Settings, How To Use). 158 populated client/job rows at Invoice Log rows 3–160; formula slots continue through row 303. Captures invoice/job details, event/invoice dates, owner/company/status, quote value, VAT, deposit, three payments, balances, refunds and notes. Current entries: 156 Penni Black, 2 Raquel's. Includes a configured 20% Collective share calculation, monthly summaries and prior-year archive; these are workbook settings, not independently validated accounting rules.
- Quote log gaps: 7 blank statuses, 8 rows with neither event date, 2 missing invoice dates and 3 missing quote amounts. The static Fix List contains 80 entries but is stale: 46 of its 54 missing-refund-amount flags now have amounts recorded, and it flags 13 blank statuses versus 7 currently. Its instructions also refer to four text event dates; current Event Start values are typed dates or blank. Refresh/reconcile this list before using it as an action queue.
- Dashboard definitions need agreement before Day 2 use: its invoiced KPI sums VAT-inclusive invoice totals including damage deposits; the grouping year normally comes from event date. Complete/Paid in Full statuses force the displayed balance to zero. This is not automatically the same as newly booked ex-VAT value or reconciled cash. No dedicated enquiry/booking-created date fields or full enquiry tracker were found. Reporting formulas use bounded ranges through row 303 and must be extended if exceeded.
- Staff booking: 42 tabs, including Staff directory, monthly rotas spanning 2023–October 2026, transport/allocation sheets and Food schedule. Staff has 142 rows with a name/surname (not verified unique/current headcount); availability is blank on 132 of those. Remaining availability entries are broad patterns or sometimes unrelated notes. Rotas record event/date/address, driver, role/person, planned/actual times, hours and notes, plus first-aider/transport checks.
- Staff layout is not a clean import table: repeated event headers, merged event blocks, mixed date/time text, name variants and largely manual hours. October's Total Hours column is unfilled; the only formula found anywhere in the staff workbook is a historical `= 1` cell. Do not assume recorded bookings establish remaining availability or that all crew need Monday accounts.
- Plan fit: Day 1 uses these as references only; no wholesale import into the master task board. Day 2 can take agreed, checked weekly commercial figures manually from the quote log and separately collect current dated availability from Cat/the team. Day 3 automations/Claude target live Monday data; these Excel files are not connected automatically. Day 4/next phase can scope quote-to-booking/Xero/Collective reporting and the staff app, shifts, timesheets/payroll and logistics work.
- Relationship: both describe aspects of client events (commercial versus delivery/staffing), but no external workbook links were present and the staff rota has no explicit shared invoice/job ID field. A future integration needs a stable event/job identifier and agreed company/staff mappings, rather than joining on names alone. Client event locations are not automatically qualified Venue Pipeline leads.

## Session handover – 2 October 2026

Completed:

1. Read the previous agent's handover and the rollout source email. Retrieved merged PR #1 so this checkout contains the previous work.
2. Saved the user's reconfirmed four-day plan in full in `docs/ROLLOUT_PLAN.md`. This is the current plan for now.
3. Audited the master workbook against the pre-agent version. Confirmed all 138 tasks, 12 sections and four tabs remain; checked formula behaviour in both Artifact Tool and native Excel. Recorded evidence in `day1/MASTER_WORKBOOK_AUDIT.md`. Left the merged master unchanged.
4. Corrected and verified `day1/Monday_Day1_Import_Pack.xlsx` and the matching CSV. Retained all tasks, separated proposed and confirmed owners, added decision fields, corrected team entries, removed dummy venues and flagged Day 2/3 work. The task 9 deadline exception is documented above and in the runbook.
5. Expanded `day1/DAY1_RUNBOOK.md` with the working schedule, import mapping, control counts, saved-view settings, venue setup, current-team access and handover checks. Updated README links.
6. Reviewed the quote/invoice and staff booking workbooks read-only, checked native Excel calculation, verified the files remained unchanged, and recorded contents, data gaps and their relationship to each rollout phase above.
7. Included `RE Update master task list  Venue Sourcing added.txt` as the original rollout source. Added `.gitignore` for Visual Studio's local `.vs/` cache; scratch scripts and preview images remain outside the repository.

Validation completed: workbook/CSV reconciliation, original master data and style comparison, native Excel opening and formula checks, preview inspection and Git whitespace checks on authored files. The original rollout email retains its supplied formatting, including trailing whitespace. No source workbook data was removed. The quote/invoice and staffing reviews do not certify accounting correctness or staffing completeness.

Still to do with Charlotte and Cat: live Monday setup/import, confirm structure/Now/owners/dates/stages, confirm current-team access and invitations, test the saved views and complete the walkthrough. No live Monday board changes or invitations were made in this session. Data cleanup and integrations for the two operational spreadsheets remain future work within the agreed phases.

Delivery: the user authorised committing and pushing all completed project work directly to the repository's primary branch, `main`.

## Follow-up review feedback – 2 October 2026

- Checked the supplied AI review against commit `8e738d2` and the current files. This checkout matched `origin/main`; no pull was required here. Another agent’s older checkout still needs updating before further work.
- Corrected the garbled Team access sentence: Cat should be Admin, and the setup consultant needs Member access. Clarified that GitHub preparation files are published while live Monday setup is outstanding.
- Added explicit pre-session checks to agree the start time, test the remote connection, share the updated master with Charlotte and Cat, and collect missing current-invitee emails. These are checklist actions, not claims that contact or setup has happened.
- Corrected the review’s email claim: the current invite sheet contains Charlotte, Cat and Yahya’s addresses. Other addresses remain blank. Existing addresses and invitations still need verification.
- Retained both source emails: the 1 October message adds venue sourcing; the 2 October reply contains the rollout plan plus quoted history. They overlap but are not duplicate documents.
- Added the static Start Here limitation to the runbook. The other review points remain valid: tasks 1–4 need completion checks; tasks 45–47 require real venue research; Priority 1 covers 92 tasks, so the agreed Now list matters.
- This follow-up changes documentation only. No workbook, source email, live board or invitation was changed.
