# Git Workflow Rules

These rules apply to all Git work in this repository. A human exception applies only where a rule explicitly allows one. Repository settings and branch protections still apply.

## Attribution

- Do not add Claude credit or attribution to commits or pull requests. This includes `Co-Authored-By: Claude` (or any variant), other Claude co-author trailers, and Claude credit in commit messages, PR titles, or PR descriptions.

## Branches, pushes, and pull requests

- Create a new branch for every codebase change before making the change, unless a human explicitly instructs you to use another branch or workflow. If currently on `main`, create and switch to a new branch first.
- You may push to feature branches whenever needed without asking for approval.
- Obtain explicit human approval before pushing directly to `main` or merging any branch into `main`. Permission to work on a change or open a PR does not itself approve either action.
- Use a pull request as the default path into `main`. Do not merge a branch directly into `main` unless a human explicitly requests that workflow.
- Merge pull requests into `main` with a merge commit. Use another merge method only when a human explicitly directs it or GitHub repository constraints require it.

## Commits

- Always make individual commits for each notable bit of work, or change.
- Follow the repository's established commit message naming convention. Check meaningful recent commits; do not treat a generic bootstrap message such as `Initial commit` as a convention.
- If no convention is established, start each subject with a capitalized, descriptive prefix and a colon, then describe the specific change with appropriate capitalization and enough detail to understand it. Examples:
  - `Add: Fade-in CSS animation to hero block`
  - `Chore: Migrate dependency management from npm to pnpm`
  - `Remove: Unused form component`
  - `Docs: Update README to include CI workflow`

## Conflicts with main

- Never merge a branch that conflicts with `main`. Explain the conflict to the human, propose a resolution, and wait for instructions before resolving it or attempting the merge. Approval to merge is still required after the conflict is resolved.
