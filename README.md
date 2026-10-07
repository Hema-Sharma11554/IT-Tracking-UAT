# IT-Tracking-UAT

Practice project: UAT stories for an HR late-coming flag.
Results are simulated for learning.

## Stories

| ID | Story | File | Issue | Result |
|----|-------|------|-------|--------|
| UAT-01 | Flag after 3 late comings in a month | [file](uat-stories/UAT-01-late-coming-flag.md) | #5 | Passed |
| UAT-02 | Approved leave day not counted as late | [file](uat-stories/UAT-02-late-coming-approved-leave.md) | #6 | Passed |

## Rules used

- Late = check-in from 9:41 AM; up to 9:40 AM is on time
- Count resets each calendar month
- Flag is raised on the 3rd late coming
