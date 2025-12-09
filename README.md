# 39883

## Current behavior

If you are using `baseBranchPatterns` and the default repo branch is ahead of the `baseBranchPatterns`, then manually updating a package on the Renovate base branch marks the PR as "abandoned" instead of auto-closing it.

## Expected behavior

Manually updating a package on the Renovate base branch should always auto-close the update PR.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/39883
