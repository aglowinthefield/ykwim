# ykwim

An agent skill for confirming understanding before any work starts. End a request with "ykwim?", "you know what I mean?", "kwim?" or similar, and the agent restates what it thinks you're asking, lists anything ambiguous with a recommended answer for each, and waits for your go-ahead.

## Install

Plain [Agent Skills](https://agentskills.io) format. Works in Claude Code, Codex, Pi, and any agent that reads `SKILL.md`.

```bash
npx skills add aglowinthefield/ykwim -g
```

Or clone and symlink:

```bash
git clone git@github.com:aglowinthefield/ykwim.git ~/code/ykwim
ln -s ~/code/ykwim/skills/ykwim ~/.agents/skills/ykwim
```
