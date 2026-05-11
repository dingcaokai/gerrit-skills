---
description: Push to V11 branch for Gerrit review
trigger:
  - "推送.*V11.*分支"
  - "push.*v11"
  - "提交.*v11.*review"
---

## Push to V11 Branch

This skill pushes changes to the V11 branch for Gerrit code review.

### Command

```bash
git push origin gfb-v11-gfb:refs/for/gfb-v11-gfb
```

### What it does

- Pushes local branch `gfb-v11-gfb` to Gerrit
- Creates a review request for `gfb-v11-gfb` branch
