# Tunda Box: Junior Data Analyst Assessment

**Name:** Faith  **Date:** [date]

## Contents
- `notebook.ipynb`: all code (data load, audit, S1–S5, D2–D3, T2, Part 5)
- `responses.md`: written answers to every question
- https://docs.google.com/document/d/1ut6YqmsyttbLAr3J2clI9oWf9qcUiqnKEkfh1m1NULI/edit?usp=sharing

## Approach
1. **Audit first.** I profiled both tables before analysing and found 7 issues
   (duplicate order 1006, outlier 1013, orphan order 1020, NULL amount 1009,
   inconsistent city text, order before signup 1003, mixed statuses).
2. **Never silently delete.** I kept the raw tables, worked from `*_clean`
   copies, and flagged problems instead of removing them.
3. **State assumptions on every answer.** Revenue = completed orders only.
4. **Show sensitivity.** Where one order changes the answer (S2, S5, D3), I
   report results with and without it.
5. **Business framing.** Part 5 shows a mix shift, not a conversion problem.

## Key assumptions
- Revenue = `status = 'completed'`.
- Duplicate 1006 removed (identical in every column).
- Order 1013 treated as a suspected error and shown separately.
- Orphan order 1020 kept, city = "Unknown".

## How to run
Open `notebook.ipynb` and use Restart & Run All. Requires pandas, sqlite3
and statsmodels.