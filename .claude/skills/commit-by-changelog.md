---
description: Commit changes based on spec file changelog format [type#id]comment
trigger:
  - "按照.*changelog.*提交"
  - "commit.*changelog"
  - "根据.*spec.*提交"
  - "\\[.*#.*\\].*提交"
---

## Commit by Changelog

This skill commits changes following the spec file changelog format.

### Commit Format

```bash
git commit -a -m "[type#id]comment"
```

### Examples

From spec file changelog:
```
%changelog
* Sat May 09 2026 dingcaokai <dingcaokai@kylinos.cn> - 4.2.23-6.p03.gfb027
- Type: bug
- ID: [551507] yum安装不存在的包kernel-tools-libs提示信息异常
- SUG:N/A
- DES:kylin-yum-optimize-8.patch
```

Commit command:
```bash
git commit -a -m "[bug#551507]yum安装不存在的包kernel-tools-libs提示信息异常"
```

### Format Rules

- Use the **first** changelog entry in the spec file
- Format: `[type#id]comment` or `[type#id] comment`
- Type examples: bug, feature, enhancement
- ID: The issue/bug number
- Comment: Brief description of the change
