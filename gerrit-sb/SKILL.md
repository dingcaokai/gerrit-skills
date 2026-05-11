---
name: gerrit-sb
description: Switch to Gerrit branch (V10 or V11). Use this when switching between Gerrit workflow branches for different versions.
license: MIT
trigger:
  - "切换.*分支"
  - "switch.*branch"
  - "checkout.*gfb"
  - "gfb.*branch"
  - "gerrit.*branch"
  - "sb"
---

# Gerrit Switch Branch

Switch between V10 and V11 branches for Gerrit workflow.

## Branches

**V10 Branch:** `gfb-v10-sp3-gfb-031`
**V11 Branch:** `gfb-v11-gfb`

## Commands

**V10 Branch:**
```bash
git checkout -b gfb-v10-sp3-gfb-031 origin/gfb-v10-sp3-gfb-031
```

**V11 Branch:**
```bash
git checkout -b gfb-v11-gfb origin/gfb-v11-gfb
```

## Usage

1. Ask user which branch to switch to: V10 or V11
2. Check if local branch exists
3. If local branch exists, switch to it
4. If not, create tracking branch from origin
5. Confirm successful switch
