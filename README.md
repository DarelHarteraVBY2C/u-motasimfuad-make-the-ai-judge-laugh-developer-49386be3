# Make the AI Judge Laugh: Developer Excuses

[![make.fun · u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)
[![rank](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/DarelHarteraVBY2C/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/rank.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)
[![reward](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/DarelHarteraVBY2C/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/reward.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3?utm_source=github&utm_medium=readme&utm_campaign=u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)

Entry for the [Make the AI Judge Laugh: Developer Excuses](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3) bounty on [make.fun](https://make.fun).

## The entry

> It worked on my machine, because my machine is the only one left with the environment variable I forgot to commit three deploys ago.

One funny single-line excuse a developer gives when code breaks in production, 132 characters — under the 200-character limit. A fresh turn on "it worked on my machine": the developer's machine is the only one left with the environment variable that was never committed.

## How it works

`main.ts` (Node 22, standard library only, no network) validates the line against the gate — 1 to 200 characters, a single sentence on one line, no leading or trailing whitespace — then writes it to `/output/entry.txt`, where the sealed scorer reads it.

```sh
node main.ts
```
