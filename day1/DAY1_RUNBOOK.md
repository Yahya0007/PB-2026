# Day 1 runbook – Monday 5 October 2026

Use the [current rollout plan](../docs/ROLLOUT_PLAN.md), reconfirmed on 2 October. Allow 7–8 hours. Start time is to be agreed. The first Tuesday review is 6 October.

Day 1: task board, import, sections, columns, marketing/brand view, Venue Pipeline, simple Tuesday view by owner, current-team access and a walkthrough. Dashboard, availability and targets belong to Day 2. Automations and Claude belong to Day 3.

## Files to use

- **Monday_Main_Board_Import.csv**: recommended import file. One header row, 138 tasks, 12 sections, stable Task IDs 1–138. UTF-8 with ISO dates.
- **Monday_Day1_Import_Pack.xlsx**: the same main import, Now decisions, empty Venue Pipeline template and team access decisions. Only Main Board Import goes into the task board; the other tabs support the meeting.
- **../PenniBlack_Collective_Team_and_Tasks_FINAL_1.xlsx**: preserved master. See [audit results](MASTER_WORKBOOK_AUDIT.md).

The import is a snapshot: refresh it if the master changes before Monday. Once live, Cat maintains the board. These files do not synchronise with Monday.

## Before starting

- [ ] Agree and record the start time with Charlotte and Cat.
- [ ] Test remote access to Charlotte’s laptop before the session, including screen sharing/control and opening the correct Monday workspace.
- [ ] Confirm workspace, Pro upgrade, Member login and Cat’s Admin access. These are planned, not verified as completed.
- [ ] Check whether the task board already exists. Do not import all tasks again blindly.
- [ ] Have Charlotte and Cat available for structure, owner, Now, date, stage and invite decisions.
- [ ] Check tasks 1–4, dated Friday 2 October, for completion; do not silently move their deadlines.
- [ ] Give Charlotte and Cat the current repository copy of `PenniBlack_Collective_Team_and_Tasks_FINAL_1.xlsx` and confirm they use it instead of the earlier circulated copy. The current copy has Task List column K, Due date, and linked Owner/Done fields in Start Here. This sharing has not yet been confirmed.
- [ ] Collect and verify missing individual emails for agreed Day 1 invitees, especially Danelle and Ana. Check existing access before inviting anyone.
- [ ] Confirm task 80: Cat is named in the notes for sending Momoko the Pichi attendee list, due Monday 5 October.

## Working schedule

Elapsed working time from the agreed start; accommodate short breaks within the allowance.

| Elapsed | Work | Finish with |
|---|---|---|
| 0:00–0:30 | Access and structure decisions | Workspace, groups and current invite list agreed |
| 0:30–2:00 | Main board and import | 138 unique tasks; fields and group counts reconciled |
| 2:00–3:30 | Review 26 source Now tasks | Agreed Now list, owners and due dates |
| 3:30–4:15 | Marketing/brand and priority views | Cat can filter by section, stage and priority |
| 4:15–5:15 | Venue Pipeline | Agreed stages and fields; real venues only if supplied |
| 5:15–6:00 | Tuesday review | Saved view tested with assigned and unassigned work |
| 6:00–6:45 | Team access | Invitations and acceptance status recorded |
| 6:45–7:30 | Walkthrough and checks | Cat can manage tasks; Day 2 inputs recorded |
| 7:30–8:00 | Allowance | Resolve import, access or decision gaps |

Invite agreed current members early when needed for task assignment; verify acceptance in the later access slot.

## Main board and import

Proposed name: **PenniBlack Collective – Tasks**.

For a new board, select header row 1 and **Item (Task)** as the item-name column. Start with the supported types below, then configure final columns. For an existing board, create the final columns first and map to them. Dates use ISO format. [Monday import instructions](https://support.monday.com/hc/en-us/articles/360000219209-Import-files-from-Excel)

| Source column | New-board import type | Final use |
|---|---|---|
| Item (Task) | Item name | Task name |
| Group | Text | Section labels for moving items into matching board groups |
| Workstream | Text | Text or Dropdown |
| Priority | Status | 1 – Money before Christmas; 2 – Build the brands; 3 – Systems (2027) |
| Stage | Status | Now; Next; Later |
| Timing (as planned) | Text | Original timing, including broad/provisional periods |
| Due date | Date | Current deadline; agree missing dates |
| Owner | Text, blank | Change to People; assign confirmed members |
| Suggested owner (confirm) | Text | Discussion aid only |
| Status | Status | Not started; Working on it; Stuck; Done |
| Notes | Text | Preserve source wording; convert to Long Text |
| Task ID | Number | Stable reference; do not renumber |
| Rollout / review note | Text | Scope conflicts and confirmation points |

Move items into these 12 groups, retaining the source Group field:

| Section | Tasks |
|---|---:|
| 0. Monday & Claude Setup | 13 |
| 1. All Brands | 16 |
| 1b. BNC Exhibition (end Oct) | 13 |
| 1c. Venue Sourcing | 14 |
| 2. PenniBlack Catering & Events | 11 |
| 3. Free Spirit Wellness | 12 |
| 4. Pichi | 9 |
| 5. Raquel’s Staffing & Bar | 7 |
| 6. VENN Productions | 4 |
| 7. Be-Zing (Kids + Youth) | 23 |
| 8. The Edit (PBC Edit) | 5 |
| 9. Systems & Admin | 11 |
| **Total** | **138** |

Before live decisions: **Now 26, Next 66, Later 46**; **Priority 1 = 92, Priority 2 = 40, Priority 3 = 6**; owners blank and statuses Not started. Record changes agreed on the day. Check IDs 1, 9, 43, 55, 80, 128 and 138, including full notes and dates.

There are nine populated import dates: four on 2 October and five on 5 October. The master has ten. Task 9’s original 5 October deadline remains in the master, source timing, Now Review and rollout note. Its operational import date is blank because the dashboard belongs to Day 2. Agree a new date; do not assume Day 2 means 6 October.

Keep task 128 (availability) for Day 2 and task 10 (Claude connection) for Day 3. All future work remains in the 138-task import; importing an item does not make it a Day 1 build commitment.

On a retry, match by Task ID and **Skip** existing items. Use **Update** only for deliberate changes, since it can overwrite live assignments and statuses. [Duplicate handling](https://support.monday.com/hc/en-us/articles/360000219209-Import-files-from-Excel)

## Now decisions and views

Use **Now Review (agree on the day)**. Source dates and suggested owners are separate from **Keep in Now?**, **Confirmed owner** and **Agreed due date**. Complete those three fields with Cat and Charlotte, then apply decisions to the live board. Blank answers remain unresolved.

The master workbook’s Start Here tab remains a static snapshot of the 1 October Now list. Its Owner and Done fields update, but newly promoted Now tasks do not appear automatically. Use the Task List Stage filter or the live Monday Now view for the current list.

Source Now IDs: 1–9, 28, 30–33, 43–45, 48, 55, 57, 59, 68–70, 80 and 128. Review tasks 9 and 128 against Day 2. Priority 1 covers 92 tasks, so the agreed Now list is the practical focus.

| View | Configuration |
|---|---|
| Marketing / brands | All tasks in agreed sections; visible Workstream, Priority, Stage, Owner, Status and Due date; filter to selected brand as needed |
| Now | Stage = Now AND Status is not Done; keep unassigned work visible |
| Priority 1 | Priority = 1 – Money before Christmas AND Status is not Done |
| Tuesday review | Stage = Now AND Status is not Done; group by Owner; show section, priority, status and due date; sort by due date and discuss blank dates |

For grouping by Owner, limit the People column to one accountable owner. Keep collaborators in notes. If multiple owners are required, use a per-owner People filter instead. Save the view; test that Done items leave it and unassigned items stay visible. [Group by](https://support.monday.com/hc/en-us/articles/4452237638546-Group-your-board-by-anything), [filters](https://support.monday.com/hc/en-us/articles/360003624660-The-Board-Filters)

## Venue Pipeline

Proposed name: **PenniBlack Collective – Venue Pipeline**. One item represents one real venue. The template is empty because the source contains venue-sourcing tasks, not a confirmed venue list.

Confirm **Contacted → Meeting → Trial → On supplier list**. Use a Stage status column and a view grouped by Stage. Agree how to hold uncontacted, declined or deferred venues; do not call an uncontacted venue Contacted.

Columns: Venue name, Stage, Venue type, Capacity, Current caterer, Contact name, Contact email/phone, How they pick suppliers, Owner, Next action, Next action date and Notes. Owner is People, Capacity is Number, Next action date is Date.

Tasks 45–47 organise the target list, top 20 and supplier research on the main board. They are not venue records. Add actual venues when supplied. Each active lead needs an owner, next action and follow-up date. Mark task 55 complete only after the pipeline is built and reviewed.

## Team access

**Team Invites (confirm)** includes all 11 master entries. Source access/start dates are separate from the Day 1 proposal, decision, verified email, agreed role and invitation status. Check addresses before use.

- Current candidates: Charlotte, Cat, Danelle and Ana, plus the setup consultant. Check existing access first. Cat is intended to be an Admin; the setup consultant needs Member access.
- Jessica starts mid-October; Lois at the end of October. Confirm whether earlier access is needed.
- Alex is TBC/when free. Raquel is view-only/later. Jess & Dave and Steph have no Monday access planned.
- Collect missing individual emails. Ana’s shared sales address is not an established personal login.
- The invite sheet already contains source email addresses for Charlotte, Cat and Yahya. Verify them before use; the other address fields are blank. A populated address does not confirm an invitation was sent or access is active.

## Acceptance and handover

- [ ] 138 unique source Task IDs and all 12 section counts reconciled before agreed additions.
- [ ] Task wording, notes, priorities, stages and source timing survived import.
- [ ] Each agreed Now item has an owner and due date, or an explicit unresolved decision with someone responsible for resolving it.
- [ ] Tasks 9, 128 and 10 follow the current rollout.
- [ ] Marketing/brand, Now, Priority 1 and Tuesday views saved and tested.
- [ ] Venue Pipeline built with confirmed stages; live leads have owner, next action and follow-up date. An empty pipeline is acceptable until real venues are supplied.
- [ ] Current access decisions and invite/acceptance status recorded.
- [ ] Cat can assign a task, change stage/status, set a date and open Tuesday’s view. Charlotte and Cat have reviewed the setup.
- [ ] Board links, unresolved actions and Day 2 needs recorded below.

| Handover record | Complete on the day |
|---|---|
| Main board link | |
| Venue Pipeline link | |
| Tuesday view link | |
| Open decisions and responsible person | |
| Cat / Charlotte review completed | |
| Day 2 date and required inputs | |

The preparation files are available on the repository’s `main` branch. Board creation, invitations, live imports and acceptance remain on-the-day actions; the access and logistics checks above are still unconfirmed.
