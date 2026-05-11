---
description: Switch to Gerrit branch (V10 or V11)
trigger:
  - "切换.*分支"
  - "switch.*branch"
  - "checkout.*gfb"
  - "gfb.*branch"
---

## Switch to Gerrit Branch

Switch to V10 or V11 branch for Gerrit workflow.

### Commands

**V10 Branch:**
```bash
git checkout -b gfb-v10-sp3-gfb-031 origin/gfb-v10-sp3-gfb-031
```

**V11 Branch:**
```bash
git checkout -b gfb-v11-gfb origin/gfb-v11-gfb
```

### Usage

Ask user which branch to switch to: V10 or V11
