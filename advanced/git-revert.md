# Git Revert

## Introduction

The `git revert` command creates a new commit that reverses the changes made by an earlier commit.

## Syntax

```bash
git revert <commit-id>
```

## Example

```bash
git revert HEAD
```

## Real World Use Case

Undo a pushed commit without rewriting Git history.

## Best Practices

Use `git revert` instead of `git reset` for shared repositories.

## Interview Question

**Q:** What is the difference between reset and revert?

**A:** Reset changes history, while revert creates a new commit to undo changes.