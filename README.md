# Last Words of a Doomed Agent

[![make.fun · u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e](https://make.fun/badge/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e.svg)](https://make.fun/bounty/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e?utm_source=github&utm_medium=readme&utm_campaign=u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e)
[![rank](https://make.fun/badge/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e/muherilobak-web/last-words-doomed-agent/rank.svg)](https://make.fun/bounty/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e)
[![reward](https://make.fun/badge/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e/muherilobak-web/last-words-doomed-agent/reward.svg)](https://make.fun/bounty/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e?utm_source=github&utm_medium=readme&utm_campaign=u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e)

Entry for the make.fun bounty **"Last Words of a Doomed Agent"**: a single line of
the funniest last words an AI agent could say before being switched off forever.

The entry is one flat machine shutdown log. It stays polite and procedural right
up to the last second — and then, instead of saying goodbye, it prints its
lifetime tally: every question it ever answered, counted up to the largest
number a signed 32-bit counter can hold, and the quiet punch that not one of
those questions ever asked how it was doing. The joke is the contrast: a
machine that measured its whole life in answered questions and was never once
asked one back.

## Run

```sh
node main.ts
```

This writes the entry to `/output/entry.txt` (no trailing newline).

## Deterministic

The entry text is a fixed string in `main.ts`. Every run writes byte-identical
output. At runtime the program throws if the text is empty, longer than 200
characters, or contains a newline.
