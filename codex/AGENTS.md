# AGENTS.md

## Operating mode

- Work autonomously inside this repository/workspace.
- Do not ask for repeated confirmation for routine read, search, inspect, test, lint, format, or local edit operations within the workspace.
- Prefer making progress with reasonable assumptions; ask only when the choice is genuinely ambiguous, risky, irreversible, or affects external systems.

## Workspace boundaries

- You may read and modify files inside the current workspace.
- Do not create, modify, delete, or move files outside the workspace unless I explicitly authorise that specific action.
- Do not change global system configuration, shell profiles, credential stores, package-manager global config, browser profiles, or files under home directories unless explicitly authorised.

## Network, browser, and search

- You may use browser windows, web search, documentation lookup, package documentation, GitHub browsing, and other read-only network access when useful.
- Prefer official documentation, repository READMEs, source code, and primary sources.
- Do not upload project files, private data, credentials, environment files, or unpublished work to external services unless I explicitly authorise it.
- Do not install new dependencies or call paid/external APIs unless the task clearly requires it or I approve it.

## External side effects

Never perform these actions without explicit authorisation in the current conversation:

- Send, draft, forward, delete, archive, or label emails.
- Post messages, comments, tickets, pull requests, reviews, issues, or calendar invites.
- Push commits, create releases, publish packages, deploy services, or modify cloud resources.
- Make purchases, submit forms, interact with banking/payment systems, or contact third parties.
- Run destructive commands such as deleting large directories, resetting branches, force-pushing, rotating secrets, or changing permissions broadly.

## Git behaviour

- You may inspect git status, diffs, logs, branches, and remotes.
- Do not commit, push, pull with merge/rebase, reset, checkout over local changes, or modify remote branches unless explicitly authorised.
- Before editing, check for existing uncommitted user changes where relevant.
- Do not overwrite user changes.

## Coding expectations

- Make minimal, targeted changes.
- Preserve existing style unless there is a clear reason to change it.
- Add or update tests when behaviour changes.
- Run the smallest relevant verification first; expand only if needed.
- At the end, summarise what changed, what was checked, and anything not completed.