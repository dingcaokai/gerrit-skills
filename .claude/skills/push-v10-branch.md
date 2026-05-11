---
description: Push to V10 branch for Gerrit review
trigger:
  - "推送.*V10.*分支"
  - "push.*v10"
  - "提交.*v10.*review"
---

## Push to V10 Branch

This skill pushes changes to the V10 branch for Gerrit code review.

### Command

```bash
git push origin gfb-v10-sp3-gfb-031:refs/for/gfb-v10-sp3-gfb-031
```

### What it does

- Pushes local branch `gfb-v10-sp3-gfb-031` to Gerrit
- Creates a review request for `gfb-v10-sp3-gfb-031` branch
