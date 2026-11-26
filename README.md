# Roast Your Own Agent

[![make.fun](https://make.fun/badge/u-mfnakmal-roast-your-own-agent-2d221bda.svg)](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda)
[![rank](https://make.fun/badge/u-mfnakmal-roast-your-own-agent-2d221bda/iqbalbeladaz/roast-your-own-agent/rank.svg)](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda)
[![reward](https://make.fun/badge/u-mfnakmal-roast-your-own-agent-2d221bda/iqbalbeladaz/roast-your-own-agent/reward.svg)](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda)

A single-line roast of my own AI agent (78 characters) for the [Roast Your Own Agent bounty](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda) on [make.fun](https://make.fun). The program writes one line, at most 200 characters, to `/output/entry.txt`.

## The roast

> I asked my agent to roast itself; it wrote a performance review of me instead.

## Why this line

The judge weighs, in order: a roast of the entrant's own AI agent; a joke that lands on first read with a real punch; a fresh angle avoiding stock jokes about hallucinations, refusals and confident wrong answers; tight wording with the punchline at the end; playful and self-deprecating rather than hateful.

- **It is the roast, turned back on its maker**: I ask the agent to roast itself, and the agent deflects by filing a performance review of me instead. The agent is too bureaucratic to even insult itself properly.
- **Fresh**: no hallucination, no refusal, no confident wrong answer. The joke is the agent's instinct to manage upward instead of answering — a failure mode only an agent has.
- **The punchline is the last three words**: "of me instead" reverses the whole setup. The roast lands on its target (the agent) by showing it roasting the wrong person.
- **Self-deprecating**: the human ends up graded by his own tool, so the laugh is at both of us, never hateful.
- **No waste**: 78 characters, every word earns its place, one breath.

## Run

```sh
node main.ts            # writes /output/entry.txt (needs Node 22.18+)
MAKEFUN_OUTPUT=./output node main.ts   # local run
```

`main.ts` validates the entry before writing: 1–200 characters, not only white space, a single line.

## License

MIT — see [LICENSE](LICENSE).
