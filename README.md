# #42704 - `postUpgradeTasks` with `executionMode: "branch"` silently skipped when dependency exists in multiple project directories

## Current behavior

postUpgradeTasks runs for one update, but not for the other. Compare the two PRs:
https://github.com/JuJup/renovate-post-upgrade-task-bug/pulls

## Expected behavior

`postUpgradeTasks` should run for both.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/42704
