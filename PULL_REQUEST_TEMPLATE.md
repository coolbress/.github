## What and why

<!-- What changed and why. `Closes #N` first when there is an issue. Delete the comment lines: they land in the squash commit otherwise. -->

## How it was verified

<!-- What you ran and what it showed. For a bug fix, the test that reproduces the bug before the fix. When AI wrote or assisted, end the description with the trailer on its own last line: `Assisted-by: <agent>:<model>` (for example `Assisted-by: Claude:claude-fable-5-1`). -->

<details>
<summary>Before marking ready</summary>

- Title is `type(scope): summary` with one of feat fix docs style refactor perf test build ci chore revert; CI checks it
- Every check is green (the ruleset decides which)
- A behaviour or bug change has a test in this pull request, or the text above says why not
- Lockfile committed if dependencies changed; nothing secret committed
- README and CHANGELOG follow a public-surface change

</details>
