# Rollback and Recovery Evidence

## Project
Simple Profit Analysis Dashboard

## Purpose
Document the process for recovering the Excel dashboard if an incorrect edit or unwanted formatting change occurs.

## Rollback Procedure
1. Keep a backup copy of the last verified Excel workbook.
2. Before making significant changes, save a separate working copy.
3. If an update causes errors, close the affected workbook without saving if appropriate.
4. Restore the last verified backup copy.
5. Reopen the restored workbook.
6. Verify the KPI values, category summary, chart, and business insights.
7. Save the restored workbook after successful verification.

## GitHub Version Recovery
If the workbook is tracked in GitHub:
1. Open the repository's commit history.
2. Identify the last known good version.
3. Download the workbook from that version, or restore the required file using Git.
4. Verify the restored workbook before replacing the current version.

## Evidence to Maintain
- Screenshot of the verified dashboard before changes.
- Backup copy of the verified Excel workbook.
- Screenshot of the restored dashboard, if rollback is performed.
- Relevant GitHub commit reference, if version history is used.

## Current Rollback Status
Rollback procedure documented. No actual rollback has been performed or verified as part of this documentation.

## Important Note
Do not report a rollback as completed unless a recovery operation has actually been performed and verified.
