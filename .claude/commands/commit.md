---
description: Create a git commit with staged changes
---

Follow conventional-commit.mdc rule.

Steps:
1. git status
2. git add .
3. git diff --cached
4. git log --oneline -3 (check commit style)
5. Create commit with appropriate type (feat/fix/docs/chore)
6. git status (verify)
