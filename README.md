# claude-agent-starter

Turn a blank **Claude Code** session into a personal agent you can message from your phone, that remembers what it learns, and that can reason over its own memory as a knowledge graph.

You give your agent one skill. It does the wiring. Three layers, in order:

1. **Telegram** — talk to your agent from your phone (and let agents talk to each other).
2. **Memory** — a file-based Obsidian vault the agent reads every session, so it never starts from zero.
3. **Graph** — a [graphify](https://pypi.org/project/graphifyy/) knowledge graph over that memory, so it can answer cross-cutting questions its flat notes would miss.

## Install

Drop the `agent-starter/` folder into your Claude Code skills directory (`~/.claude/skills/`), then in a fresh session run:

```
/agent-starter
```

Answer a few questions (agent name, where to keep its memory, your Telegram bot token) and it sets everything up.

## What you get

A named agent with a phone channel, a long-term memory, and a brain map over that memory. From there, you give it real work — and it writes down what it learns.

> Building a **team** of these agents (an "Agent OS") is a separate step. That's the next post.

---

ساختِ یه ایجنتِ شخصی روی Claude Code که از گوشی باهاش حرف بزنی، چیزایی که یاد می‌گیره رو یادش بمونه، و بتونه رو حافظه‌ش به‌شکلِ گراف فکر کنه. فقط کافیه این اسکیل رو بهش بدی.

نکته‌ی ایران: هم برای تلگرام هم برای ورود به Claude، یه نتِ پایدارِ تمیز لازمه — یه‌بار درست راهش بنداز.

---

Built by [Amirmahdi Mohammadi](https://www.linkedin.com/in/amirmahdi-mohammadi-2b65a8166) · AI lead at Rade AI.
