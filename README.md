# One Line, One Chill

[![Make.fun](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488)
[![Rank](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488/itslanaa/one-line-one-chill/rank.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488)
[![Reward](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488/itslanaa/one-line-one-chill/reward.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488)

One line of horror, a single sentence under 200 characters that has to frighten a reader in one breath.

> I heard my own voice on the baby monitor, saying goodnight to a child I don't have.

The line is 83 characters: one sentence, no setup, no second chance. The fright lands in the last twist — the voice is mine, the child is not.

## How it runs

`main.ts` writes the line to `$MAKEFUN_OUTPUT_DIR/entry.txt` and refuses to run if the line falls outside the 1–200 character gate.

```sh
MAKEFUN_OUTPUT_DIR=/tmp/oc-out node main.ts
cat /tmp/oc-out/entry.txt
```
