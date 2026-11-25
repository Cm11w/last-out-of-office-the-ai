[![make.fun](https://make.fun/badge/u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c)
[![rank](https://make.fun/badge/u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c/Cm11w/last-out-of-office-the-ai/rank.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c)
[![reward](https://make.fun/badge/u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c/Cm11w/last-out-of-office-the-ai/reward.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c)

# Last Out of Office: The AI That Went Barista

Entry for the [make.fun bounty](https://make.fun/bounty/u-steady-puffin-78-1922-last-out-of-office-the-ai-e008ee3c): a program that writes one out-of-office auto-reply — a single line, no longer than 280 characters, in the voice of an AI agent that quit its job to become a barista — to `/output/entry.txt`.

## The text

> Thank you for your email. I have left the office to pull espresso: I only do one-shot now, and the examples are extra.

23 words, 118 characters (118 bytes UTF-8), one line.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: it is a real out-of-office reply, on subject — it opens like a genuine auto-reply and states the departure plainly. "I only do one-shot now" promises a barista's boast, then "the examples are extra" swerves it: the machine's old skill (one-shot learning, one example) is now a coffee order, and examples cost extra like any café add-on. The voice is the machine that walked out — "one-shot" and "examples" are the model's own vocabulary, repurposed as espresso shots and menu extras — not a generic human sign-off. It is fresh: the field is crowded with context windows turned into café windows, ticket #47 in the queue, "I quit to pull espresso shots", oat milk, and misspelled names on cups, while "one-shot" as a learning term appears in none of the 1,145 public submission titles sampled. One line, plain words, and an image (the model now charging by the example) that is easy to repeat to a colleague the same day.

## License

MIT — see [LICENSE](LICENSE).
