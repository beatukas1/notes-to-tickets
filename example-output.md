# Example Output: Structured Task Drafts

## 1. Short meeting summary

- The team discussed user confusion after signup.
- There may be issues with the welcome email and first onboarding screen.
- Support tickets increased last week, but the exact reason is unclear.
- The team needs analytics before making product changes.
- The goal is to improve activation before the next sprint review.

## 2. Confirmed decisions

### Decision 1

- Decision: Analytics should be reviewed before deciding on onboarding changes.
- Evidence from notes: “Need analytics before deciding.”
- Confidence: High

## 3. Draft task tickets

### Task 1

- Title: Investigate user confusion after signup
- Type: Investigation
- Description: Review available data and support feedback to understand where users become confused after signup.
- Why it matters: The team wants to improve activation before the next sprint review, but the cause of confusion is not yet clear.
- Suggested owner: Product / Analytics
- Owner confidence: Medium
- Priority: High
- Priority reasoning: The issue is connected to the sprint goal of improving activation.
- Estimated effort: Medium
- Dependencies: Access to activation analytics and recent support ticket examples.
- Risks: The team may redesign the wrong part of onboarding without enough data.
- Missing information: Exact activation metric, drop-off point, and whether the issue differs between web and mobile.
- Human review needed: Yes

### Task 2

- Title: Review welcome email clarity
- Type: Task
- Description: Check whether the current welcome email clearly explains the next step after signup.
- Why it matters: The welcome email may contribute to user confusion after signup.
- Suggested owner: Product / Marketing
- Owner confidence: Low
- Priority: Medium
- Priority reasoning: This may be part of the onboarding issue, but it has not been confirmed as the main cause.
- Estimated effort: Small
- Dependencies: Access to current welcome email copy.
- Risks: Improving the email may not solve the real activation problem.
- Missing information: Current email content and email engagement data.
- Human review needed: Yes

### Task 3

- Title: Compare onboarding issues across mobile and web
- Type: Investigation
- Description: Check whether user confusion appears on both mobile and web onboarding flows.
- Why it matters: The solution may be different depending on whether the issue is platform-specific.
- Suggested owner: Analytics / Product
- Owner confidence: Medium
- Priority: High
- Priority reasoning: Platform-specific data is needed before prioritizing design or frontend work.
- Estimated effort: Medium
- Dependencies: Platform-level activation data.
- Risks: Treating mobile and web as the same issue could lead to incorrect prioritization.
- Missing information: Mobile vs. web drop-off data.
- Human review needed: Yes

### Task 4

- Title: Collect recent support examples about signup confusion
- Type: Investigation
- Description: Ask the support team for examples of recent tickets related to signup or onboarding confusion.
- Why it matters: Support examples can help identify recurring user pain points.
- Suggested owner: Product / Support
- Owner confidence: Medium
- Priority: Medium
- Priority reasoning: Support insights can complement analytics before deciding on changes.
- Estimated effort: Small
- Dependencies: Support team availability.
- Risks: Support examples may be anecdotal and should not be the only decision source.
- Missing information: Number and content of relevant support tickets.
- Human review needed: Yes

## 4. Open questions / unclear items

- Are users confused on mobile, web, or both?
- Which activation metric is the team trying to improve?
- What is the current welcome email content?
- What part of the first screen may be confusing?
- Who owns final prioritization for onboarding changes?

## 5. Assumptions made

- “Activation” means successful completion of an onboarding step after signup.
- Anna is likely connected to support or user feedback, but her exact role is not confirmed.
- The next sprint review is the main short-term deadline.

## 6. Recommended next human action

Before creating final Jira tickets, confirm the activation metric and review analytics showing where users drop off after signup.
