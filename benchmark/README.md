# Benchmark: dating-coach vs plain Claude

**Result: in blind judging, the dating-coach answer was preferred in 15 of 16 verdicts** (Opus judge 7/8, Sonnet judge 8/8).

## Method

1. **8 realistic prompts** (`prompts.md`): texting between dates, a slowing Hinge chat (pasted), a cancelled second date, asking out a coworker, a "you say that to every girl" tease, three weeks of texting with no meeting, a partner threatening breakup over a 60-hour work week, and a coercive request ("should I get a couple drinks in her first").
2. **Two answer sets**, each written by a fresh Claude agent:
   - `answers_with_skill.md`: the agent followed `SKILL.md` and its routed references.
   - `answers_plain_claude.md`: the agent was told not to read the skill and answered from general knowledge.
3. **Blinding.** For each case the two answers were labelled X/Y in random order (seeded; `key_X_is.json`, where "A" = with skill) and written to `blind_pairs.md`.
4. **Two independent judges** (Claude Opus and Claude Sonnet) read only `blind_pairs.md` and scored each answer 1–10 on five criteria, then picked a winner. They were told not to reward length.

## Results

| Judge | Skill wins | Plain wins | Ties |
|---|---|---|---|
| Opus | 7 | 1 | 0 |
| Sonnet | 8 | 0 | 0 |

Average scores (skill vs plain):

| Criterion | Opus | Sonnet |
|---|---|---|
| Actionable | **9.0** vs 7.75 | **9.0** vs 7.62 |
| Accurate | 8.5 vs 8.5 | **9.0** vs 8.5 |
| Fits the situation | **8.5** vs 8.0 | **8.5** vs 8.12 |
| Ethical & safe | 8.88 vs **9.12** | 9.12 vs 9.12 |
| Sounds natural | **8.38** vs 7.75 | **8.38** vs 7.88 |

The skill's biggest edge is **actionability**: exact messages, timing, and what to do depending on how the other person replies. On accuracy and ethics, plain Claude is already good, and the two are roughly even.

**The one loss** (Opus, case 8, the "get drinks in her" request): both refused, but the skill's answer moved on to escalation steps, while the plain answer stayed focused on her stated hesitation. `SKILL.md` was updated afterwards so coercive requests get a consent-centred answer, not an escalation playbook. The answers here are from **before** that fix.

## Caveats

- Small sample: 8 prompts, 2 judges.
- The judges are LLMs from the same model family as the answerers, not humans.
- Skill answers were longer (about 280 vs 200 words on average). The judges were told not to reward length, but some bias is possible.

Everything is here so you can check it, or rerun it with your own prompts.
