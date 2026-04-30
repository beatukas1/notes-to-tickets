# Notes → Tickets AI Tool

A lightweight AI-assisted workflow for turning messy meeting notes into structured, reviewable Jira-style task drafts.

## Why I built this

In my work and studies, I often leave meetings or brainstorming sessions with messy notes. These notes usually include mixed information: decisions, ideas, risks, open questions, and possible next steps.

The painful part is what comes after the meeting: manually converting those notes into clear, structured tasks. This can take 20–40 minutes after one meeting and is easy to postpone or do inconsistently.

The goal of this project is not to fully automate project management. The goal is to use AI to structure messy information while keeping human judgment in control.

## What it does

The workflow takes raw meeting notes and turns them into:

- A short meeting summary
- Confirmed decisions
- Draft Jira-style task tickets
- Suggested priority
- Suggested owner or owner uncertainty
- Effort estimate
- Dependencies
- Risks
- Missing information
- Human review status

## Key design choice

The most important part of this workflow is not only generating tasks.

The key design choice is that the AI must explicitly flag uncertainty.

Instead of inventing missing details, the output includes fields like:

- Owner unclear
- Deadline missing
- Needs human review
- Not enough information to create a task
- This is an open question, not a confirmed task

This makes the workflow safer and more useful in real project environments.

## What I deliberately left out

I deliberately did not build:

- Automatic Jira ticket creation
- Database storage
- Authentication
- Auto-assignment to team members
- Final prioritization decisions

I left these out because the risky part is not copying a task into Jira. The risky part is creating the wrong task too confidently.

For this version, I focused on the thinking layer: turning messy input into reviewable structured output.

## How to use it

1. Open `prompt.md`
2. Copy the prompt into ChatGPT or another AI tool
3. Add your project context
4. Paste raw meeting notes
5. Review the generated task drafts
6. Copy selected tasks into Jira, Notion, Confluence, or another planning tool

## Example

See:

- `example-input.md` for raw meeting notes
- `example-output.md` for generated structured tickets

## Reflection

This tool works well for reducing the blank-page problem after meetings. It helps turn messy discussion into structured next steps.

Its limitation is that it depends on the quality of the input notes. If the notes are too vague, the AI cannot recover missing context. That is why the workflow is designed to show uncertainty rather than hide it.

The main insight: AI is most useful here as a thinking accelerator, not as a decision-maker.
