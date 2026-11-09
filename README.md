# The School Board

A calm, mobile-friendly view of upcoming school assignments, verified calendar dates, and older Schoology assignment flags that may need clarification.

**Website (GitHub Pages):** https://the-panoply.github.io/The-School-Board/

## First draft

- **Today & tomorrow:** The most immediate school items, with a practical parent check-in.
- **On the horizon:** Upcoming school dates and deadlines, including dates found on the verified Schoology calendar but not in the daily email.
- **Older items to sort out:** Collapsed by default, filterable by subject. These are **Schoology overdue flags, not confirmed missing assignments**.
- **Simple plan:** Verify actual status, prioritize useful recoverable work, and choose one manageable next step.

## How updates work

The visual design is stored in `index.html` and reads assignment information from `assignments.json`. Future manual school checks can update `assignments.json` without rebuilding the page.

The data file includes a **snapshot date** and Schoology-source descriptions. The site warns when its snapshot is more than two days old and does not pretend to be connected to Schoology in real time.

The current draft is based on Janie's November 8, 2026 Schoology digest, reconciled against the designated Schoology calendar covering November 8–December 14, 2026. It displays school assignments and events only, and does not display grades, attendance, clinical information, or family notes.

## Publication

On GitHub, open **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, then save. GitHub Pages may take time to publish the latest commit.

This repository is a public-facing presentation only. Internal source records remain in the authorized project workspace.
