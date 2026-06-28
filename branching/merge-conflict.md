# Merge Conflict

## Introduction

A merge conflict happens when Git cannot automatically merge changes from two branches.

## Common Causes

- Same line modified in different branches.
- File deleted in one branch but modified in another.

## How to Resolve

1. Open the conflicted file.
2. Edit the file manually.
3. Save the file.
4. Run:

```bash
git add .
git commit
```

## Best Practices

- Pull changes frequently.
- Keep feature branches short.

## Interview Question

**Q:** What is a merge conflict?

**A:** A situation where Git cannot automatically combine changes from different branches.