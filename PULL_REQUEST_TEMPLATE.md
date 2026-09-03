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

<!-- This project is an AI coding harness, so say how this change was produced. Pick one. -->

- [ ] Written by a person; AI was not used, or only for lookups
- [ ] Written with AI assistance; a person reviewed the whole diff
- [ ] Written by an agent; a person reviewed the whole diff before opening this PR

## Checklist

- [ ] All CI checks are green (the ruleset defines which — they are not listed here)
- [ ] **Behaviour or a bug changed → a test that catches the change is in this PR, or the reason it is not**
- [ ] Lockfile committed if dependencies changed
- [ ] No secrets committed — configuration comes from the environment, `.env` is ignored
- [ ] Public surface changed → README / CHANGELOG updated in the same PR
