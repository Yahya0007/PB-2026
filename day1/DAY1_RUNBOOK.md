# Day 1 Runbook – Monday 5 Oct 2026 (Monday.com setup day)

Source plan: Charlotte's emails of 1 Oct 2026 ("Monday 5 Oct – Monday.com setup", "Update: master task list – Venue Sourcing added") and `PenniBlack_Collective_Team_and_Tasks_FINAL_1.xlsx` (138 tasks; 26 Now / 66 Next / 46 Later).

**Who:** Yahya (remote on Charlotte's laptop, own Member login) builds. Cat (admin, own computer) and Charlotte brainstorm alongside all day.

## 0. Before the day – confirm (Fri 2 Oct tasks, Cat)
- [ ] Monday trial status checked; upgraded to **Pro, monthly billing** (cards: Charlotte)
- [ ] Cat is **Admin**; Yahya invited as **Member** (info@infovis.co.uk)
- [ ] Charlotte's laptop remote access working
- [ ] Weekend samples received (spreadsheet, starter task list, sample marketing plan, team targets, enquiry tracker extract). Not in the repo yet except the xlsx files already uploaded (`QUOTE & INVOICE LOG 2026`, `STAFF BOOKING SHEET`).
- [ ] Files in `day1/` are ready: `Monday_Day1_Import_Pack.xlsx` (4 sheets) and `Monday_Task_List_Import.csv`

## 1. Suggested running order (~full day)

| # | Time | Build | Task IDs | Input |
|---|------|-------|----------|-------|
| 1 | Start | Kick-off: confirm access, agree board names, status labels, owners-blank rule (Cat allocates) | 6 | – |
| 2 | Block 1 | **Marketing board** – one group per brand, then **load the task list** | 7, 8 | `Monday Marketing Board Import` sheet / CSV |
| 3 | Block 2 | **Venue pipeline board** (new in Charlotte's 1 Oct 20:37 email) | 55 | `Venue Pipeline Import` sheet |
| 4 | Block 3 | **Goals & targets dashboard** for Tuesday meeting | 9 | `Targets Import` sheet + marketing board |
| 5 | Block 4 | **Team availability calendar** (quick win) | 128 | `Team Availability Import` sheet |
| 6 | If time | **Connect Claude to Monday** | 10 | Cat as admin authorises |
| 7 | End | Hand-over: Cat walks through My Work + Tuesday review routine | – | – |

Also due Mon 5 Oct but not Yahya's build: **Send Momoko (Menier Venues) the Pichi launch attendee list** (ID 80, Cat – promised by Charlotte).

## 2. Step detail

### 2.1 Marketing board + task list (IDs 7, 8)
1. Create a Main board "PenniBlack Collective – Marketing".
2. Import `Monday_Day1_Import_Pack.xlsx` → sheet **Marketing Board Import** (or the CSV). Map: `Group` → Group, `Item (Task)` → Item name, then columns below.
3. Column types:
   - Workstream → Dropdown or Text
   - Priority → Status (3 labels: 1 Money before Christmas / 2 Build the brands / 3 Systems 2027)
   - Stage → Status (Now / Next / Later)
   - When → Text (values like "Fri 2 Oct", "Oct–Nov" aren't clean dates)
   - Owner → People (blank on import; Cat allocates)
   - Status → Status (Not started / Working on it / Done / Stuck)
   - Notes → Long text; Task ID → Numbers (keeps link to the spreadsheet)
4. Expect **12 groups**, 138 items: Setup 13 · All Brands 16 · BNC Exhibition 13 · Venue Sourcing 14 · PenniBlack 11 · Free Spirit 12 · Pichi 9 · Raquel's 7 · VENN 4 · Be-Zing (Kids + Youth) 23 · The Edit 5 · Systems & Admin 11.
5. Views to save: **Now only** (Stage = Now), **By owner**, **Priority 1**. Tell each person to use **My Work**.
6. Owners are blank by design; leave for Cat.

### 2.2 Venue pipeline board (ID 55)
- New board "Venue Pipeline". Groups = pipeline stages in Charlotte's order: **Contacted → Meeting → Trial → On supplier list** (import sheet also adds "Target list (not yet contacted)" before and "Not a fit / parked" after – delete if not wanted).
- Columns: venue type, capacity, current caterer, contact, how they pick suppliers (preferred list / tender / commission), owner (Cat / Jessica / Lois), next action + date, notes.
- Seed from tasks 45–47 (target list, top 20, how venues pick suppliers). The sheet has placeholder example rows – delete them.
- Point of difference (IDs 43–44): Charlotte's note – "whole Collective as one supplier: food, drink, styling, staffing, wellness, Latino". Capture in the board description.

### 2.3 Goals & targets dashboard (ID 9)
Targets board (`Targets Import` sheet): per brand per month – enquiries, bookings, £ booked (target v actual). Charlotte/Cat to supply the numbers (tasks 14–16 set them; the sample "team targets" file should help).
Dashboard widgets for Tuesday:
1. Tasks by group (stacked by Status) – battery/progress per brand
2. Stage: Now vs Next vs Later counts
3. Priority 1 tasks not done
4. Tasks by owner (Now)
5. Targets vs actuals (enquiries / bookings / £ booked) from the Targets board
6. Venue pipeline: venues per stage
7. Key dates box: Free Spirit at Menier Penthouse (hoping Wed 21 Oct, awaiting Momoko); BNC exhibition end Oct (date TBC)

### 2.4 Team availability calendar (ID 128)
Board from `Team Availability Import` (Mon–Sun tick/status columns per person) plus a Calendar/Timeline view. Starts: Charlotte/Cat/Danelle/Ana now · Jessica mid-Oct · Lois end Oct · Alex when free. Raquel view-only/later; Jess & Dave, Steph outside the system. Confirm availability with each person.

### 2.5 Claude connection (ID 10 – if time)
Cat (admin) authorises the Monday connector. Seats per Team sheet: Charlotte Premium, Cat Premium, Lois Standard, Danelle Standard, Jessica TBC, Ana "review later", others none.

## 3. Open questions to ask on the day
- Exact Monday groups for Be-Zing: one group (as in the sheet) or Kids / Youth split?
- Who owns each Venue Sourcing task (Cat, Jessica, Lois)?
- Free Spirit date from Momoko – blocks tasks 69–70.
- BNC exhibition date/stand details (tasks 30–33).
- Be-Zing Kids award ceremony details (still to check).
- Availability data source: each person self-reports, or pull from `STAFF BOOKING SHEET`?

## 4. Done criteria for Day 1
Marketing board live with all 138 tasks in 12 groups · venue pipeline board exists · Tuesday dashboard shows task and target widgets · availability calendar created · (stretch) Claude connected.
