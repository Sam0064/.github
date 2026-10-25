## Associated ticket
Include ONLY if a Trello or Jira card exists: full link to the card this PR closes. Delete this section when there is no card.

## Why are we doing this
What was wrong or missing, in plain English. What a user or maintainer was experiencing. No class, method or field names here.

## How are we doing this
What the change does, described as behaviour. Enough that someone who has never seen this code can predict what it now does. Name a file only when the reader needs to go look at it.

## Evidence
- Unit tests added: what each one asserts, in words.
- Mutations confirmed fixed: which ones, and the result that proves it.

## Known risks
What could go wrong, what it would look like if it did, and what is not covered. Write "none identified" only if that is true.

## How to revert
Check every box that applies and fill in the specifics.
- [ ] Code only: revert the merge commit; the pipeline redeploys
- [ ] Migration: reversible? Command to go back. Is old code safe on the new schema?
- [ ] Data / backfill: how to undo it, or why it can't be undone
- [ ] Feature flag: name of the flag to turn off
- [ ] Infra / env var: what to set back
- [ ] Other lineages: does each branch line need its own revert?
- [ ] Cannot be reverted: explain below what to do instead
