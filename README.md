# The School Board

A calm, mobile-friendly view of upcoming school assignments, verified dates, current ParentVUE grades, and older Schoology assignment flags that may need clarification.

**Website (GitHub Pages):** https://the-panoply.github.io/The-School-Board/

## Main sections

- **Today & Tomorrow:** Immediate work and past-dated items that still need family follow-up. Past-dated items remain here with a “Needs Follow-up” label until the family acts.
- **On the horizon:** Upcoming school dates, assignments, tests, and recovery deadlines.
- **Overdue assignments:** Collapsible, filterable Schoology flags. A Schoology overdue flag is not, by itself, proof that work is missing or unsubmitted.
- **Class Schedule and Grade Snapshot:** The grade panel shows current Q2 working marks from ParentVUE as large aligned letters with smaller percentages. Q1 finalized report-card marks appear as a small historical reference under each course.
- **Completed:** Keeps device-local completion marks separate from family-reported central completion records.

## How updates work

The visual design is stored in `index.html`; the static data comes from `assignments.json`. The site does not synchronize with FCPS in real time.

The data file carries a snapshot date and source notes. Each review should compare ParentVUE, the authenticated Schoology site, daily Schoology emails, and the existing source-linked records without treating any source as complete by default. Preserve source-specific wording and uncertainty. A blank submission view or a “Not Graded” mark is not proof that work was not submitted.

The November 13, 2026 snapshot uses ParentVUE Q2 summary grades and selected current assignment rows, plus Schoology parent Home activity and upcoming events and earlier assignment-detail observations. It is bounded and partial: not every Schoology course assignment page or announcement was inspected. Marketing’s ParentVUE detail rows appeared stale; summary grades are used. The grade panel distinguishes Q2 working grades from official finalized Q1 report-card marks.

## Publication

GitHub Pages is deployed from the repository’s `main` branch and root directory. After a change, fetch the latest files, preserve stable assignment IDs and unrelated records, then verify the commit and rendered site.

This repository is public-facing. Internal source evidence remains in the authorized Janie project workspace.
