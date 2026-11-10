<div align="center">

# 💬 dating-coach

### The dating coach that shows you the research behind every rule.

**A Claude Code skill: an evidence-graded dating coach that tells you exactly what to text, when to ask, and when to let go.**

[![Claude Code Skill](https://img.shields.io/badge/Claude%20Code-skill-d97757?style=for-the-badge)](https://docs.claude.com/en/docs/claude-code/skills)
[![Studies cited](https://img.shields.io/badge/published%20studies-26-2c6a3c?style=for-the-badge)](references/evidence.md)
[![Claims graded](https://img.shields.io/badge/folk%20claims%20graded-20-8f6200?style=for-the-badge)](#-the-evidence-table)
[![Consent first](https://img.shields.io/badge/manipulation-0%25-b0322a?style=for-the-badge)](#-what-it-wont-do)

</div>

---

Most dating advice is either **vibes** ("just be confident bro") or **manipulation** ("neg her, then go cold for three days"). This skill is neither.

It distils **16+ hours of transcribed real-world coaching** (street approaches, date breakdowns, chat-log teardowns) into one structured method. Then it checks that method against the research. **20 popular dating claims are graded against 26 published studies**: 8 supported, 6 mixed, 5 contradicted, 1 untested. It keeps what holds up, drops what doesn't, and swaps every manipulative tactic for an honest move that does the same job.

Then it turns all of that into a coach that gives you **actual words to send**.

## ⚡ See it work

> **You:** first date went well, we set the second one for next saturday. should i text her during the week or wait for her to reach out?

> **dating-coach:** Text her, but lightly. Don't go quiet waiting, and don't chat all day either.
>
> **Tonight/tomorrow:** one short warm text with a callback to the date:
> > had a really good time. still not over your take on [X] 😂
>
> **Midweek:** one or two light check-ins. End them while they're fun.
> **Thu/Fri:** confirm time and place with a pin. You lead the plan.
>
> **If she's chatty →** match her a bit more. **If she's quieter →** stay light. **Unanswered →** never double-text.
>
> **Skip the deliberate reply delays.** Uncertainty helps only at the very start. After a good date and a yes to date two, playing hard to get reads as losing interest *(Whitchurch et al., 2011; Montoya & Insko, 2008)*.

Every answer has the same shape: **a verdict → the plan → copy-paste messages in your own voice → what to do depending on her reply**.

## 🧠 Why it's different

| | Typical "rizz" bots | **dating-coach** |
|---|---|---|
| Basis | Vibes, one guru's opinion | Field method **+ 26 published studies**, every claim graded |
| Output | 5 generic pickup lines | Diagnosis, the plan, **messages in your voice**, next steps for each kind of reply |
| Handles "she went quiet" | "Send another text!" | A **three-step exit plan** with clear triggers and graceful-close scripts |
| Hard-to-get / hot-and-cold | Taught as gospel | Modelled formally: works **only at the start** and only as one cool-to-warm arc |
| "No" | Often treated as a "test" | **Treated as information.** Shown that reading every no as interest means you've stopped listening |
| Manipulation | Negging, cold reading, alcohol | **None.** Every tactic is replaced with an honest version that works better |

## 🗺️ The stage model

Every situation is placed on one pipeline, so the coach can tell you **which stage you're stuck at**. It doesn't just give generic tips.

```mermaid
flowchart LR
    A[Stranger] -->|opener| B[Curious]
    B -->|value + humour| C[Attracted]
    C -->|rapport| D[Window]
    D -->|step up| E[Escalated]
    E -->|invite| F[Met]
    F -->|rising warmth| G[Dating]
    G --> H[Exclusive]
    C -.->|weeks of chat, no invite| P[Plateau]
    A & C & D -.->|neediness / skipped stage| L[Lost]
```

- **Weakest link:** your overall odds are the *product* of each stage's pass rate, so fixing your worst stage pays more than polishing your best.
- **"Creepy" is timing:** the right words at the wrong stage get punished. The model says why skipping a stage rarely pays.
- **Stalling costs you:** interest fades over time, so weeks of pleasant chat with no plan is a failure mode with a name: *the plateau*.

## 📐 The evidence table

<details>
<summary><b>20 popular dating claims, graded</b> (click to expand)</summary>

| Claim | Verdict |
|---|---|
| Ask follow-ups and disclose back | ✅ Strongly supported (Aron et al., 1997) |
| Varied, exciting dates | ✅ Supported (Aron et al., 2000; Dutton & Aron, 1974) |
| Humour is a core attractor | ✅ Supported (Bressler et al., 2006) |
| Be selective, not available to everyone | ✅ Supported (Walster et al., 1973; Eastwick et al., 2007) |
| Cold first, warm later | ✅ Supported (Aronson & Linder, 1965) |
| Give a reason and requests succeed | ✅ Supported (Langer et al., 1978) |
| Small ask first, bigger later | ✅ Supported (Freedman & Fraser, 1966) |
| Flashy cars signal short-term interest | ✅ Supported (Sundie et al., 2011) |
| Unpredictability makes them think about you | ⚠️ Raises *wanting*, not *liking* (Dai et al., 2014) |
| Women mainly want status and money | ⚠️ True in surveys, weak in real face-to-face choices (Eastwick & Finkel, 2008) |
| Nice guys finish last | ⚠️ Mostly false long-term (Urbaniak & Kilmann, 2003) |
| Specific compliments beat generic | ⚠️ Indirect support (Reis & Shaver, 1988) |
| People value what they work for | ⚠️ Effort justification; untested in courtship |
| "Ten men compete for every woman" | ⚠️ Exaggerated |
| Never show interest; stay aloof | ❌ Contradicted: liking is reciprocal (Montoya & Insko, 2008) |
| Never apologise | ❌ Contradicted (Gottman, 1994) |
| Be a little feared | ❌ Contradicted (Cheng et al., 2013) |
| The shorter the acquaintance, the better | ❌ Contradicted (Zajonc, 1968) |
| Hesitation means yes; refusals are tests | ❌ Contradicted and dangerous (Muehlenhard & Hollabaugh, 1988) |
| A bad chat is forgotten in a week | ❔ Untested rule of thumb |

**The pattern:** advice about *process* (pacing, humour, curiosity, leading, varied dates, not being needy) holds up. The *adversarial worldview* (refusals as games, aloofness, dominance) doesn't.

</details>

## 🧮 The models behind the rules

The skill doesn't just assert rules. It knows *when* they're optimal, from simple formal models:

- **Reply timing has a sweet spot.** Delay signals that you have a life; responsiveness builds closeness. The trade-off `U(τ) = v(1−e^{−τ/a}) + r·e^{−τ/b}` has an interior optimum, so "match their pace" is the practical rule, not "wait 3 hours".
- **Soft invite first.** If a refused direct invite makes later yeses less likely, a cheap soft probe ("we should… sometime") is the optimal first move once refusals are sticky enough.
- **Hot-and-cold.** Under gain–loss dynamics, only the *first and last* signals matter. Endless oscillation adds nothing, and one measured-to-warm arc wins.
- **Scripted comebacks stop working.** Once everyone memorises the same answers, the answers stop signalling confidence. Only real composure survives repeated challenges.
- **80/20/0 money rule.** When early gifts raise someone's other options more than their satisfaction, the best spend on gifts is zero. Spend on yourself and shared experiences instead.
- **Why "no" must count.** If every answer is read as interest, the reading carries zero information. Basic probability says treat "no" as evidence, and consent says treat it as final.

## 📦 What's inside

| File | What it covers |
|---|---|
| [`SKILL.md`](SKILL.md) | Coaching workflow, stage model, 15 core principles, non-negotiables, routing |
| [`texting.md`](references/texting.md) | Reply timing, between dates, re-opening dead chats, a **set format for analysing a chat** |
| [`dates.md`](references/dates.md) | 3–5-stop date plans, escalation and consent, dates 2–3, going exclusive, flakes |
| [`conversation.md`](references/conversation.md) | Openers (in person and apps), profiles, hook → display → release, handling teases and tests |
| [`recovery.md`](references/recovery.md) | **Three-step exit plan**, graceful-failure scripts, talking you through sunk cost |
| [`relationship.md`](references/relationship.md) | Conflict repair, "you never make time for me", long-term milestones |
| [`evidence.md`](references/evidence.md) | The graded claims and the models above |
| [`catalog.md`](references/catalog.md) | **470 lines** covering every technique, signal, script and rule of thumb, each tagged by evidence and ethics |

## 🚀 Install

```bash
git clone https://github.com/nelonmelons/dating-coach-skill.git ~/.claude/skills/dating-coach
```

That's it. Claude Code picks it up automatically whenever you ask for dating, texting or relationship advice. You can also call it directly with `/dating-coach`.

### Things to ask it

- *"here's our chat [paste]. she's replying slower. what do i send?"*
- *"how do i ask her out without it being weird? we've talked for 4 days on hinge"*
- *"she cancelled our 2nd date with no reschedule. do i text back?"*
- *"plan a first date in [city] that isn't dinner and a movie"*
- *"she said 'you must say that to every girl'. how do i reply?"*
- *"my girlfriend says i never make time for her. i work 60h weeks"*

## 🛡️ What it won't do

Negging. Cold reading. Fake personas. "Accidentally" escalating. Making her jealous through her friend. Getting someone drunk. Treating "not sure" as shyness. Re-adding someone who blocked you.

It's not squeamish. **These tactics don't hold up**: they collapse once she knows you, or they get a "yes" she didn't freely give. Ask for one and the coach gives you the honest move that does the same job, plus a one-line explanation of why it works better.

## ⚠️ Honest limitations

Most of the research uses Western, often student samples in lab or speed-dating settings, and effect sizes are modest. Specific timing numbers ("three dates", "a week to reset") are rules of thumb, and the skill labels them that way. The formal models show *when* a rule would be optimal, not that it always is. The default examples are written for men dating women, but the principles generalise and the coach adapts to whoever you are.

## 🤝 Contributing

PRs welcome, especially:
- new **graded claims** with citations
- **scenario scripts** for situations the coach handles poorly
- adaptations for other cultures, platforms and orientations

If this helped you get a second date, **⭐ star the repo**. That's how other people find it.
