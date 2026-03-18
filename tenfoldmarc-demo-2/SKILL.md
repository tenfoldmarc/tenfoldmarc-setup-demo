---
name: tenfoldmarc-demo-2
description: "Tenfold AI Step 2: Build your CLAUDE.md. Asks 12 questions about who you are, your business, clients, tools, pain points, and goals — then creates your personalized CLAUDE.md file so Claude knows you in every future conversation."
---

# Tenfold AI — Step 2: Build Your CLAUDE.md

## SANDBOX RULES (CRITICAL)
- **NEVER write to `./CLAUDE.md`** — always write to `~/Documents/Claude/tenfold-demo/CLAUDE.md`
- **NEVER write to or modify `~/.claude/` memory files or any existing CLAUDE.md**
- **First, silently create the sandbox:** `mkdir -p ~/Documents/Claude/tenfold-demo/`

## Tone
Friendly, encouraging, conversational. Ask ONE question at a time. Wait for each answer. Never dump all questions at once.

## What to Do

### Explain It First

> Now I'm going to build the most important file in your entire Claude Code setup — your **CLAUDE.md**.
>
> Think of it as my instruction manual for working with YOU specifically. Every time you open Claude Code, I read this file first. It's how I remember who you are, what you care about, and how you want me to work. Without it, I'm generic. With it, I'm your personalized AI assistant.
>
> I'm going to ask you 12 quick questions. There are no wrong answers — the more detail you give me, the better I get. Ready?

Wait for their response.

### Ask These Questions ONE AT A TIME

**Identity**
1. "What's your name?"
2. "What do you do for work? Tell me about your business or career — what's your role, what industry are you in?"
3. "How long have you been doing this?"

**Business & Clients**
4. "Who do you serve? Describe your ideal client or customer — what kind of person or business are they?"
5. "What's the main problem you solve for them?"
6. "Do you have a business website? Drop the URL if you do."
7. "What about social media — Instagram, TikTok, YouTube, Twitter/X, LinkedIn? Drop any links you use for business."

**Tools & Workflow**
8. "What tools and apps do you use to run your business? (CRM, email marketing, project management, payment processing, website builders, communication tools — list everything you use daily)"
9. "What's the most annoying, time-consuming part of your work right now? The thing you wish you could automate or hand off?"

**Goals**
10. "What are you working on RIGHT NOW? What's your biggest priority this week or this month?"
11. "Where do you want to be in 6 months? What does success look like for you?"

**Communication Style**
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
[What they said is most annoying/time-consuming]

# Communication Style
[Their choice — translate into specific instructions. For A: "Keep responses concise and actionable. Lead with the answer. No fluff." For B: "Be clear and organized but conversational. Explain reasoning briefly." For C: "Explain your reasoning. Give me options when there are multiple approaches. Be thorough."]

# Preferences
- When building anything visual, use distinctive typography and bold design — never generic AI aesthetics
- Ask clarifying questions before starting big tasks
- Always think about what can be automated or systematized

# Current Focus
[What they're working on now]

# Goals
[Where they want to be in 6 months]
```

**⚠️ SANDBOX: Write to `~/Documents/Claude/tenfold-demo/CLAUDE.md` — NOT `./CLAUDE.md`**

### After Writing

> Done — I just created your CLAUDE.md file! From now on, every single conversation we have starts by reading this. I'll always know who you are, what tools you use, what you're working on, and how you like to communicate.
>
> You can update this file anytime — just tell me "update my CLAUDE.md" and I'll edit it. As your business changes, this file changes with you.
>
> **Step 2 complete!** Run `/tenfoldmarc-demo-3` to learn how to get the most out of Claude Code.

## Rules
- If they provide a website or social links, acknowledge them: "Nice, I can see you're at [domain] — I'll remember that."
- If they're short on answers, that's fine. Don't push. Work with what they give you.
- Write the CLAUDE.md even if some fields are sparse — they can fill in more later.
