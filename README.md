# Offload OS Lite

**A free Obsidian vault where Claude does the upkeep.** You dump what's in your head, Claude files it, plans your day and runs your weekly review.

Every note system I tried died the same way: capturing was easy, but filing, linking and reviewing turned into a second job. This vault moves that job to an AI and keeps the rules simple enough to survive a bad week.

- Plain Markdown. No plugins required.
- 3 commands: `/dump`, `/today`, `/week`
- Works with Claude Code, or with copy-paste prompts in any AI chat (free ChatGPT included)

---

## What's inside

```
00 Inbox/          everything new lands here
10 Projects/       one note per project (has a finish line)
20 Areas/          ongoing responsibilities
30 Resources/      topics and reference
40 Archive/        done or paused. Nothing gets deleted.
Daily/             written by /today
Weekly/            written by /week
Templates/         Daily.md, Weekly review.md
prompts/           the same 3 workflows as copy-paste prompts
CLAUDE.md          the rules Claude follows in this vault
.claude/commands/  /dump, /today, /week
```

## Quick start (5 minutes)

1. **Download** this repo (green `Code` button → `Download ZIP`) and unzip it.
2. **Open the folder as a vault** in Obsidian (`Open folder as vault`).
3. **Pick how you'll talk to the AI:**
   - **Claude Code:** open a terminal in the vault folder and run `claude`. The commands below are ready to use.
   - **Any AI chat:** open the `prompts/` folder, copy a prompt, paste your notes under it.
4. Write everything on your mind into `00 Inbox/Start here.md` and run `/dump`.

> Back up your vault (or put it in git) before letting any AI agent edit files. Start with this test vault, not your full archive.

## The 3 commands

| Command | What it does | When |
|---|---|---|
| `/dump` | Splits a messy brain dump into tasks, project updates, ideas and worries, and files each one | Whenever your head is full |
| `/today` | Asks about your fixed commitments, picks max 3 priorities, leaves ~30% of the day empty | Every morning, 2 minutes |
| `/week` | Wins first, then keep / shrink / move / let go for every project, then next week's plan | Sunday, ~20 minutes |

## The rules that make it stick

These live in `CLAUDE.md`. They're the reason I could leave this running daily:

- **Never delete. Archive instead.**
- **Show the plan before changing more than 5 notes.**
- **Never invent deadlines.**
- **Max 3 priorities a day. Plan ~70%, leave the rest empty.** A plan at 100% breaks on the first surprise.
- **Wins first in the weekly review.** Reviews that open with what you didn't do get skipped by week three.

When Claude does something you don't like, don't argue in chat. Add a rule to `CLAUDE.md`. Over time that file becomes a description of how you work.

## What it's bad at

- It shouldn't choose your priorities. It proposes, you decide.
- Long dumps sometimes file a task into the wrong project. The summary at the end of `/dump` makes that easy to catch.

---

## Want more?

- **Free guide: [The 15-Minute Week](https://offload-os.kit.com/ca666b8655).** 3 pages, the planning prompts with examples. Works with any AI chatbot.
- **[Offload OS](https://offloados.gumroad.com/l/offload-os)** is the full version I made and sell: more commands, a structured vault and video walkthroughs. You don't need it to use everything in this repo.

*Disclosure: I make Offload OS. Everything here is free, MIT-licensed, and works on its own.*

## License

MIT. Use it, fork it, change it.
