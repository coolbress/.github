<!--
Title: type(scope): summary. Types: feat fix docs style refactor perf test
build ci chore revert (add ! for a breaking change). CI checks the title.

Everything below this comment becomes the body of the squash commit on main,
so write it as one. First, what changed and why (reference an issue with
`Closes #N` when there is one). Then, how it was verified: what you ran and
what it showed; for a bug fix, the test that reproduces the bug before the fix.
Prose, no headings, no checkboxes.

When AI wrote or assisted, end with the trailer as the last line:

    Assisted-by: <agent>:<model>

for example `Assisted-by: Claude:claude-fable-5-1` (the Linux kernel's form).
AI is never a co-author and never signs off; the person who merges answers
for every line. No trailer means no AI beyond lookups.

Before marking ready: every check is green (the ruleset decides which); a
behaviour or bug change has a test in this pull request, or the description
says why not; the lockfile is committed when dependencies changed; nothing
secret is committed; README and CHANGELOG follow a public-surface change.
-->
