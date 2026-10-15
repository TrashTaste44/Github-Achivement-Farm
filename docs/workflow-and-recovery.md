# Workflow, verification, and recovery

## Why branches and pull requests?

A branch isolates a change. A pull request records the proposed difference,
discussion, and merge result. Squash merging puts the proposed change on the
default branch as one commit while retaining the pull request history.

## Verify a run

- Confirm both documentation pull requests are marked Merged.
- Confirm `docs/getting-started.md` and this guide exist on the default branch.
- Follow the CLI's printed pull request links to inspect author, files, and timestamps.
- Check your profile separately for achievements. A merged PR is evidence of a
  completed workflow, not evidence that GitHub awarded a particular badge.

## Recover from interruption

Keep the runner's local `.achievement-lab` directory. Run the same command with
the same repository name, GitHub account, and state directory. The runner looks up
its branches and pull requests, skips merged work, and continues incomplete work.
If an API request fails, inspect the error and repository before retrying. Do not
delete the state file to force a restart against an existing repository.

## Review and repository rules

These are small, self-authored documentation changes in a personal sandbox and
are merged without requesting peer review. Shared projects should use the review
and testing appropriate to their risk. The runner does not bypass branch rules;
if GitHub requires checks or review, stop and satisfy those requirements normally.

## Cleanup

Branches are retained for inspection. After you finish, you may delete them in
GitHub. Deleting the entire public repository is a separate, manual decision.
