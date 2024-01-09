# Git Branching Rules
Please follow the below git branching rules and naming conventions for PR to get approved.

## Basic Rules

1. **Lowercase and Hyphen-separated** : Stick to lowercase for branch names and use hyphens to separate words. For instance, `feature/new-login` or `bugfix/header-styling`.
2. **Alphanumeric Characters:** Use only alphanumeric characters (a-z, 0–9) and hyphens. Avoid punctuation, spaces, underscores, or any non-alphanumeric character.
3. **No Continuous Hyphens:** Do not use continuous hyphens. `feature--new-login` can be confusing and hard to read.
4. **No Trailing Hyphens:** Do not end your branch name with a hyphen. For example, `feature-new-login-` is not a good practice.
5. **Descriptive:** The name should be descriptive and concise, ideally reflecting the work done on the branch.

## Branch Prefixes

Using prefixes in branch names helps to quickly identify the purpose of the branches. Here are some common types of branches with their corresponding prefixes:

1. **Feature Branches:** These branches are used for developing new features. Use the prefix `feature/`. For instance, `feature/login-system`.
2. **Bugfix Branches:** These branches are used to fix bugs in the code. Use the prefix `bugfix/`. For example, `bugfix/header-styling`.
3. **Hotfix Branches:** These branches are made directly from the production branch to fix critical bugs in the production environment. Use the prefix `hotfix/`. For instance, `hotfix/critical-security-issue`.
4. **Release Branches:** These branches are used to prepare for a new production release. They allow for last-minute dotting of i’s and crossing t’s. Use the prefix `release/`. For example, `release/v1.0.1`.
5. **Documentation Branches:** These branches are used to write, update, or fix documentation. Use the prefix `docs/`. For instance, `docs/api-endpoints`.

## Including Jira (or other Project Management Tool) Ticket Numbers

In some workflows, especially in larger teams, it’s common to include the ticket number from a project management tool like Jira in the branch name. This makes it easy to track the work done on a specific ticket. For instance, if you are working on a ticket numbered “T-123” for adding a new login system, the branch name could be `feature/T-123-new-login-system`.

## Sample Branch Names

Here are some samples of good branch names following the above conventions:

1. `feature/T-456-user-authentication`
2. `bugfix/T-789-fix-header-styling`
3. `hotfix/T-321-security-patch`
4. `release/v2.0.1`
5. `docs/T-654-update-readme`
