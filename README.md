# dating-coach

A Claude Code skill that acts as a personal dating coach. It's built on an evidence-graded courtship playbook: a stage model, texting cadence, reading interest, invitations, dates, escalation and consent, recovery when things go cold, and relationship repair.

It gives a direct verdict, exact messages to send in your own voice, and next steps that branch on how the other person replies. Manipulative tactics are swapped for honest versions that do the same job.

## Install

```bash
git clone git@github.com:nelonmelons/dating-coach-skill.git ~/.claude/skills/dating-coach
```

Claude Code loads it automatically when you ask for dating, texting or relationship advice. You can also call it explicitly with `/dating-coach`.

## Layout

| File | Covers |
|---|---|
| `SKILL.md` | Coaching workflow, stage model, core principles, non-negotiables, routing |
| `references/texting.md` | Cadence, reply timing, between dates, re-opening chats, chat-analysis format |
| `references/dates.md` | Planning, on the date, escalation and consent, dates 2–3, exclusivity, flakes, money |
| `references/conversation.md` | Profiles, openers, conversation craft, teases and "tests" |
| `references/recovery.md` | Exit ladder, graceful-failure scripts, sunk cost |
| `references/relationship.md` | Conflict repair, busy schedules, long-term milestones |
| `references/evidence.md` | 20 popular claims graded against research, plus the simple models behind the rules |
| `references/catalog.md` | The full long tail of techniques and numbers, each tagged by evidence and ethics |
