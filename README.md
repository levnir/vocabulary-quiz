# English–Hebrew Vocabulary Quiz

A fun, browser-based quiz app for practising English–Hebrew vocabulary, with a focus on irregular verbs.

## Features

- Bidirectional translation: English → Hebrew and Hebrew → English
- Irregular verb support: asks for both the infinitive and the past tense
- 3 attempts per question (with hearts); the correct answer is revealed after 3 wrong attempts
- Score tracking: correct/wrong counters, current streak, and best streak
- Letter grade at the end (A+ through F)
- Sound effects, confetti animations, and a virtual Hebrew keyboard
- No installation required — just open `index.html` in any browser

## How to update the word list

Edit `vocabulary.js` before each exam. Each entry follows one of these formats:

```js
{ en: "hello", he: "שלום" }                          // regular word
{ en: "to run", past: "ran", he: "לרוץ" }            // irregular verb
```

## Live demo

[https://levnir.github.io/vocabulary-quiz/](https://levnir.github.io/vocabulary-quiz/)

## Files

| File | Description |
|------|-------------|
| `index.html` | The quiz app |
| `vocabulary.js` | The word list — edit this before each exam |
| `vocabulary1.txt` / `vocabulary2.txt` | Source vocabulary in the same format, for reference |
| `VocabularyExtractPrompt.txt` | Prompt used to extract vocabulary from the PDF |
| `Irregular Verbs V1, V2.pdf` | Original source document for the irregular verbs list |
