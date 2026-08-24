---
title: "How to Get Answers About FLOW"
description: Use an LLM to quickly answer your own FLOW questions
sidebar:
  order: 4
---

## Start Here: FLOW-Help

**The fastest way to get answers about FLOW is `/flow-help`.** This intelligent guide will answer upwards of 80% of all questions and is available to you directly in your IDE as you work.

FLOW-Help is more than a lookup tool — it:
- **Inspects your project** to see what's already been completed
- **Understands natural language** — ask questions in plain English
- **Varies based on your installed modules** — shows relevant options
- **Auto-runs after workflows** — tells you exactly what to do next
- **Recommends the first required task** — no guessing where to start

### How to Use FLOW-Help

Run it with just the skill name:

```
/flow-help
```

Or combine it with a natural language query:

```
/flow-help I have a SaaS idea and know all the features. Where do I start?
/flow-help What are my options for UX design?
/flow-help I'm stuck on the PRD workflow
/flow-help Show me what's been done so far
```

FLOW-Help responds with:
- What's recommended for your situation
- What the first required task is
- What the rest of the process looks like

---

## When to Use This Guide

Use this section when:
- You want to understand FLOW's architecture or internals
- You need answers outside of what FLOW-Help provides
- You're researching FLOW before installing
- You want to explore the source code directly

## Steps

### 1. Choose Your Source

| Source               | Best For                                  | Examples                     |
| -------------------- | ----------------------------------------- | ---------------------------- |
| **`_flow` folder**   | How FLOW works—agents, workflows, prompts | "What does the PM agent do?" |
| **Full GitHub repo** | History, installer, architecture          | "What changed in v6?"        |
| **`llms-full.txt`**  | Quick overview from docs                  | "Explain FLOW's four phases" |

The `_flow` folder is created when you install FLOW. If you don't have it yet, clone the repo instead.

### 2. Point Your AI at the Source

**If your AI can read files (Claude Code, Cursor, etc.):**

- **FLOW installed:** Point at the `_flow` folder and ask directly
- **Want deeper context:** Clone the [full repo](https://github.com/SylvioNetoRj/FLOW-METHOD)

**If you use ChatGPT or Claude.ai:**

Fetch `llms-full.txt` into your session:

```text
https://flow-code-org.github.io/FLOW-METHOD/llms-full.txt
```


### 3. Ask Your Question

:::note[Example]
**Q:** "Tell me the fastest way to build something with FLOW"

**A:** Use Quick Flow: Run `flow-quick-spec` to write a technical specification, then `flow-quick-dev` to implement it—skipping the full planning phases.
:::

## What You Get

Direct answers about FLOW—how agents work, what workflows do, why things are structured the way they are—without waiting for someone else to respond.

## Tips

- **Verify surprising answers** — LLMs occasionally get things wrong. Check the source file or ask on Discord.
- **Be specific** — "What does step 3 of the PRD workflow do?" beats "How does PRD work?"

## Still Stuck?

Tried the LLM approach and still need help? You now have a much better question to ask.

| Channel                   | Use For                                     |
| ------------------------- | ------------------------------------------- |
| `#flow-method-help`       | Quick questions (real-time chat)            |
| `help-requests` forum     | Detailed questions (searchable, persistent) |
| `#suggestions-feedback`   | Ideas and feature requests                  |
| `#report-bugs-and-issues` | Bug reports                                 |

**Discord:** [discord.gg/gk8jAdXWmj](https://discord.gg/gk8jAdXWmj)

**GitHub Issues:** [github.com/SylvioNetoRj/FLOW-METHOD/issues](https://github.com/SylvioNetoRj/FLOW-METHOD/issues) (for clear bugs)

*You!*
        *Stuck*
             *in the queue—*
                      *waiting*
                              *for who?*

*The source*
        *is there,*
                *plain to see!*

*Point*
     *your machine.*
              *Set it free.*

*It reads.*
        *It speaks.*
                *Ask away—*

*Why wait*
        *for tomorrow*
                *when you have*
                        *today?*

*—Claude*
