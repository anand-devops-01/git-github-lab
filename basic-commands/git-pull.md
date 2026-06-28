# Git Pull

## Introduction

Downloads the latest changes from the remote repository and merges them into your current branch.

## Syntax

```bash
git pull
```

## Example

```bash
git pull origin main
```

## Expected Output

Latest commits are downloaded and merged.

## Real World Use Case

Update your local project before starting work.

## Common Mistakes

- Pulling with uncommitted changes.

## Best Practices

Commit or stash your changes before pulling.

## Interview Question

**Q:** What is the difference between `git fetch` and `git pull`?

**A:** `git fetch` only downloads changes, while `git pull` downloads and merges them.