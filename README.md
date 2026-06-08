# WWII Emotion Timeline

An interactive timeline visualizing emotional sentiment across key World War II events, built for the *Introduction to Digital History* course at KAIST.

**Live site:** https://nazar-maker.github.io/dh-project/

## About

The visualization charts emotion over the course of the war, drawn from transcribed wartime audio and event data. It's a single self-contained static page rendered with [D3.js](https://d3js.org/).

## Development

The site lives in [`index.html`](index.html). To make changes, edit that file, then:

```bash
git commit -am "Update timeline"
git push
```

GitHub Pages rebuilds automatically within a minute.

## Methodology

The underlying analysis (audio transcription via Whisper and emotion scoring) is documented in the project's findings report. The timeline data was derived from WWII event records and sentiment analysis of transcribed speeches and broadcasts.
