<!-- Title: Conventional Commits — type(scope): summary
     Types: feat fix docs style refactor perf test build ci chore revert (breaking as needed).
     The title is checked by CI, so there is no "type of change" section here. -->

## What and why

<!-- Lead with the conclusion: what changed and why it was needed.
     Reference an issue with `Closes #N` when there is one. -->

## How it was verified

<!-- What you ran and what it showed. For a bug fix, add the test that reproduces
     the bug before the fix. -->

## AI assistance

<!-- Pick one. A commit made with AI carries the trailer `Assisted-by: <agent>:<model>`
     (e.g. `Assisted-by: Claude:claude-fable-5-1`, the form the Linux kernel uses);
     AI is never a co-author and never signs off. The person who merges answers for
     every line. -->

- [ ] No AI, or AI only for lookups
- [ ] AI-assisted: commits carry `Assisted-by:`; I reviewed every line
- [ ] Agent-written: commits carry `Assisted-by:`; a person reviews every line before merge

## Checklist

- [ ] All CI checks are green (the ruleset defines which — they are not listed here)
- [ ] **Behaviour or a bug changed → a test that catches the change is in this PR, or the reason it is not**
- [ ] Lockfile committed if dependencies changed
- [ ] No secrets committed — configuration comes from the environment, `.env` is ignored
- [ ] Public surface changed → README / CHANGELOG updated in the same PR
