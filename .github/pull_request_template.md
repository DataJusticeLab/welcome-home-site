# Tickets

| Ticket | Summary | Jira |
| ------ | ------- | ---- |
| WAY-00 | One line on what the ticket asked for | https://celteeka.atlassian.net/browse/WAY-00 |

<!--
One row per ticket, the first row being the ticket this branch is named after.
Keep the key in the title too (for example "WAY-38 | SL | Show the items of a
started checklist") so the work is linked even where this table is not read.
-->

## What changed

<!-- The change in a few lines: what a reviewer will see in the diff, and in what order to read it. -->

## Before / After

<!--
Drag images or videos straight into the table; GitHub uploads them and leaves a link.
Use the same screen, the same device and the same data on both sides, so the
difference is the change and nothing else. For a flow, a short recording beats stills.
Nothing visual in this PR? Delete the section rather than leaving it empty.
-->

| Before | After |
| ------ | ----- |
|        |       |

## Why

<!-- The problem this solves. Link the design, the decision or the conversation where it was agreed. -->

## How to test

<!-- Steps against the running site, not just "it looks right". Say which browser or platform if it matters. -->

1.

## Acceptance criteria

<!-- Copy the criteria from the ticket and tick only what this PR delivers. Anything left, say so and why. -->

- [ ]

## Not in this PR

<!-- Known gaps, follow-up tickets, deliberate deviations from the ticket's wording. -->

## Checks

- [ ] **This PR contains breaking changes** — tick and describe them under *Not in this PR*: changed paths, removed pages, changed link targets, anything needing a coordinated update elsewhere
- [ ] Site renders correctly from `file://` and from the GitHub Pages subpath (all links and assets are relative, no absolute paths)
- [ ] Every commit message reads `WAY-00 | XX | Description`
- [ ] The branch is named `feature/WAY-00-XX-description-in-hyphens`
- [ ] *Before / After* filled in, or the section deleted as not applicable
