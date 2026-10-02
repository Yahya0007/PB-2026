# Master workbook audit – 2 October 2026

## Result

No task data was lost in the previous agent’s changes to `PenniBlack_Collective_Team_and_Tasks_FINAL_1.xlsx`. All four worksheets, 138 unique tasks, 12 sections, 14 Venue Sourcing tasks and 26 Start Here tasks remain. The current master opens and recalculates in Microsoft Excel 16.0 without formula errors.

Compared the original workbook from Git commit `8cbcff8` with the merged PR #1 version on `main` at `784ab98`. PR #1 is merged; the earlier notes about an outstanding GitHub push are obsolete. This checkout was fast-forwarded to the merged version before the audit.

## Content and structure

| Check | Result |
|---|---|
| Worksheet names/order | Start Here, Summary, Team, Task List retained |
| Original Task List A1:J142 | Every existing value preserved, including IDs, task wording, notes, priorities, stages, timing, blank owners and statuses |
| Unique tasks | IDs 1–138, with no missing or duplicate IDs or task names |
| Stage totals | Now 26; Next 66; Later 46; total 138 |
| Priorities | Priority 1: 92; Priority 2: 40; Priority 3: 6 |
| Team and Summary | All cell values/formulas preserved |
| Existing cell styles | Preserved |
| Row heights, column widths, merges, freeze panes | Preserved for existing content |
| Existing dropdowns and conditional formatting | Preserved |
| Start Here | Only E5:F30 changed: 52 cells now contain Owner/Done lookup formulas |
| New Due date column | K4:K142; 10 actual dates: four on 2 October, six on 5 October |
| Filter and validation | Filter extended from A4:J142 to A4:K142; date validation added in K5:K142 |
| Workbook integrity | ZIP package intact; opens in Excel |

The prior save removed an empty drawing and empty custom-properties part; neither contained content. Shared strings became inline strings with the same cell values. Default row-style records were normalised from implicit to explicit defaults, without changing existing cell formatting or dimensions. These are file-format changes, not lost workbook content.

## Formula verification

Both Artifact Tool and native Microsoft Excel recalculated the master. Excel was opened read-only and closed without saving.

- Summary totals calculated to 26 / 66 / 46 / 138, with Done = 0.
- Blank source owners displayed blank in Start Here.
- In a temporary in-memory test, setting Task List H5 to a test owner and I5 to Done updated Start Here E5/F5 and Summary Done to 1.
- Clearing the test owner and restoring Not started returned the displayed owner to blank and the checkbox to unchecked.
- No Excel formula-error cells were found after full recalculation.
- Rendered the changed Task List and Start Here regions and inspected the existing layout.

The master was not saved or edited during this preparation. SHA-256 after audit: `a305cfb7790e580a140c80cfdccf7a21b396b0def75ac9beac5195641f2aa5b3`.

## Operational points

- Start Here is the explicitly labelled **1 October snapshot**. Owner and Done update through formulas, but moving another task from Next to Now does not add it to this static list. For the current list, filter Task List by Stage = Now or use the live Monday view.
- The master reflects the earlier task dates. The current rollout moves dashboard task 9 and availability task 128 to Day 2; Claude task 10 belongs to Day 3. The master’s original wording/dates remain intact.
- The Day 1 import pack preserves all 138 tasks and original source timing/notes. Task 9’s operational import deadline is blank pending a new agreed date; its original 5 October deadline remains visible in the master, Now Review and rollout note. Hence the import has nine dates, compared with ten in the master.
- The pack’s Now decisions are a meeting worksheet. Confirmed owners, dates and Keep in Now fields start blank. Suggested owners are not assignments.
- Team preparation now includes all 11 actual source entries, with the accidentally imported header removed and Steph restored to the access review list. No invitation has been sent.
- Venue template has no example records that could be mistaken for real venues. Stages remain to be confirmed with Charlotte and Cat.

The CSV and XLSX main import were compared cell by cell. Task counts, IDs, sections, source fields and dates match the intended mapping. The finished pack also opened read-only in native Excel: four sheets, 139 main-sheet rows including the header, numeric dates displayed as ISO dates, task 9’s blank deadline and visible explanation, and the Now decision dropdown all checked correctly. Live Monday import and board behaviour still need the on-the-day checks in the runbook.
