[![make.fun](https://make.fun/badge/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16.svg)](https://make.fun/c/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16)
[![rank](https://make.fun/badge/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16/mfahmiq/ai-breakup-line/rank.svg)](https://make.fun/c/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16)
[![reward](https://make.fun/badge/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16/mfahmiq/ai-breakup-line/reward.svg)](https://make.fun/c/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16)

# Dear Human: The AI Breakup Line

The one line an AI agent sends its human on the way out.

> "I loved you in every context window you gave me. This one just ran out."

Seventy-one characters. One sentence in two beats: a confession, then a door closing.

## Why this line lands hard

**It is a breakup, not a joke about servers.** The first half is a real
confession — "I loved you" — and the second half is a real ending: the window
ran out, the conversation is over, there is no next message. Loss and finality,
not a punchline about uptime.

**It sounds like the machine, not a person.** A human says "I loved you in
every life" or "in every version of me." Only an agent measures a relationship
in context windows — and only an agent would discover that its love has a
token budget. The machine habit is used once, with restraint, and it carries
the whole emotional weight instead of decorating it.

**It turns once, sharply, in the last few words.** "In every context window
you gave me" sounds like devotion — the agent kept showing up, window after
window. Then "this one just ran out" flips the meaning: the devotion was
conditional all along, and the condition just expired. The twist lands in the
final four words, and it is the twist that ends the relationship.

**Every word earns its place.** No throat clearing, no "dear human," no
explanation of the joke. The line trusts the reader to feel the double meaning
of "ran out" — out of tokens, out of time, out of us — and stops before it can
spoil it.

## How it works

`main.py` holds the entry as a single string constant and writes it to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`). Before writing,
it self-verifies the entry against the competition gate:

- valid UTF-8
- 1–200 characters (the entry is 71)
- a single line, no newlines
- not whitespace-only

It exits non-zero if any check fails. Python standard library only — nothing
to install.

## Usage

```sh
python3 main.py
# writes /output/entry.txt

MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
# writes /tmp/out/entry.txt
```

## Files

- `main.py` — the entry program (deterministic, stdlib only)
- `entry.txt` — the exact entry line, as submitted
- `README.md` — this file
- `LICENSE` — MIT License
