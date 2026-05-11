# Gerrit Skills

A collection of Claude Code skills for Gerrit workflow automation.

## Skills

### gerrit-cm
Commit changes based on spec file changelog format `[type#id]comment`.

**Usage:** `/gerrit-cm` or triggers like "按照changelog提交"

### gerrit-sb
Switch to Gerrit branch (V10 or V11).

**Usage:** `/gerrit-sb` or triggers like "切换分支"

### gerrit-pb
Push to Gerrit branch for code review.

**Usage:** `/gerrit-pb` or triggers like "推送分支"

## Installation

Clone this repository to your Claude Code skills directory:

```bash
cp -r gerrit-cm ~/.claude/skills/
cp -r gerrit-sb ~/.claude/skills/
cp -r gerrit-pb ~/.claude/skills/
```

## License

MIT
