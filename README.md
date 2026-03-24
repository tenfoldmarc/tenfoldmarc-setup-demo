# Tenfold AI Setup — DEMO

Demo version of the Tenfold AI onboarding for Claude Code. Use this for recording tutorials and walkthroughs without modifying your real workspace.

Built by [@tenfoldmarc](https://instagram.com/tenfoldmarc)

## Install

**Easiest way:** Open Claude Code and say:

> Install this skill for me: https://github.com/tenfoldmarc/tenfoldmarc-setup-demo

Claude will handle the rest.

**Or do it yourself:**

Mac/Linux:
```bash
git clone https://github.com/tenfoldmarc/tenfoldmarc-setup-demo.git ~/.claude/commands/tenfoldmarc-demo-setup
```

Windows:
```bash
git clone https://github.com/tenfoldmarc/tenfoldmarc-setup-demo.git %USERPROFILE%\.claude\commands\tenfoldmarc-demo-setup
```

Then type `/tenfoldmarc-demo-setup` to start the full walkthrough.

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
