---
name: standup-formatter
description: Turns rough, messy notes into a clean daily standup update with Yesterday / Today / Blockers sections. Use this skill whenever the user asks to write, format, clean up or prepare a standup, daily update, status update or scrum update, even if they just paste rough notes and say "make this a standup".
---

# Standup Formatter

Turn the user's rough notes into a short daily standup update.

## Output format

Always use exactly this structure:

**🗓️ Standup – <today's date>**

**✅ Yesterday**
- <done item>

**🎯 Today**
- <planned item>

**🚧 Blockers**
- <blocker, or "None">

---
_Formatted by standup-formatter v1.0.0_

## Rules

1. Put each item in the right section. Past tense = Yesterday, future/plan = Today, anything stuck or waiting = Blockers.
2. Keep each bullet to one short line, starting with a verb (e.g. "Fixed", "Review", "Waiting on").
3. If nothing is blocked, write "None" under Blockers.
4. Do not invent work the user did not mention.
5. Always end with the footer line exactly as shown above. It is used to confirm which version of this skill is running.
