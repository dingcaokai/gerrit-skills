---
description: Switch to V10 branch (gfb-v10-sp3-gfb-031) from origin
trigger:
  - "切换到.*V10.*分支"
  - "switch.*v10.*branch"
  - "checkout.*v10"
  - "gfb-v10-sp3"
---

## Switch to V10 Branch

This skill switches to the V10 branch using the Gerrit workflow.

### Command

```bash
git checkout -b gfb-v10-sp3-gfb-031 origin/gfb-v10-sp3-gfb-031
```

### What it does

- Creates a new local branch `gfb-v10-sp3-gfb-031`
- Tracks the remote branch `origin/gfb-v10-sp3-gfb-031`
