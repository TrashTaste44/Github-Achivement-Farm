# Getting started

This personal sandbox demonstrates a complete documentation pull request workflow.
It is also an experiment with GitHub profile achievements; awards are not guaranteed.

## Prerequisites

- A personal GitHub account that can create public repositories.
- Windows PowerShell 5.1 or PowerShell 7 and the GitHub CLI (`gh`).
- Authenticate locally with `gh auth login --hostname github.com`.

## What the lab does

1. Create a dedicated public repository, or use an explicitly selected personal lab.
2. Add this guide through a documentation branch and pull request.
3. Add a workflow and recovery guide through a second pull request.
4. Squash merge each pull request and verify its merged state.

The runner uses the GitHub REST API through `gh api`; a Git checkout is unnecessary.
Never place passwords, tokens, client files, or private information in this public lab.

## Inspect the result

Open the repository's Pull requests tab and select Closed. Each of the two pull
requests should show Merged. Open Files changed to inspect the documentation.
The guides remain in the default branch after merging.
