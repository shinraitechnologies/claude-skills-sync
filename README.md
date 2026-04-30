# claude-skills-sync

Auto-synced Claude Code skills, updated weekly from:
- [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills)
- [anthropics/skills](https://github.com/anthropics/skills)

Skills are stored as `.md` files in `skills/` and are intended to be pulled into `~/.claude/skills/`.

## Local sync

```bash
# One-time setup
git clone https://github.com/shinraitechnologies/claude-skills-sync ~/.claude/skills-sync

# Pull latest skills (run weekly or on-demand)
cd ~/.claude/skills-sync && git pull && cp skills/*.md ~/.claude/skills/
```
