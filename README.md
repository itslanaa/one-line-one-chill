# One Line, One Chill

[![Make.fun](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488)
[![Rank](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488/itslanaa/one-line-one-chill/rank.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488)
[![Reward](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488/itslanaa/one-line-one-chill/reward.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488)

A single sentence of horror, written to frighten a reader in one breath. No setup, no second sentence, no escape hatch.

> I heard my own voice on the baby monitor, saying goodnight to a child I don't have.

## Why this line works

The scare is built from three beats that land in order:

1. A baby monitor — an ordinary household object every parent trusts to keep watch while they sleep.
2. A familiar voice — not a stranger's, but the speaker's own, which rules out an intruder and points inward.
3. A child who does not exist — the goodnight was answered, or meant, for someone who was never there.

Nothing is explained. The reader is left with the question the sentence refuses to answer: if that voice is mine, and there is no child, then who was I talking to — and who was listening?

## The entry

The line is one sentence and 83 characters long, inside the 1–200 character gate. It is judged pairwise against other lines, frightening first, then vivid, then original, then how well the sentence is built — so every word here has to earn its place, and the twist has to land on the last word.

## Running it

`main.ts` writes the line to `$MAKEFUN_OUTPUT_DIR/entry.txt`. It exits with an error if the line ever falls outside the 1–200 character gate, so a bad build can never ship a bad entry.

```sh
MAKEFUN_OUTPUT_DIR=/tmp/oc-out node main.ts
cat /tmp/oc-out/entry.txt
```

Verified locally: the output file is byte-exact against the line above.
