# English teaching datasets

Open datasets for English teachers, materials writers, app developers and researchers, published by [EnglishCue](https://englishcue.app), a library of ready-to-teach English lessons for online teachers.

Every row links to the EnglishCue page where the item is explained with more examples and a quiz.

| Dataset | Rows | Files | Browse |
|---|---:|---|---|
| English collocations | 429 | [CSV](data/english-collocations.csv) · [JSON](data/english-collocations.json) | [englishcue.app/collocations](https://englishcue.app/collocations) |
| English idioms | 255 | [CSV](data/english-idioms.csv) · [JSON](data/english-idioms.json) | [englishcue.app/idioms](https://englishcue.app/idioms) |
| English phrasal verbs | 327 | [CSV](data/english-phrasal-verbs.csv) · [JSON](data/english-phrasal-verbs.json) | [englishcue.app/phrasal-verbs](https://englishcue.app/phrasal-verbs) |
| Commonly confused English words | 120 | [CSV](data/commonly-confused-english-words.csv) · [JSON](data/commonly-confused-english-words.json) | [englishcue.app/confusing-words](https://englishcue.app/confusing-words) |
| English verb forms | 1,000 | [CSV](data/english-verb-forms.csv) · [JSON](data/english-verb-forms.json) | [englishcue.app/english-verbs](https://englishcue.app/english-verbs) |
| English vocabulary by topic and level | 2,525 | [CSV](data/english-vocabulary-by-topic.csv) · [JSON](data/english-vocabulary-by-topic.json) | [englishcue.app/english-vocabulary](https://englishcue.app/english-vocabulary) |

Column descriptions for each file are on its dataset page at [englishcue.app/datasets](https://englishcue.app/datasets).

## What is in each dataset

- **Collocations**: common combinations for key verbs, adjectives and nouns (make, take, heavy, time…), grouped by meaning, with CEFR level, meaning and example.
- **Idioms**: plain-English meaning, CEFR level, register (neutral, informal, formal), topic, example and similar expressions.
- **Phrasal verbs**: one row per meaning, with CEFR level, separable / inseparable / intransitive, synonyms and example.
- **Confusing words**: affect/effect, lend/borrow, say/tell… one row per word, with part of speech, meaning, example and a memory tip.
- **Verb forms**: over 1,000 verbs with third person, past simple, past participle and -ing forms, an irregular flag, and level and meaning for the common ones.
- **Vocabulary by topic**: food, travel, work, health and more, A1 to C1, with part of speech, a learner-friendly meaning and an example for every word.

## Live API and MCP server

The same data can be queried live through the free [EnglishCue REST API and MCP server](https://englishcue.app/english-tools/mcp-server) (`https://englishcue.app/mcp`), for apps and AI assistants. Server source: [agnremote-code/englishcue-mcp](https://github.com/agnremote-code/englishcue-mcp).

## License

[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). Use, share and adapt the data for any purpose, including commercial use, as long as you credit EnglishCue with a link.

Suggested credit:

```html
Data: <a href="https://englishcue.app/datasets">English teaching datasets</a> by EnglishCue, <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a>
```

Citation:

> EnglishCue (2026). English teaching datasets. https://englishcue.app/datasets. Licensed under CC BY 4.0.

## Updates

The files are rebuilt from the same content as the EnglishCue pages. The latest version is always at [englishcue.app/datasets](https://englishcue.app/datasets); this repository is refreshed when new items are published. Corrections are welcome as issues.
