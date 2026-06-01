# Italian Learning App

A lightweight Italian language learning app with vocabulary flashcards, grammar lessons, quizzes, and progress tracking.

**Live demo**: https://YOUR_USERNAME.github.io/italian-app

## Features

- Flashcards — 38 words across 7 categories, filter by category
- Quiz — 10-question multiple choice with scoring
- Grammar — 8 lessons from beginner to intermediate, with examples
- Progress — accuracy tracking and per-category progress bars
- Progress is saved in localStorage (persists between sessions)

## Tech

Pure HTML, CSS, and JavaScript — no frameworks, no build step, no dependencies except the Tabler icons font.

## How to deploy

See setup instructions below.

## Adding vocabulary

Open `index.html` and find the `VOCAB` array. Add entries in this format:

```js
{id: 39, it: 'sole', en: 'sun', cat: 'nature', diff: 1},
```

## Adding grammar topics

Find the `GRAMMAR` array and add entries in this format:

```js
{
  id: 9,
  title: 'Imperfetto — past habits',
  diff: 2,
  explanation: 'Used for repeated past actions or descriptions...',
  examples: [
    'Da bambino mangiavo la pasta ogni giorno. — As a child I ate pasta every day.',
  ]
}
```
