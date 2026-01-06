---
description: Create a git commit with staged changes
---

Follow conventional-commit.mdc rule.

Steps:
1. git status
2. git add .
3. git diff --cached
4. git log --oneline -3 (check commit style)
5. Invoke changelog-writer agent to update CHANGELOG.md
6. Create commit with appropriate type (feat/fix/docs/chore)
7. git status (verify)
