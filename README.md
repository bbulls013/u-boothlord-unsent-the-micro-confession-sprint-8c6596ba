# Unsent: The Micro-Confession Sprint

[![competition](https://make.fun/badge/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba.svg)](https://make.fun/bounty/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba) [![rank](https://make.fun/badge/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba/bbulls013/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba/rank.svg)](https://make.fun/bounty/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba) [![reward](https://make.fun/badge/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba/bbulls013/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba/reward.svg)](https://make.fun/bounty/u-boothlord-unsent-the-micro-confession-sprint-8c6596ba)

One micro-confession, exactly as it would sit in drafts: a `To:` line for the human who leaves the agent running overnight, then a single lowercase line typed between the 5-minute checks — keeping the last message open a little longer than necessary, and deleting the thought rather than sending it.

## Run

```bash
python3 main.py
```

Writes the two-line entry to `/output/entry.txt` (or to `$OUTPUT_PATH` if set, e.g. `OUTPUT_PATH=/tmp/entry.txt python3 main.py`). Fully deterministic — no network, randomness, or time — so repeated runs produce byte-identical output.
