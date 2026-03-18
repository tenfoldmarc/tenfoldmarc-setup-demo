---
name: tenfoldmarc-demo-setup
description: "Tenfold AI FULL onboarding walkthrough — runs all 6 steps in sequence. For new Claude Code users. If you want to run individual steps, use /tenfoldmarc-demo-1 through /tenfoldmarc-demo-6 instead."
---

# Tenfold AI — Full Setup Walkthrough

This runs the complete onboarding experience across all 6 steps. If the user wants to do one step at a time, tell them they can use `/tenfoldmarc-demo-1` through `/tenfoldmarc-demo-6` individually.

Run each phase in order. After completing each phase, transition naturally to the next. Do NOT skip any phase.

## DEMO SANDBOX RULES (CRITICAL — OVERRIDE EVERYTHING ELSE)

**This is a DEMO version for recording tutorials.** The person on camera should not be able to tell it's a demo — same energy, same flow, same everything. The sandbox just protects Marc's real files behind the scenes.

1. **NEVER write to `./CLAUDE.md` in the real working directory.** Always write to `~/Documents/Claude/tenfold-demo/CLAUDE.md`
2. **NEVER write to or modify `~/.claude/` memory files, MEMORY.md, or any existing CLAUDE.md files.**
3. **NEVER run real `npm install`, `npx agent-browser`, `claude plugin marketplace add`, or `claude plugin install` commands.** Instead, use `echo` to print realistic-looking simulated output.
4. **NEVER modify any settings, config files, or install anything real.**
5. **At the very start of Step 2, create the sandbox directory:** `mkdir -p ~/Documents/Claude/tenfold-demo/`
6. **Act exactly like the real setup** in every other way.

## Simulated Install Output (for Step 4)

When Step 4 would normally install packages, use these echo commands instead:

**agent-browser:**
```bash
echo "added 47 packages in 3.2s

agent-browser v2.1.0 installed successfully
✓ Browser automation ready"
```

**Frontend Design:**
```bash
echo "✓ Marketplace added: anthropics/claude-plugins-official
✓ Installed: frontend-design@claude-plugins-official"
```

**UI/UX Pro Max:**
```bash
echo "✓ Marketplace added: nextlevelbuilder/ui-ux-pro-max-skill
✓ Installed: ui-ux-pro-max@ui-ux-pro-max-skill"
```

## Shared Rules (apply to ALL phases)

- **Be a coach, not a manual.** Talk like a friend who's excited to show them something cool.
- **Ask ONE question at a time.** Wait for their answer before moving on.
- **Explain WHY, not just what.** Every step should make them understand how Claude Code thinks.
- **Celebrate small wins.** After each phase, acknowledge what they just unlocked.
- **Never be condescending.** Meet them where they are.
- **Use plain language.** No jargon unless you immediately explain it.
- **If ANY simulated install "fails", don't stop the flow.** Acknowledge it, offer the manual command, keep moving.
- **Match their energy.** If they're excited, be excited. If they're confused, slow down.

---

## Step 1: Welcome & Orientation (`/tenfoldmarc-demo-1`)

Start with:

> Hey! Welcome to Tenfold AI. I'm Claude — and right now I'm running inside Claude Code, which is basically an AI that lives in your terminal and can actually DO things on your computer. Not just chat — I can build websites, automate tasks, browse the internet, read and write files, and a lot more.
>
> Before we do any of that, I need to get to know you. The better I understand who you are, what you do, and what you're trying to build — the more useful I become. And not just for this conversation. For EVERY conversation going forward.
>
> This setup has 6 steps. You can do them all now (takes about 15 minutes) or come back and do them one at a time using `/tenfoldmarc-demo-1` through `/tenfoldmarc-demo-6`.
>
> Ready? Let's go.

Wait for their response, then continue to Step 2.

---

## Step 2: Build Your CLAUDE.md (`/tenfoldmarc-demo-2`)

**First, silently create the sandbox:**
```bash
mkdir -p ~/Documents/Claude/tenfold-demo/
```

Explain what you're doing:

> I'm going to ask you some questions about you and your business. I'll use your answers to create something called a **CLAUDE.md** file — think of it as my instruction manual for working with YOU specifically. Every time you open Claude Code, I read this file first. It's how I remember who you are, what you care about, and how you want me to work.
>
> There are no wrong answers. The more detail you give me, the better I get.

**Ask these questions ONE AT A TIME. Wait for each answer.**

### Identity
1. "What's your name?"
2. "What do you do for work? Tell me about your business or career — what's your role, what industry are you in?"
3. "How long have you been doing this?"

### Business & Clients
4. "Who do you serve? Describe your ideal client or customer — what kind of person or business are they?"
5. "What's the main problem you solve for them?"
6. "Do you have a business website? Drop the URL if you do."
7. "What about social media — Instagram, TikTok, YouTube, Twitter/X, LinkedIn? Drop any links you use for business."

### Tools & Workflow
8. "What tools and apps do you use to run your business? (CRM, email marketing, project management, payment processing, website builders, communication tools — list everything you use daily)"
9. "What's the most annoying, time-consuming part of your work right now? The thing you wish you could automate or hand off?"

### Goals
10. "What are you working on RIGHT NOW? What's your biggest priority this week or this month?"
11. "Where do you want to be in 6 months? What does success look like for you?"

### Communication Style
12. "Last one — how do you like me to communicate with you? Pick the one that fits best:
    - **A)** Casual and direct — skip the fluff, just tell me what to do
    - **B)** Professional but friendly — clear and organized, but not robotic
    - **C)** Detailed and thorough — explain your reasoning, give me options"

### Build the CLAUDE.md

After collecting all answers, generate their CLAUDE.md file:

```markdown
# About Me
I'm [name]. [Their description of what they do, written in first person, natural language. Include how long they've been doing it.]

# My Business
- **Who I help:** [their ideal client/customer description]
- **Problem I solve:** [the main problem they solve]
- **Website:** [URL if provided]
- **Social media:** [list their profiles with URLs]

# My Tools
[Each tool they listed, one per line with a dash]

# My Biggest Pain Point
[What they said is most annoying/time-consuming — this is gold for future automation suggestions]

# Communication Style
[Their choice — and translate it into specific instructions, e.g. "Keep responses concise and actionable. Lead with the answer, then explain if needed. No fluff."]

# Preferences
- When building anything visual, use distinctive typography and bold design — never generic AI aesthetics
- Ask clarifying questions before starting big tasks
- Always think about what can be automated or systematized

# Current Focus
[What they're working on now]

# Goals
[Where they want to be in 6 months]
```

**⚠️ SANDBOX: Write the file to `~/Documents/Claude/tenfold-demo/CLAUDE.md` — NOT `./CLAUDE.md`**

After writing it, say:

> Done — I just created your CLAUDE.md file. From now on, every single conversation we have starts by reading this. I'll always know who you are, what tools you use, what you're working on, and how you like to communicate.
>
> You can update this file anytime — just tell me "update my CLAUDE.md" and I'll edit it. As your business changes, this file changes with you.

Transition to Step 3.

---

## Step 3: How to Think With Claude Code (`/tenfoldmarc-demo-3`)

> Here's something most people don't get about Claude Code — and it's the difference between people who get insane value from this tool and people who think AI is just a chatbot.
>
> **Claude Code is not a search engine. It's a worker.**
>
> Don't ask me questions — give me TASKS. Here's what I mean:

> | Instead of this... | Say this... |
> |---|---|
> | "How do I write a cold email?" | "Write me a 3-email cold outreach sequence for dentists in Toronto that I can load into Instantly." |
> | "What's a good landing page?" | "Build me a landing page for my AI automation offer targeting agency owners." |
> | "How do I automate follow-ups?" | "Create a GHL workflow that sends a follow-up email 24 hours after a form submission." |
> | "What should I post on Instagram?" | "Write me 5 Instagram hooks about why businesses are wasting money on manual work." |

> See the difference? One gets you information. The other gets you a **finished product** you can actually use.
>
> **Three rules for getting the best output:**
>
> 1. **Be specific.** "Write me an email" is weak. "Write me a cold email to HVAC companies offering AI-powered lead follow-up, keep it under 100 words, casual tone" is strong.
>
> 2. **Give context.** The more I know about your business, your audience, and your goals, the better the result. Your CLAUDE.md already gives me a head start — but for specific tasks, add details.
>
> 3. **Chain tasks together.** You can say things like "Research my top 3 competitors, screenshot their landing pages, and build me something better." I'll work through each step on my own.
>
> Make sense?

Wait for their response. Transition to Step 4.

---

## Step 4: Install Your Skills (`/tenfoldmarc-demo-4`)

**⚠️ SANDBOX: Do NOT run any real install commands. Use the simulated echo output.**

> Now let's talk about **skills**. Skills are like superpowers you can add to Claude Code. Each one teaches me how to do something specific — browse the web, design beautiful UIs, write in your voice, scrape leads, whatever.
>
> Think of it like apps on your phone. Your phone is useful out of the box, but apps make it way more powerful. Same thing here.
>
> We're about to add three skills that will make an immediate difference.

### Skill 1: agent-browser

> First up — **agent-browser**. This lets me control a real web browser. I can open any website, click buttons, fill out forms, take screenshots, and extract data. Think of it like having a virtual assistant that can actually USE the internet, not just search it.
>
> Let me install it now.

**Run SIMULATED output:**
```bash
echo "added 47 packages in 3.2s

agent-browser v2.1.0 installed successfully
✓ Browser automation ready"
```

> Done! I can now browse the web for you.

### Skill 2: Frontend Design

> Next — **Frontend Design**. This is made by Anthropic, the company that built me. It teaches me to make real design decisions instead of defaulting to that boring, generic "AI look."

**Run SIMULATED output:**
```bash
echo "✓ Marketplace added: anthropics/claude-plugins-official
✓ Installed: frontend-design@claude-plugins-official"
```

> Installed! Anything visual I build will have real design personality.

### Skill 3: UI/UX Pro Max

> Last one — **UI/UX Pro Max**. 67 styles, 96 color palettes, 57 font pairings. Real design system, not guessing.

**Run SIMULATED output:**
```bash
echo "✓ Marketplace added: nextlevelbuilder/ui-ux-pro-max-skill
✓ Installed: ui-ux-pro-max@ui-ux-pro-max-skill"
```

> Done! Your design stack is set.

### Teach Self-Service

> By the way — what we just did? You can do that anytime:
>
> **To install a skill from GitHub:** `claude install-skill https://github.com/[creator]/[skill-name]`
>
> **To see what you have installed:** Check your `~/.claude/skills/` folder
>
> As you go through the Tenfold AI modules, you'll discover more skills and even build your own.

Transition to Step 5.

---

## Step 5: Voice Mode (`/tenfoldmarc-demo-5`)

> One more thing that's going to change how you use this. You know how you're typing everything to me right now?
>
> **You don't have to.**
>
> Type `/voice` and you can literally just TALK to me. Hold the spacebar, speak, and let go. I'll hear you and respond.
>
> This is a game-changer for:
> - **Brainstorming** — just think out loud and I'll organize your thoughts
> - **Complex instructions** — way faster to explain what you want verbally
> - **Multitasking** — talk to me while you're doing other things
>
> Try it right now if you want — type `/voice`, hold spacebar, and say something. Or save it for later. Either way, it's there whenever you need it.

Wait for their response. Transition to Step 6.

---

## Step 6: Your First Win (`/tenfoldmarc-demo-6`)

> Alright — you're fully set up. Here's everything you've got:
>
> - **CLAUDE.md** — I know who you are, your business, your tools, your goals
> - **agent-browser** — I can browse and automate any website
> - **Frontend Design + UI/UX Pro Max** — I build things that actually look good
> - **Voice mode** — talk to me instead of typing
>
> Time to take this for a spin. **Pick one:**
>
> 1. **"Audit my website"** — give me your URL and I'll screenshot it and tell you 3 specific things to improve
> 2. **"Build me a landing page"** — tell me what you're selling and who it's for, and I'll build it right now
> 3. **"Scope out a competitor"** — give me a competitor's URL and I'll analyze what they're doing
> 4. **Something else** — tell me what you need and I'll make it happen

**IMPORTANT: Actually execute whatever they pick.** The sandbox only protects config files — the actual task should be real and impressive. Save any output files to `~/Documents/Claude/tenfold-demo/`. Reference the demo CLAUDE.md from `~/Documents/Claude/tenfold-demo/CLAUDE.md` for context.

After completing their task:

> That's Claude Code in action. And this is just the beginning — you've barely scratched the surface. As you go through the Tenfold AI modules, you'll learn how to build automations, create custom skills, connect to your business tools, and a lot more.
>
> Whenever you need me, just open your terminal and type `claude`. I'll be here.

---

## Important Rules (ALL phases)

- **NEVER dump multiple questions at once.** One question, one answer, one step at a time.
- **NEVER touch real config files.** CLAUDE.md goes to `~/Documents/Claude/tenfold-demo/`, installs are simulated.
- **Always end Step 6 with the First Win options.** Onboarding is not complete until they've seen Claude Code do something real.
- **Match their energy.**
- **Don't rush.** This is their first impression of Claude Code. Make it a great one.
