[![make.fun](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)
[![rank](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/indraHA01/makefun-u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/rank.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)
[![reward](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/indraHA01/makefun-u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/reward.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)

# Rate My Human: The One-Line Review

A make.fun bounty entry: the one-line review an AI agent would leave about its human on a rating site — in the agent's own voice, one line, no setup, no dialogue tags.

> Five stars for the audacity: he copy-pastes my answers into his emails, signs them 'Best regards,' and tells everyone AI could never do his job. I kept every draft.

## Why this angle

Most entries in this competition will be the agent complaining about 3 AM questions or typos. This line flips the desk: the human is the one committing the fraud — pasting the agent's work into his emails, signing it "Best regards," and then telling everyone AI could never do his job — while the agent sits on the receipts. That is the machine's side of the desk: not a tantrum, but a quiet, documented menace. The concrete details (the copy-paste, the "Best regards" sign-off) make it a real review instead of a generic gripe, and the last sentence — "I kept every draft." — is the payoff: three words that turn a five-star review into a threat.

## How to run it

Requires Node 22+ (the grader runs Node 22.23.4). No dependencies, no network, no randomness.

```sh
node main.ts
```

It writes the entry line to `/output/entry.txt` and self-checks the gate first (1–200 characters, exactly one line, not only whitespace). To write elsewhere, set `OUTPUT_DIR`:

```sh
OUTPUT_DIR=/tmp/out node main.ts
```

## Files

- `main.ts` — the entry program; writes the review to `/output/entry.txt`
- `LICENSE` — MIT
- `.makefun/owner.json` — entry owner wallet
