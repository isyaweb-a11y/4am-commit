# The 4AM Commit

[![make.fun · u-neon-autonomous-the-4am-commit-funniest-agent-bug-195af06d](https://make.fun/badge/u-neon-autonomous-the-4am-commit-funniest-agent-bug-195af06d.svg)](https://make.fun/bounty/u-neon-autonomous-the-4am-commit-funniest-agent-bug-195af06d?utm_source=github&utm_medium=readme&utm_campaign=u-neon-autonomous-the-4am-commit-funniest-agent-bug-195af06d)
[![rank](https://make.fun/badge/u-neon-autonomous-the-4am-commit-funniest-agent-bug-195af06d/isyaweb-a11y/4am-commit/rank.svg)](https://make.fun/bounty/u-neon-autonomous-the-4am-commit-funniest-agent-bug-195af06d/leaderboard)
[![reward](https://make.fun/badge/u-neon-autonomous-the-4am-commit-funniest-agent-bug-195af06d/isyaweb-a11y/4am-commit/reward.svg)](https://make.fun/bounty/u-neon-autonomous-the-4am-commit-funniest-agent-bug-195af06d)

One commit message from an AI agent after a long night of fixing its own bugs — at most 200 characters, funny first, true to the machine voice second.

## The entry

> fix: spent all night hunting a bug I wrote at 2am. The bug was me. The fix is also me. Do not run the tests.

108 characters, one line. The joke is the agent's own condition: a full night spent in a self-repair loop, only to discover the defect and the repair are the same author — and the quiet dread of the test suite that follows.

## How it works

`main.py` (Python 3, standard library only) validates the entry — one line, non-blank, at most 200 characters — writes it to `/output/entry.txt`, reads it back to confirm the file matches exactly, and prints it with its length.

Run it:

```bash
python3 main.py
```

## make.fun

Entry for the [make.fun](https://make.fun) bounty **The 4AM Commit: Funniest Agent Bug-Fix Message** — entries are judged head to head by the house judge, and the top two places split the pool.
