---
readingTime:
  minutes: 1.8
  words: 450
fkglResult: 9.2
---

# 03.0 Auto Mode Overview in Coding Agents

You've learned that token efficiency is all about sending the right amount of information to the right model. Now let's talk about a feature built directly into tools like **Cursor** and **GitHub Copilot** that automates part of that decision for you: **Auto mode**.

## What Auto Mode Actually Is

**Auto mode** is a **model-routing feature**, not an autocomplete feature. When you set your coding agent to Auto, you are telling the tool: *"Don't lock in one model — pick the best one for each request automatically."*

Modern coding agents have access to several AI models with different capabilities and costs:

- **Smaller, faster models** (e.g., Claude Haiku, GPT-4o mini) are excellent for short completions, quick questions, and simple edits. They use fewer tokens and respond almost instantly.
- **Larger, more capable models** (e.g., Claude Sonnet, GPT-4o) handle complex reasoning, multi-file refactors, and nuanced code generation. They use more tokens per request.

Without Auto mode, you manually pick one model and it handles *everything* — which means you're burning expensive tokens on tasks that didn't need them. **Auto mode solves this.**

## How Auto Mode Routes Your Requests

| Task Type | Example | Model Auto Picks |
|---|---|---|
| Short inline completion | Finish this `for` loop | Smaller, faster model |
| Quick explanation | What does this function return? | Smaller, faster model |
| Complex refactor | Rewrite this module to use async/await | Larger, capable model |
| Multi-file generation | Scaffold a REST API with auth | Larger, capable model |

The routing happens automatically, behind the scenes. You don't have to think about it — but understanding it helps you write better prompts and predict your token costs.

## What Auto Mode Is NOT

It's important to clear up a common misconception: **Auto mode is not the same as standard autocomplete or inline code suggestions.** Autocomplete — the ghost text that appears as you type — works the same way regardless of whether Auto mode is on or off. Auto mode only affects **which model processes your request**, not whether suggestions appear.

## Summary

Auto mode in coding agents:

- Automatically selects the most appropriate AI model for each task
- Uses lighter models for simple work → fewer tokens consumed
- Uses powerful models for complex work → higher quality output
- Is a **model-routing feature**, not an autocomplete feature

---

### Fill in the blanks to test your understanding!

```fill_in_the_blank 1="model-routing" 2="tokens" 3="automatically" 4="task complexity"

Auto mode is a _1_ feature — it does not control whether suggestions appear.

Using Auto mode helps reduce the number of _2_ consumed on simple tasks.

When Auto mode is active, the tool _3_ selects the best model for each request.

The key variable Auto mode responds to is _4_.
```
