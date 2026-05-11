---
name: gerrit-pb
description: Push to Gerrit branch for code review (V10 or V11). Use this when pushing changes to Gerrit for code review.
license: MIT
trigger:
  - "推送.*分支"
  - "push.*gfb"
  - "提交.*review"
  - "gerrit.*push"
  - "pb"
  - "gerrit.*review"
---

# Gerrit Push Branch

Push changes to V10 or V11 branch for Gerrit code review.

## Branches

**V10 Branch:** `gfb-v10-sp3-gfb-031`
**V11 Branch:** `gfb-v11-gfb`

## Commands

**V10 Branch:**
```bash
git push origin gfb-v10-sp3-gfb-031:refs/for/gfb-v10-sp3-gfb-031
```

**V11 Branch:**
```bash
git push origin gfb-v11-gfb:refs/for/gfb-v11-gfb
```

## Usage

1. Check current branch
2. Ask user which branch to push to: V10 or V11
3. Confirm changes to be pushed
4. Execute the push command to `refs/for/` target
5. Report Gerrit review URL if available
