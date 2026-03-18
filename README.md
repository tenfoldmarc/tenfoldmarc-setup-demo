# Tenfold AI Setup — DEMO

Demo version of the Tenfold AI onboarding for Claude Code. Use this for recording tutorials and walkthroughs without modifying your real workspace.

Built by [@tenfoldmarc](https://instagram.com/tenfoldmarc)

## Quick Install

```bash
claude install-skill https://github.com/tenfoldmarc/tenfoldmarc-setup-demo
```

Then type `/tenfoldmarc-setup` to start the full walkthrough.

## What's Different From the Real Version

- CLAUDE.md is written to `~/Documents/Claude/tenfold-demo/` instead of your working directory
- All package/plugin installs are simulated (nothing actually gets installed)
- Your real CLAUDE.md, MEMORY.md, and `~/.claude/` config are never touched
- Step 6 (First Win) still executes real tasks so it looks impressive on camera

## Cleanup

When you're done recording:

```bash
rm -rf ~/Documents/Claude/tenfold-demo/
```
