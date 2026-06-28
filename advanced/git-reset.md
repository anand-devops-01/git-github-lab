# Git Reset

## Introduction

The `git reset` command moves the current branch to a previous commit and can unstage or discard changes.

## Syntax

```bash
git reset <commit-id>
```

## Example

```bash
git reset HEAD~1
```

## Real World Use Case

Undo the last commit before pushing it.

## Best Practices

Be careful when using `--hard` because it permanently removes changes.

## Interview Question

**Q:** What is the difference between soft, mixed, and hard reset?

**A:** Soft keeps changes staged, mixed unstages changes, and hard removes all changes.