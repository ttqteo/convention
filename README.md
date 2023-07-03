
# Branch and Commit Convention

## Branch Naming Convention

```
git branch <category/reference/description-in-kebab-case>
```

- `feature` is for adding, refactoring or removing a feature
- `bugfix` is for fixing a bug
- `hotfix` is for changing code with a temporary solution and/or without following the usual - process (usually because of an emergency)
- `test` is for experimenting outside of an issue/ticket

Examples

- You need to add, refactor or remove a feature: `git branch feature/issue-42/create-new-button-component` 
- You need to fix a bug: `git branch bugfix/issue-342/button-overlap-form-on-mobile`
- You need to fix a bug really fast (possibly with a temporary solution): `git branch hotfix/no-ref/registration-form-not-working`
- You need to experiment outside of an issue/ticket: `git branch test/no-ref/refactor-components-with-atomic-design`

## Commit Naming Convention
```
git commit -m '<category: do something; do some other things>'
```

- `feat` is for adding a new feature
- `fix` is for fixing a bug
- `refactor` is for changing code for peformance or convenience purpose (e.g. readibility)
- `chore` is for everything else (writing documentation, formatting, adding tests, cleaning useless code etc.)

Examples


```
git commit -m 'feat: add new button component; add new button components to templates'
git commit -m 'fix: add the stop directive to button component to prevent propagation'
git commit -m 'refactor: rewrite button component in TypeScript'
git commit -m 'chore: write button documentation'
```

---
Reference: [A Simplified Convention for Naming Branches and Commits in Git](https://dev.to/varbsan/a-simplified-convention-for-naming-branches-and-commits-in-git-il4#:~:text=Branch%20Naming%20Convention&text=A%20git%20branch%20should%20start,bugfix%20%2C%20hotfix%20%2C%20or%20test%20.&text=After%20the%20category%2C%20there%20should,%2C%20just%20add%20no%2Dref%20.)
