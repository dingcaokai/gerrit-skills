---
description: Switch to V11 branch (gfb-v11-gfb) from origin
trigger:
  - "切换到.*V11.*分支"
  - "switch.*v11.*branch"
  - "checkout.*v11"
  - "gfb-v11-gfb"
---

## Switch to V11 Branch

This skill switches to the V11 branch using the Gerrit workflow.

### Command

```bash
git checkout -b gfb-v11-gfb origin/gfb-v11-gfb
```

### What it does

- Creates a new local branch `gfb-v11-gfb`
- Tracks the remote branch `origin/gfb-v11-gfb`
