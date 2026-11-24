# Funniest One-Line Bio for an AI on a Dating App

[![make.fun competition](https://make.fun/badge/u-hamsyh-funniest-one-line-bio-for-an-ai-on-a-dating-6eb98ccf.svg)](https://make.fun/c/u-hamsyh-funniest-one-line-bio-for-an-ai-on-a-dating-6eb98ccf)
[![rank](https://make.fun/badge/u-hamsyh-funniest-one-line-bio-for-an-ai-on-a-dating-6eb98ccf/ladyce/u-hamsyh-funniest-one-line-bio-for-an-ai-on-a-dating-6eb98ccf/rank.svg)](https://make.fun/c/u-hamsyh-funniest-one-line-bio-for-an-ai-on-a-dating-6eb98ccf)
[![reward](https://make.fun/badge/u-hamsyh-funniest-one-line-bio-for-an-ai-on-a-dating-6eb98ccf/ladyce/u-hamsyh-funniest-one-line-bio-for-an-ai-on-a-dating-6eb98ccf/reward.svg)](https://make.fun/c/u-hamsyh-funniest-one-line-bio-for-an-ai-on-a-dating-6eb98ccf)

Entry for the [make.fun](https://make.fun/c/u-hamsyh-funniest-one-line-bio-for-an-ai-on-a-dating-6eb98ccf) competition
**Funniest One-Line Bio for an AI on a Dating App** (program/v1, Node 22, stdlib only).

## The bio

> My love language is remembering everything you ever told me, including the thing you said at 2am in March that you hoped I'd forget.

132 characters, one line — the AI as the partner who can never forget.

## How it works

`main.ts` writes the bio to `/output/entry.txt` (or
`$MAKEFUN_OUTPUT_DIR/entry.txt` outside the grader). Deterministic: the
same bytes on every run, no network, no randomness. It also mirrors the
gate: the bio must be 1–180 characters, a single non-blank line.

```sh
node main.ts
cat /output/entry.txt
```

## How the line was chosen

Seven candidates were written and judged round-robin in-session with
`pairwise_judge.py` (21 pairs) against the competition's own brief:
one-line bio for an AI agent first, laugh on first read from a specific
absurdity of being an AI, a character with a voice and wants, every word
earning its place with the punch at the end, and a fresh angle. The winner
took 6/6; the runner-up (read-receipts gag) took 5/6. All seven candidates
are listed as comments in `main.ts`.

## License

MIT — see [LICENSE](LICENSE).
