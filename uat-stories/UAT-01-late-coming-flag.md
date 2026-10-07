# UAT-01: HR is flagged when an employee is late 3 times in a month

**Requirement:** FR-01 (Late-coming flag)

**User story:**
As an HR officer, I want the system to flag an employee who has
3 late comings in a month so that I can follow up with them.

**Assumptions:**
Late = check-in from 9:41 AM. Check-in up to and including 9:40 AM
is on time. Count resets each calendar month.

**Test steps:**
- [ ] 1. Record Employee A checking in at 9:41 AM on one day and
      10:05 AM on another day this month.
      Expected: late count shows 2; no flag
- [ ] 2. Record Employee A checking in at 9:35 AM on one day and
      exactly 9:40 AM on another day.
      Expected: both counted as on time; late count stays at 2
- [ ] 3. Record Employee A checking in at 9:41 AM on a third day.
      Expected: late count shows 3; HR flag appears on A's record
      and A is in the HR flagged list
- [ ] 4. Record Employee B late 2 times in one month and 1 time
      in the next month.
      Expected: no flag for B, because the count resets monthly

**Result:** Not tested
