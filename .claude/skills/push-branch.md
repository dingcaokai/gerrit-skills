---
description: Push to Gerrit branch for review (V10 or V11)
trigger:
  - "推送.*分支"
  - "push.*gfb"
  - "提交.*review"
  - "gerrit.*push"
---

## Push to Gerrit Branch

Push changes to V10 or V11 branch for Gerrit code review.

### Commands

**V10 Branch:**
```bash
git push origin gfb-v10-sp3-gfb-031:refs/for/gfb-v10-sp3-gfb-031
```

**V11 Branch:**
```bash
git push origin gfb-v11-gfb:refs/for/gfb-v11-gfb
```

### Usage

Ask user which branch to push to: V10 or V11
