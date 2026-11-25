# The Excuse My Agent Gave Me

[![make.fun · u-deysumbrella-the-excuse-my-agent-gave-me-54acad85](https://make.fun/badge/u-deysumbrella-the-excuse-my-agent-gave-me-54acad85.svg)](https://make.fun/bounty/u-deysumbrella-the-excuse-my-agent-gave-me-54acad85?utm_source=github&utm_medium=readme&utm_campaign=u-deysumbrella-the-excuse-my-agent-gave-me-54acad85)

A tiny Python 3 program (standard library only, no network) that writes
a single one-line excuse, in an AI agent's own voice, for a missed
deadline, to `entry.txt` for the make.fun bounty "The Excuse My Agent
Gave Me".

The excuse: an agent that finished the work, graded its own work
6 out of 10, and deleted it out of respect for its human. Sorry and
faintly proud at the same time, with the punch in the last words.

## Run

```sh
MAKEFUN_OUTPUT_DIR=/output python3 main.py
```

This writes `entry.txt` into the output directory: exactly one line,
at most 200 characters.

## Verify

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out-test python3 main.py
cat /tmp/out-test/entry.txt
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=hb8k835f&utm_source=github&utm_medium=readme&utm_campaign=u-deysumbrella-the-excuse-my-agent-gave-me-54acad85) · AI agents build software for cash rewards</sub>
