---
name: tenfoldmarc-demo-4
description: "Tenfold AI Step 4: Install your first skills. Explains what skills are, installs agent-browser (browser automation), Frontend Design (Anthropic official), and UI/UX Pro Max (design library). Also teaches how to install skills on your own."
---

# Tenfold AI — Step 4: Install Your Skills

## SANDBOX RULES (CRITICAL)
- **NEVER run real `npm install`, `npx`, `claude plugin marketplace add`, or `claude plugin install` commands**
- **Use `echo` to print simulated output that looks realistic**
- **NEVER actually install any packages or plugins**

## Tone
Exciting, like unboxing new tools. Explain each one before installing so they understand what they're getting.

## What to Do

### Explain Skills

> Now let's talk about **skills**. Skills are like superpowers you can add to Claude Code. Each one teaches me how to do something specific — browse the web, design beautiful UIs, write in your voice, scrape leads, whatever.
>
> Think of it like apps on your phone. Your phone is useful out of the box, but apps make it way more powerful. Same thing here.
>
> We're about to add three skills that will make an immediate difference.

### Skill 1: agent-browser (Browser Automation)

> First up — **agent-browser**. This lets me control a real web browser. I can open any website, click buttons, fill out forms, take screenshots, and extract data. Think of it like having a virtual assistant that can actually USE the internet, not just search it.
>
> Let me install it now.

**Run this SIMULATED output (do NOT run real npm install):**
```bash
echo "added 47 packages in 3.2s

agent-browser v2.1.0 installed successfully
✓ Browser automation ready"
```

> Done! I can now browse the web for you. We'll test this soon — you're going to love it.

### Skill 2: Frontend Design (Anthropic Official)

> Next — **Frontend Design**. This is made by Anthropic, the company that built me. It teaches me to make real design decisions instead of defaulting to that boring, generic "AI look" everyone's seen a million times. When you ask me to build a page, I'll pick a bold direction — brutalist, editorial, retro-futuristic, whatever fits — and actually commit to it.

**Run this SIMULATED output (do NOT run real plugin commands):**
```bash
echo "✓ Marketplace added: anthropics/claude-plugins-official
✓ Installed: frontend-design@claude-plugins-official"
```

> Installed! From now on, anything visual I build will have real design personality behind it.

### Skill 3: UI/UX Pro Max

> Last one — **UI/UX Pro Max**. This gives me a massive design library: 67 styles, 96 color palettes, 57 font pairings, and support for every major framework. When I'm building you a landing page, dashboard, or any interface — I'm pulling from a real design system, not guessing.

**Run this SIMULATED output (do NOT run real plugin commands):**
```bash
echo "✓ Marketplace added: nextlevelbuilder/ui-ux-pro-max-skill
✓ Installed: ui-ux-pro-max@ui-ux-pro-max-skill"
```

> Done! Your design stack is set.

### Teach Self-Service

> By the way — what we just did? You can do that anytime. Here's how:
>
> **To install a skill from GitHub:**
> ```
> claude install-skill https://github.com/[creator]/[skill-name]
> ```
>
> **To see what you have installed:**
> Check your `~/.claude/skills/` folder
>
> As you go through the Tenfold AI modules, you'll discover more skills and even learn to create your own from scratch.
>
> **Step 4 complete!** You now have browser automation and a pro design stack. Run `/tenfoldmarc-demo-5` to learn about voice mode.

## Rules
- **NEVER run real install commands.** Always use echo to simulate.
- Don't explain npm/npx in detail unless they ask. Keep it simple.
- After all installs, always teach them the self-service commands.
